<template>
  <header>
      <div class="container">

        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <nav>
            <ul>
                <li>
                    <a href="#">Characters</a>
                    <a href="#">Comix</a>
                    <a href="#">Movies</a>
                    <a href="#">Tv</a>
                    <a href="#">Games</a>
                    <a href="#">Collections</a>
                    <a href="#">Videos</a>
                    <a href="#">Fans</a>
                    <a href="#">News</a>
                    <a href="#">Shop</a>
                </li>
            </ul>
        </nav>

      </div>

  </header>
</template>



<script>
export default {
    name:'Header'
}
</script>

<style lang="scss" scoped>

    header{
        // display: flex;       

        .container{
            display: flex;
            justify-content: space-between; 

            .logo{
                display: flex;
                align-items: center;

                img{
                    height: 70px;
                    
                }
            }
        
            nav{
                display: flex;

                ul{
                    display: flex;
                    list-style: none;
                    justify-content:center;

                    li a{
                        display: inline-block;
                        text-decoration: none;
                        color: black;
                        padding: 30px 10px;
                        margin: 0 5px;
                        line-height: 60px;

                        &.active , &:hover{           
                            color: aquamarine;
                            border-bottom: 3px solid lightblue;
                        }
                    }
                }
            }
        }
    }

    

</style>