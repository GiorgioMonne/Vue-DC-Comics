<template>
  <footer>
      <div class="container-due">

        <div class="sopra">

              <div class="card">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="#">DIGITAL COMIX</a>
              </div>

              <div class="card">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <a href="#">DC MERCHANDISE</a>
              </div>

              <div class="card">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <a href="#">SUBSCRIPTION</a>
              </div>

              <div class="card">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <a href="#">COMIC SHOP LOCATION</a>
              </div>

              <div class="card">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <a href="#">DC POWER VISA</a>
              </div>

        </div>

        <div class="container-due">
            <div class="container">
                <div class="middle">
                    <ul>
                        <li>
                            <h2>DC COMICS</h2>
                            <a href="#">Characters</a>
                            <a href="#">Comics</a>
                            <a href="#">Movies</a>
                            <a href="#">TV</a>
                            <a href="#">Games</a>
                            <a href="#">Videos</a>
                            <a href="#">News</a>

                            <h2>SHOP</h2>
                            <a href="#">Shop DC</a>
                            <a href="#">Shop DC Collectibles</a>

                        </li>


                        <li>
                            <h2>DC</h2>
                            <a href="#">Terms Of Use</a>
                            <a href="#">Privacy policy (New)</a>
                            <a href="#">Ad Choices</a>
                            <a href="#">Advertising</a>
                            <a href="#">Jobs</a>
                            <a href="#">Subscriptions</a>
                            <a href="#">Talent Workshops</a>
                            <a href="#">CPSC Certificaties</a>
                            <a href="#">Ratings</a>
                            <a href="#">Shop Help</a>
                            <a href="#">Contact Us</a>
                        </li>

                        <li>
                            <h2>SITIES</h2>
                            <a href="#">DC</a>
                            <a href="#">MAD Magazine</a>
                            <a href="#">DC Kids</a>
                            <a href="#">DC Universe</a>
                            <a href="#">DC Power Visa</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

    <div class="container-tre">
        <div class="container">
            <div class="sotto">

                <div class="bottom">
                    <button >
                        SIGN-UP NOW!
                    </button>
                </div>

                <div class="destra">
                    <h2>FOLLOW US</h2>
                    <ul>
                        <li>
                            <img src="../assets/img/footer-facebook.png" alt="">
                            <img src="../assets/img/footer-twitter.png" alt="">
                            <img src="../assets/img/footer-youtube.png" alt="">
                            <img src="../assets/img/footer-pinterest.png" alt="">
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </li>
                    </ul>
                </div>

            </div>
        </div>
    </div>

  </footer>
</template>

<script>
export default {
    name:'Footer'
}
</script>

<style lang="scss" scoped>

    footer{
            .sopra{
                background-color: rgb(11, 146, 236);
                display: flex;
                justify-content: center;

                .card{ 
                    height: 100%;
                    padding: 30px 15px;
                    
                    img{
                        height: 45px;
                        width: 35px;
                        vertical-align: middle;
                        // background-color: aquamarine;
                    }

                    a{
                        text-decoration: none;
                        color: white;
                        padding: 30px 10px;
                        margin: 0 5px;
                        line-height: 60px;
                        font-size: 10px;

                        &.active , &:hover{           
                            color: aquamarine;
                            // border-bottom: 3px solid lightblue;
                        }
                    }
                }
            }

        .container-due{
            background-image: url('../assets/img/footer-bg.jpg');

            .container{

                .middle{

                    ul{
                        display: flex;
                        padding: 10px 10px;

                        li{
                            display: flex;
                            flex-direction: column;
                            margin: 15px 10px;

                            h2{
                                margin: 5px 0;
                                font-size: 16px;
                            }

                            a{
                                text-decoration: none;
                                font-size: 12px;
                                color: white;
                                opacity: 0.3;

                            }
                        }  
                    }
                }
            }
        }

        .container-tre{
            background-color: rgb(73, 73, 73);
            .sotto{
                display: flex;
                justify-content: space-between;
                align-items: center;
            
                .bottom{

                    button{
                        padding: 5px;
                        background-color:rgb(73, 73, 73);
                        color: white;
                        font-weight: bold;
                        border: 1px solid rgb(63, 63, 233);
                        margin: 20px auto;
                        font-size: 12px;
                    }
                }

                .destra{
                    display: flex;

                    h2{
                        display: flex;
                        margin: auto 10px;
                    }

                    ul{
                        display: flex;
                        list-style: none;

                        li{
                            margin: auto 10px;

                            img{
                                height: 30px;
                                width: 30px;
                                margin: auto 5px;
                                vertical-align: middle;
                                border-radius: 50%;
                                cursor: pointer;
                            } 
                        }
                    }
                }
            }
            
        }
    }

</style>