<template>
  <main>
        <div class="container">
            <div class="content">
                <div class="box">
                    <p>Contenuto</p>
                </div>
            </div>
            <div class="products">
               <img src="@/img/buy-comics-digital-comics.png" alt="" class="prod-img">
               <a href="#">Digital Comics</a>

               <img src="@/img/buy-comics-merchandise.png" alt="" class="prod-img">
               <a href="#">Comics Merchandise</a>

               <img src="@/img/buy-comics-shop-locator.png" alt="" class="prod-img">
               <a href="#">Shop Locator</a>

               <img src="@/img/buy-comics-subscriptions.png" alt="" class="prod-img">
               <a href="#">Subscriptions</a>

               <img src="@/img/buy-dc-power-visa.svg" alt="" class="prod-img">
               <a href="#">Dc Power Visa</a>

            </div>


        </div>
  </main>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">

    main{
        .container{
            .content{
                background: black;
                color: white;
                font-size: 35px;
                height: 100px;
                margin-top: 10px;
                    .box{
                       p{
                           padding: 10px;
                       } 
                    }
                }

            .products{
                background: #0c7ceb;
                height: 200px;  
                padding: 50px;

                    .prod-img{
                        width: 100px;
                        height:100px;
                        padding: 0 20px;
                        vertical-align: middle;
                    }

                    a{
                        color: white;
                        text-decoration: none;
                        font-size: 20px;
                    }
       
                }
        }
    }
    
    
    
    
</style>