<template>
  <Home msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    Home: HomePage
}
}
</script>

<style>
@import './styles/index.css'
</style>
