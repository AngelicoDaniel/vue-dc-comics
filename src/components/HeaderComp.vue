<template>
  <div>
    <img src="../assets/img/dc-logo.png" alt="DC-logo">
    <nav>
        <ul>
          <li>
            <a href="#">CHARACTERS</a>
          </li>
          <li class="active">
            <a href="#">COMICS</a>
          </li>
          <li>
            <a href="#">MOVIES</a>
          </li>
          <li>
            <a href="#">TV</a>
          </li>
          <li>
            <a href="#">GAMES</a>
          </li>
          <li>
            <a href="#">COLLECTIBLES</a>
          </li>
          <li>
            <a href="#">SHOP</a>
          </li>
          <li>
            <a href="#">VIDEOS</a>
          </li>
          <li>
            <a href="#">FANS</a>
          </li>
          <li>
            <a href="#">NEWS</a>
          </li>
          <li>
            <a href="#">SHOP</a>
          </li>

      </ul>
    </nav>

  </div>
</template>

<script>
export default {
  name: 'HeaderComp'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div{
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin: 5px;
}

.active{
  border-bottom: 2px solid #0282f9;
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  text-decoration: none;
  color: black;
}
</style>
