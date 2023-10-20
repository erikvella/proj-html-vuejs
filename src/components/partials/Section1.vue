<script>
export default {
name:'Section1'
}
</script>


<template>
  <section>
    <div class="container-fluid">
      <div class="row">
        <!-- colonna di sx -->
        <div class="col-8">
          <h1 class="title-col-sx">EVERY MOMENT COUNTS</h1>

          <div class="yellow-line"></div>

          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, temporibus delectus exercitationem sunt, quas dicta illo maiores excepturi odio mollitia aliquam illum.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat laborum, quo soluta autem provident architecto, temporibus esse, distinctio officia ea modi numquam reprehenderit? Sed autem suscipit tempora, accusantium cumque fugit odit dolore dicta iusto nobis fuga expedita sapiente fugiat aperiam?
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero a saepe ipsam aut eius accusantium. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam.
          </p>

          <div class="button bg-yellow text-center">OUR MISSION</div>
        </div>


        <!-- colonna di dx -->
        <div class="col-4 bg-pink justify-content-center">
          
          <div class="stat">
            <h1 class=" white-text text-center "><i class="fa-regular fa-heart fa-lg"></i> 2032</h1>
            <h4 class="white-text text-center">Volunteers wordlwide</h4>
          </div>

          <div class="my-5">
            <h1 class=" white-text text-center "><i class="fa-solid fa-earth-americas fa-lg"></i> 132</h1>
            <h4 class="white-text text-center">Active projects</h4>
          </div>

          <div class="my-5">
            <h1 class=" white-text text-center "><i class="fa-solid fa-dollar-sign fa-lg"></i> 3.8M</h1>
            <h4 class="white-text text-center">Donated</h4>
          </div>
          
          


        </div>

      </div>

    </div>
  </section>
</template>


<style lang="scss" scoped>
section{
  height: 700px;
  width: 100%;
}
.container-fluid{
  height: 100%;
  .title-col-sx{
    margin-top: 100px;
    margin-left: 100px;
  }
}
.yellow-line{
  margin: 20px 100px;
}
p{
  margin: 40px 100px;
  color:  #5c6668;
}
.button{
  margin: 10px 100px;
  width: 180px;
}

// stili per la colonna di dx
.col-4{
  height: 700px;
}
.stat{
  margin-top: 160px;
}
</style>