<script>
import { section2_cards } from '../../data/store';
export default {
name:'Section2',
data(){
  return{
    section2_cards
  }
}
}
</script>

<template>
  <section>
    <div class="container">
      
        <h1 class=" white-text text-center">OUR VALUES</h1>
        <div class="yellow-line mt-3 mx-auto"></div>
        <h4 class=" grey-text text-center mt-5">Think big. Act bigger</h4>
    </div>   
     
    <div class="container">

      <div class="row">
        <div 
        v-for="(item , index) in section2_cards"
        :key="index"
        class="col-3">
          <p class="text-center"><i :class="item.icon"></i></p>
          <h2 class="text-center white-text">{{ item.title }}</h2>
          <p class="text-center grey-text my-5">{{ item.text }}</p>
          <div class="button bg-yellow text-center mx-auto">{{ item.btn_text }}</div>
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