<template>
    <header class="header">
        <TheLogo />
        <TheNavigation />
        <UserActions />
    </header>
</template>
<script>
import TheLogo from './TheLogo.vue';
import TheNavigation from './TheNavigation.vue';
import UserActions from './UserActions.vue';

export default {
    components: {
        TheLogo,
        TheNavigation,
        UserActions
    }
}
</script>
<style scoped>

.header {
    margin: 20px auto;
    width: 1200px;
    height: 45px;
    background: #FFF;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
    
</style>