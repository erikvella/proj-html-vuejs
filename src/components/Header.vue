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

    <div class="container my-5 ">
      <h1 class="text-center">MAKE A DIFFERENCE</h1>
      <p class="text-center">
        As long as poverty, injustice & inequality persist, none of us can truly rest
      </p>
    </div>
    <div class="container d-flex justify-content-center">
      <div class="button white-border mx-3">OUR MISSION</div>
      <div class="button yellow-border mx-3">DONATE NOW</div>
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
  margin-top: 35px;
}
.white-border{
  border: 1px solid white;
  color: white;
}
.yellow-border{
  border: 1px solid  #fec96b;
  color: #fec96b;
}

h1{
  color: white;
  font-size: 5rem;
  margin-top: 150px;

}
p{
  color: white;
  font-size: 1.5rem;
}

.button{
padding: 10px 30px;
}
</style>