<template>
  <div id="app">
    <HeaderComp/>
    <MainComp/>
    <BlueComp/>
    <FooterComp/>
    <LastComp/>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import BlueComp from './components/BlueComp.vue'
import FooterComp from './components/FooterComp.vue'
import LastComp from './components/LastComp.vue'
export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    BlueComp,
    FooterComp,
    LastComp
  }
}
</script>

<style lang="scss">

body{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

ul{
  list-style-type: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: lightgray;
  margin-top: 10px;
}
</style>
