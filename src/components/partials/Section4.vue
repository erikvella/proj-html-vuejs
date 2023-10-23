<script>
import { section4_cards } from '../../data/store';
export default {
name:'Section4',
data(){
  return{
    section4_cards
  }
}
}
</script>

<template>
  <section>
    <div class="container">
      
      <h1 class="text-center">LATEST ARTICLES</h1>
      <div class="yellow-line mt-3 mx-auto"></div>
      <h4 class="dark-grey-text text-center mt-5">Together we make all the differences</h4>
    </div>  
  
  <div class="container">
    <div class="row">
      <!-- qui abbiamo la colonna di sx -->
      <div class="col-6">
        <div class="big-img-card my-5 ">
          <img class="big-img" src="../../assets/img/HelloIMG1669149322752.jpeg" alt="">
          <h4 class="yellow-text p-4">Understanding community complexities</h4>
          <p class="dark-grey-text px-4">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Earum hic aperiam, odio accusamus asperiores delectus?
          </p>
        </div>
      </div>

      <!-- qui inizia la colonna di dx -->
      <div class="col-6">
        
         <div 
         v-for="(item , index) in section4_cards"
         :key="index"
         class="small-img-card d-flex my-5">
            <div class="box-img">
              <img class="small-img" src="../../assets/img/HelloIMG1669149318263.jpeg" alt="">
            </div>
            <div class="small-img-text">
                    <h4 class="yellow-text mx-4">{{ item.title }}</h4>
                      <p class="dark-grey-text mx-4">
                          {{ item.text }}
                      </p>
            </div>
         </div>
         
       
      </div>
    </div>
  </div>


  <!-- piccolo segmento in rosa -->

  <div class="container bg-pink my-5 ">
    <h4 class="white-text text-center py-4">VIEW ALL OUR ARTICLES</h4>
  </div>
  </section>
</template>



<style lang="scss" scoped>
section{
  height: 1200px;
  width: 100%;
}
h1{
  padding-top: 150px;
}
.big-img-card{
  height: 600px;
  width: 560px;
  box-shadow: 1px 5px lightgrey;
}
.big-img{
  width: 560px;
}

.small-img-card{
  height: 115px;
}
.small-img{
  width: 145px;
}
.bg-pink:hover{
  cursor: pointer;
  background-color: #ab3230;
}
</style>