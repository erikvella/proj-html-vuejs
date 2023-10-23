<script>
export default {
name:'Section3'
}
</script>

<template>
  <section>
    <div class="container">
      
      <h1 class="mt-5 text-center">RECENT CAUSES</h1>
      <div class="yellow-line mt-3 mx-auto"></div>
      <h4 class=" dark-grey-text text-center mt-5">We run projects in over 30 countries in 5 continents</h4>

    </div>  


    <div class="container-fluid my-5">

      <div class="row justify-content-between">

        <div class="col-3">
          <img class="m-5" src="../../assets/img/HelloIMG1669149317319.jpeg" alt="">
        </div>
        <div class="col-3">
          <img class="m-5" src="../../assets/img/HelloIMG1669149318263.jpeg" alt="">
        </div>
        <div class="col-3">
          <img class="m-5" src="../../assets/img/HelloIMG1669149319450.jpeg" alt="">
        </div>
        <div class="col-3">
          <img class="m-5" src="../../assets/img/HelloIMG1669149321401.jpeg" alt="">
        </div>

      </div>

    </div>
  </section>
<!-- piccola sezione in rosa -->
  <section class="bg-pink">
    <h3 class="white-text text-center">VIEW ALL OUR CAUSES</h3>
  </section>
</template>



<style lang="scss" scoped>
section{
  height: 740px;
  width: 100%;
}

img{
  height: 270px;
}

.bg-pink{
  height: 150px;
}
.bg-pink:hover{
  cursor: pointer;
  background-color: #ab3230;
}
h3{
  padding-top: 60px;
}
</style>