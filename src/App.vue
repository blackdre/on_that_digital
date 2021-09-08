<template>
  <!-- <router-view /> -->
  <About />
  <Services />
  <Carousel />
  <Footer />
</template>

<script>
import Footer from "./components/layouts/Footer.vue";
import Carousel from "./components/layouts/Carousel.vue";
import Services from "./components/layouts/Services.vue";
import About from "./components/About.vue";
export default {
  components: { Footer, Carousel, Services, About },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
