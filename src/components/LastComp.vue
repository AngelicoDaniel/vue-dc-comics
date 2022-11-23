<template>
    <div class="bg">
        <h3 class="signUp">SIGN-UP NOW!</h3>
        <div class="followUs">
            <h3>FOLLOW US</h3>
            <div>
                <img src="../assets/img/footer-facebook.png" alt="Facebook">
                <img src="../assets/img/footer-twitter.png" alt="Twitter">
                <img src="../assets/img/footer-youtube.png" alt="YouTube">
                <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
                <img src="../assets/img/footer-periscope.png" alt="Periscope">
            </div>
        </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'LastComp'
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
.bg{
    background-color: #2D2C2D ;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.followUs{
    display: flex;
    align-items: center;
}
img{
    padding: 15px
}

h3{
    color: #3B7CFF;
}

.signUp{
    color: white;
    padding: 15px;
    border: 2px solid #3B7CFF;
}
  </style>