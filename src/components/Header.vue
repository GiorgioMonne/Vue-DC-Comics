<template>
  <header>
      <div class="container">

        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <nav>
            <ul>
                <li v-for="(link, index) in links" :key="index"><a :class="{active : isActive}"  href="link.url">{{link.text}}</a></li>
            </ul>
        </nav>

      </div>

  </header>
</template>



<script>
export default {
    name:'Header',
    data(){

        return{ 

            links: [
                {
                    text: 'CHARACTERS',
                    url: '#',
                    current: 'false',
                },
                {
                    text: 'COMICS',
                    url: '#',
                    current: 'true',
                },
                {
                    text: 'MOVIES',
                    url: '#',
                    current: 'false',
                },
                {
                    text: 'TV',
                    url: '#',
                    current: 'false',
                },
                {
                    text: 'GAMES',
                    url: '#',
                    current: 'false',
                },
                {
                    text: 'COLLECTIBLES',
                    url: '#',
                    current: 'false',
                },
                {
                    text: 'VIDEOS',
                    url: '#',
                    current: 'false',
                },
                {
                    text: 'FANS',
                    url: '#',
                    current: 'false',
                },
                {
                    text: 'NEWS',
                    url: '#',
                    current: 'false',
                },
                {
                    text: 'SHOP',
                    url: '#',
                    current: 'false',
                },
            ]            
        }
    }
}
</script>

<style lang="scss" scoped>

    header{
        height: 120px;      

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
                        line-height: 57px;
                        font-size: 12px;

                        &.active , &:hover{           
                            color: rgb(85, 191, 226);
                            border-bottom: 3px solid rgb(85, 191, 226);
                        }
                    }
                }
            }
        }
    }
</style>