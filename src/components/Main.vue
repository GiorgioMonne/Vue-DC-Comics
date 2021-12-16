<template>
  <main>

    <div class="container-tre"> 

    </div>

     <div class="container-due">
        <Book/>
    </div>

  </main>
</template>

<script>

import Book from './sections/Book.vue';

export default {
    name:'Main',
    components:{
        Book
    }
}
</script>

<style lang="scss" scoped>
    main{

        .container-due{
            background-color: black;
            padding: 10px 10px;
        }

        .container-tre{
            background-image: url('../assets/img/jumbotron.jpg');
            background-size: cover;
            height: 280px;
        }

        .load{
        background-color: rgb(32, 147, 255);
        margin: 30px;
        padding: 7px 40px;
        color: white;
        font-size: 12px;
        margin: 20px auto; 
    }

    }
</style>