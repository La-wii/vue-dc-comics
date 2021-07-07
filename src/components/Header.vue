<template>
  <header class="clearfix">

    <div class="logo">
      <img src="../img/dc-logo.png" alt="">
    </div>

    <nav>
      <ul>

        <li v-for="(link, index) in link" :key="index"> <a :href="link.url">{{link.text}}</a></li>
        <!-- <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">Tv</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Collectibles</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">Fans</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Shop</a></li> -->
      </ul>
    </nav>

  </header>

</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
  data (){
    return {
      link :[
        {
          text: 'Characters',
          url:'#',
          current: false
        },
        {
          text: 'Comics',
          url:'#',
          current: false
        },
        {
          text: 'Movies',
          url:'#',
          current: false
        },
        {
          text: 'Tv',
          url:'#',
          current: false
        },
        {
          text: 'Games',
          url:'#',
          current: false
        },
        {
          text: 'Collectibles',
          url:'#',
          current: false
        },
        {
          text: 'Videos',
          url:'#',
          current: false
        },
        {
          text: 'Fans',
          url:'#',
          current: false
        },
        {
          text: 'News',
          url:'#',
          current: false
        },
        {
          text: 'Shop',
          url:'#',
          current: false
        },
      ]
    }
  }
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
            padding-bottom: 45px;
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
