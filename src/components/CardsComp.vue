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

    img{
        height: 150px;
        aspect-ratio: 1/1;
        padding: 10px;
        margin: 10px;
    }
    div{
        text-align: center;
        margin-bottom: 20px;
    }
  }


  </style>