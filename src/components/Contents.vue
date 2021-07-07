<template>
  <div class="container-cards">
      <div class="card">
        <img :src="prod.thumb" alt="">
      </div>
  </div>
</template>

<script>
export default {
  name: "contents",
  props: ["prod"]
}
</script>

<style scoped lang="scss">
.container-cards{
  width: calc(100% / 6 - 20px);
  height: 200px;
  margin-bottom: 110px;
  .card{  
    margin: 20px 10px;
      img{
        height: 100%;
      }
    }
}



</style>