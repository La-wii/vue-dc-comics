<template>
  <main>
        <div class="jumbotron"></div>
        <div class="container">
            <div class="content">
                <div class="box">
                    <!-- <p>Contenuto</p> -->
                    <button>Current Series</button>
                    <div class="container">
                        <div class="cards">
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                            <div class="card"></div>
                        </div>

                    </div>
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
// import Product from "@/data/Product.js";
export default {
    // name:
    // data(){

    // }
}
</script>

<style scoped lang="scss">

    main{
        .jumbotron{
            background-image: url(../img/jumbotron.jpg);
            background-size: cover;
            height: 300px;
        }
        .container{
            .content{
                background: black;
                color: white;
                font-size: 35px;
                // height: 100px;
                // margin-top: 10px;
                    .box{
                        position: relative;
                        button {
                            padding: 10px 20px;
                            background-color: blue;
                            color: white;
                            font-size: 20px;
                            text-transform: uppercase;
                            position: absolute;
                            left: 250px;
                            bottom: 470px;
                        }
                        .container{
                           width: 80%;
                           margin: 0 auto;
                            .cards{
                                display: flex;
                                flex-wrap: wrap;
                                    .card{
                                        width: calc(100% / 6 - 20px);
                                        height: 200px;
                                        background-color: blueviolet;
                                        margin: 20px 10px; 
                                    }
                                }
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