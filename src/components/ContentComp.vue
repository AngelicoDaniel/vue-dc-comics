<template>
    <div class="black">
       <h2>--&gt; Content goes here &lt;-- </h2>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HeaderComp'
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
.black{
    color: white;
    background-color: #1B1C1D;
    text-align: start;
}
h2{
    width: 80%;
    margin: auto;
    padding: 1.8em;
}
  </style>