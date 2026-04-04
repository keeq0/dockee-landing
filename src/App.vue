<template>
  <div class="app-container">
    <ParticleBackground
      :particle-count="20"
      :connect-distance="150"
      :mouse-connect-distance="200"
      color="#6C67FD"
      :max-speed="1.2"
    />
    <TheHeader />
    <MainSection />
    <AboutSection />
  </div>
</template>

<script>
import AboutSection from './components/AboutSection/AboutSection.vue';
import MainSection from './components/MainSection/MainSection.vue';
import TheHeader from './components/TheHeader/TheHeader.vue';
import ParticleBackground from './components/ParticleBackground.vue';

export default {
  components: {
    TheHeader,
    MainSection,
    AboutSection,
    ParticleBackground,
  },
};
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

section {
  padding: 50px 0;
}

.color-blue {
  color: #6C67FD;
}

@media (max-width: 576px) {
  section {
    padding: 30px 0;
  }
}

.app-container {
  position: relative;
  z-index: 1;
  background: transparent;
}
</style>