<script>

</script>

<template>
<header>
  <div class="container">
    <img src="../../img/favicon.ico" alt="logo" class="logo">
    <nav class="navbar">
      <ul>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Collectibles</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">Fans</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Shop</a></li>
      </ul>
    </nav>
  </div>
</header>
</template>

<style lang="scss" scope>

header {
  text-align: center;
  padding: 20px 0;

  .container{
    display: flex;
    justify-content: space-between;
    width: 1000px;
    margin: auto;
  }
  .logo {
    width: 100px;
  }

  .navbar {
    padding: 15px 0;

    ul {
      list-style-type: none;
      display: flex;
      justify-content: center;
      gap: 20px;

      li {
        
        a {
          text-decoration: none;
          font-size: 16px;
          &:active {
            border-bottom: 20px blue;
          }
        }
      }
    }
  }
}
</style>
npm,