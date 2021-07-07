<template>
    <div class="container">

        <footer>
            <div class="link-content-clearfix">
                    <div class="side">
                    <h3>dc comics</h3>
                    <div class="dc-comics">
                        <ul>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        </ul>
                    </div>

                    <h3>shop</h3>
                    <div class="shop">
                        <ul>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        </ul>
                    </div>
                </div>

                
                <div class="dc">
                    <h3>dc</h3>
                    <ul>
                    <li><a href="#">link</a></li>
                    <li><a href="#">link</a></li>
                    <li><a href="#">link</a></li>
                    </ul>
                </div>
                
                <div class="sites">
                    <h3>sites</h3>
                    <ul>
                    <li><a href="#">link</a></li>
                    <li><a href="#">link</a></li>
                    <li><a href="#">link</a></li>
                    </ul>
                </div>
            </div>

        </footer>

        <div class="footer-bottom">
            <div class="button">
                <button>Sign-up now</button>
            </div>

            <div class="social">
                <span>Follow us</span>
                <img src="../img/footer-facebook.png" alt="">
                <img src="../img/footer-periscope.png" alt="">
                <img src="../img/footer-pinterest.png" alt="">
                <img src="../img/footer-twitter.png" alt="">
                <img src="../img/footer-youtube.png" alt="">

            </div>
        </div>

    </div>
    
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">

    footer{
        background-image: url(../img/footer-bg.jpg);
        height: 400px;
        padding: 50px;

            .link-content-clearfix{

                .side, .dc, .sites{
                float: left;
                margin-right: 40px;
                

                    .dc-comics{
                    margin-bottom: 20px
                    }

                    h3{
                    text-transform: uppercase;
                    font-size: 20px;
                    color: white;
                }

                ul {

                    li{
                        list-style: none;
                    
                            a{
                                text-decoration: none;
                                color: lightgray;
                            }

                    }
                }

            }
            


        }
        
           
    }
    
    .footer-bottom{
            background-color: #1c1c1c;  
            height: 150px;
            padding: 50px;
                .button{
                    float: left;
                    button{
                        padding: 10px 20px;
                        background-color: black;
                        border: 4px solid blue;
                        color: white;
                        text-transform: uppercase;
                    }
                }

                .social{
                    float: right;
                    span{
                        font-size: 30px;
                        color: blue;
                        text-transform: uppercase;
                        font-weight: 400;
                    }
                    span, img{
                        margin-right: 30px;
                    }   
                }
    }
    
</style>