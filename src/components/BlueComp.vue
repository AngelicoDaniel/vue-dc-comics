<template>
    <div>
    <nav>
      <ul class="loghi">
          <li>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>DIGITAL COMICS</span>
          </li>
          <li>
            <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <span>DC MERCHANDISE</span>
          </li>
          <li>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <span>SUBSCRIPTION</span>
          </li>
          <li>
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <span>COMIC SHOP LOCATOR</span>
          </li>
          <li>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>DC POWER VISA</span>
          </li>

      </ul>
    </nav>
    </div>
  </template>
  
  <script>
  export default {
    name: 'BlueComp'
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
div{
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #2F79F7;
}
.loghi{
    color: white;
    padding: 20px;
    img{
        width: 40px;
        vertical-align: middle;
        padding: 10px;
    }

}


ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  align-items: center;
}

  </style>