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
      <div class="button white-border mx-3 text-center">OUR MISSION</div>
      <div class="button yellow-border mx-3 text-center">DONATE NOW</div>
    </div>


    <!-- qui ci sono i due box bianchi a destra nell'header -->
    <div class="box1">
      <span><i class="fa-brands fa-vuejs fa-2xl dark-text"></i></span>
      <h6 class="dark-text text-center">Prebuilts</h6>
    </div>
    <div class="box2">
    <p class="green-text text-center">$ <span class="green-text num">45</span></p>
    <h6 class="dark-text text-center">On Sale</h6>
    </div>

  </header>
</template>



<style lang="scss" scoped>
header{
  height: 900px;
  background-image: url(../assets/img/jumbotron.jpeg);
  background-size: cover;
  background-position: center;
  position: relative;
}

img{
  margin-top: 35px;
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

.box1{
  position: absolute;
  background-color: white;
  height: 70px;
  width: 70px;
  border-radius: 10px;
  top: 150px;
  right: 30px;
}
.box2{
  position: absolute;
  background-color: white;
  height: 70px;
  width: 70px;
  border-radius: 10px;
  top: 230px;
  right: 30px;
}
.fa-vuejs{
  margin-top: 30px;
  margin-left: 22px;
}
.green-text{
  color: rgb(22, 144, 4);
  margin: 0;
}

.num{
  font-size: 2rem;
  
}

// effetti hover
.box1:hover{
  cursor: pointer;
  background-color:  #e0d5d5;
}
.box2:hover{
  cursor: pointer;
  background-color:   #e0d5d5;
}
</style>