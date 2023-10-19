<script>
import Navbar from './partials/Navbar.vue';

export default {
    name: 'Header',
    components: {
       Navbar 
      }
}
</script>

<template>
  <header>
    <div class="top-bar d-flex justify-content-around">
      <div>
        <img src="../assets/img/logoTop.png" alt="">
      </div>
      <Navbar />
    </div>
  </header>
</template>



<style lang="scss" scoped>
header{
  height: 900px;
  background-image: url(../assets/img/jumbotron.jpeg);
  background-size: cover;
  background-position: center;
}

img{
  margin-top: 25px;
}

</style>