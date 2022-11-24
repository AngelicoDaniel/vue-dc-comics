<template>
    <div class="card">

       <img :src="dettagliCard.thumb" alt="">
       <div>{{dettagliCard.series}}</div>

    </div>
  </template>
  
  <script>


  export default {
    name: 'CardsComp',
    props: {
        dettagliCard: Object
    }
  }
  </script>
  
 
  <style scoped lang="scss">

  .card{
    width: calc(100% / 6);
  }


  </style>