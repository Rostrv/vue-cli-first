<template>
  <div id="app">
    <firstTitle/>
    <heroImg/>
  </div>
</template>
<script>
import FirstTitle from './components/firstTitle.vue'
import heroImg from './components/heroImg.vue'

export default {
  name: 'App',
  components: {
    FirstTitle,
    heroImg
  }

}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
