<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <NavigationBar />
  <IdCard/>
</template>

<script>
import IdCard from './components/IdCard.vue'
import NavigationBar from './components/NavigationBar.vue';
export default {
  name: 'App',
  components: {
    IdCard,
    NavigationBar
  }
}
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
