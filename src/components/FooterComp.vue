<template>
    <div class="bg">

     <div class="lists">
        <div>
            <ul>
                <h3>DC COMICS</h3>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <ul>
                <h3>SHOP</h3>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
        </div>
        <div>
            <ul>
                <h3>DC</h3>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshop</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
        </div>
        <div>
            <ul>
                <h3>SITES</h3>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>
     </div>

     <div class="dc-logo">
        <img src="../assets/img/dc-logo-bg.png" alt="">
     </div>  

    </div>
  </template>
  
  <script>
  export default {
    name: 'FooterComp'
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
  
.bg{
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-color: black;
    height: 400px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    overflow: hidden;
}

ul{
    text-align: start;
}
li{
    font-size: 12px;
    color: gray;
}

.lists{
    display: flex;
}


  </style>
  