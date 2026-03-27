<template>
    <a href="#" class="logo">
        <div class="logo__rectangle"><div class="logo__circle"></div></div>
        <p class="logo__text">Doсkee</p>
    </a>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .logo {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 10px;
    }

    .logo__rectangle {
        width: 30px;
        height: 30px;
        border-radius: 10px;
        background: #6C67FD;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .logo__circle {
        width: 10px;
        height: 10px;
        border-radius: 100%;
        background: #FFF;
    }

    .logo__text {
        font-size: 28px;
        font-weight: 800;
    }
</style>