<script>
export default {
name:'Footer'
}
</script>

<template>
  <section>
    <!-- container riservato al logo -->
    <div class="container-logo">
      <img src="../assets/img/logo2colors.png" alt="">
    </div>

         <!-- footer con il relativo menu dei social -->

    <div class="container-footer bg-dark-white">
      <p class="text-center py-4">&copy; Copyright 2012 | Avada theme by <span class="yellow-text">ThemeFusion</span> | All Rights Reserved | Powered by <span class="yellow-text">WordPress</span></p>

      <nav>     
        <ul>
          <li>
            <a class="yellow-text mx-2" href="#"><i class="fa-brands fa-facebook-f fa-lg"></i></a>
          </li>
          <li>
            <a class="yellow-text mx-2" href="#"><i class="fa-brands fa-instagram fa-lg"></i></a>
          </li>
          <li>
            <a class="yellow-text mx-2" href="#"><i class="fa-brands fa-twitter fa-lg"></i></a>
          </li>
          <li>
            <a class="yellow-text mx-2" href="#"><i class="fa-brands fa-youtube fa-lg"></i></a>
          </li>
         
        </ul>
      </nav>
    </div>
  </section>
</template>



<style lang="scss">
section{
  height: 330px;
}

.container-logo{
  height: 180px;
  display: flex;
  justify-content: center;
  align-items: center;
  img{
    height: 60px;
  }
}
.container-footer{
  height: 150px;
  ul{
    list-style: none;
    display: flex;
    justify-content: center;
  }
}
</style>