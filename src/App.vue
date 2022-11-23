<template>
  <div id="app">
    <HeaderComp/>
    <ContentComp/>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import ContentComp from './components/ContentComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp
  }
}
</script>

<style lang="scss">

body{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
