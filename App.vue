<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyButtonVue msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>

import MyButtonVue from './components/MyButton.vue'

export default {
  name: 'App',
  components: {
    MyButtonVue
  }
}
</script>




<style>



</style>
