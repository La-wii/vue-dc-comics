<template>
  <header class="clearfix">

    <div class="logo">
      <img src="../img/dc-logo.png" alt="">
    </div>

    <nav>
      <ul>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">Tv</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Collectibles</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">Fans</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Shop</a></li>
      </ul>
    </nav>

  </header>

</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header{
    height: 100px;
      .clearfix::after{
        display: table;
        content: '';
        clear: both;
      }
      .logo{
        float: left;
        margin-left: 100px;
      }
    nav{
      float: right;
      padding-top: 25px;
      ul {
      justify-content: flex-end;
      list-style-type: none;
      padding: 0;
      margin-right: 100px;
        li {
        display: inline-block;
        margin: 0 10px;
          &:hover{
            padding-bottom: 30px;
            border-bottom: 5px solid blue;
          }
          a {
          color: black;
          text-decoration: none;
          }
        }
      }
    }
}



</style>
