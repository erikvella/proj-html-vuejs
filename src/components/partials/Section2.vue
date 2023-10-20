<script>
export default {
name:'Section2'
}
</script>

<template>
  <section>
    <div class="container">
      
        <h1 class=" white-text text-center">OUR VALUES</h1>
        <div class="yellow-line my-5 mx-auto"></div>
        <h4 class=" grey-text text-center">Think big. Act bigger</h4>
    </div>   
     
    <div class="container">

      <div class="row">
        <div class="col-3">
          <p class="text-center"><i class="fa-solid fa-droplet fa-2xl"></i></p>
          <h2 class="text-center white-text">Clean water</h2>
          <p class="text-center grey-text my-5">Nullam convallis, orci in congue aliquet, diam mauris cursus urna. Id maximus lectus magna maximus.</p>
          <div class="button bg-yellow text-center mx-auto">LEARN MORE</div>
        </div>
        <div class="col-3">
          <p class="text-center"><i class="fa-solid fa-stethoscope fa-2xl"></i></p>
          <h2 class="text-center white-text">Vaccinations</h2>
          <p class="text-center grey-text my-5">Nullam convallis, orci in congue aliquet, diam mauris cursus urna. Id maximus lectus magna maximus.</p>
          <div class="button bg-yellow text-center mx-auto">LEARN MORE</div>
        </div>
        <div class="col-3">
          <p class="text-center"><i class="fa-solid fa-graduation-cap fa-2xl"></i></p>
          <h2 class="text-center white-text">Education</h2>
          <p class="text-center grey-text my-5">Nullam convallis, orci in congue aliquet, diam mauris cursus urna. Id maximus lectus magna maximus.</p>
          <div class="button bg-yellow text-center mx-auto">LEARN MORE</div>
        </div>
        <div class="col-3">
          <p class="text-center"><i class="fa-brands fa-pagelines fa-2xl"></i></p>
          <h2 class="text-center white-text">Farming</h2>
          <p class="text-center grey-text my-5">Nullam convallis, orci in congue aliquet, diam mauris cursus urna. Id maximus lectus magna maximus.</p>
          <div class="button bg-yellow text-center mx-auto">LEARN MORE</div>
        </div>
      </div>

    </div>

  </section>
</template>



<style lang="scss" scoped>
section{
  height: 950px;
  width: 100%;
  background-image: url(../../assets/img/jumbotron.jpeg);
  background-size: cover;
  background-position: center;
}
h1{
  padding-top: 150px;
}
h2{
  margin-top: 40px;
}
.row{
  margin-top: 200px;
}
.fa-solid , .fa-brands{
  color:  #fec96b;
  font-size: 4rem;
}


</style>