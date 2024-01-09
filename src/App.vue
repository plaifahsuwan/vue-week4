<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <AboutPage />
  <ContactPage />
</template>

<script>
import AboutPage from './components/HelloWorld.vue'
import ontactPage from './components/HelloWorld.vue'
export default {
  name: 'App',
  components: {
    AboutPage,
    ContactPage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
