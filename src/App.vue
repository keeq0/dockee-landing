<template>
  <TheHeader />
  <MainSection />
</template>

<script>
import MainSection from './components/MainSection/MainSection.vue';
import TheHeader from './components/TheHeader/TheHeader.vue';



export default {
  components: {
    TheHeader,
    MainSection
  }
}
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
  list-style: none;
  text-decoration: none;
}

a {
  color: #000;
}

h1 {
  padding-bottom: 20px;
}

/* -- Colors -- */

.color-blue {
  color: #6C67FD;
}



</style>
