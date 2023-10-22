<script>
import { top_menu } from '../../data/store';
export default {
name:'Navbar',
data(){
  return{
    top_menu
  }
}
}
</script>


<template>
  <div class="d-flex">
    <nav class="my-4">
    <ul>
      
      <li
      v-for="(item , index) in top_menu"
      :key="index"
      >
        <a href="#" class="menu-item" :class="item.class">{{ item.text }}</a>
      </li>
      
      
    
    </ul>
  </nav>

  

  </div>


</template>


<style lang="scss" scoped>
.menu-item{
  
  padding: 10px 25px;
}

ul{
  list-style: none;
  display: flex;
  li{
    margin: 25px;
    color: white;
    a{
      text-decoration: none;
      color: white;
    }
  }
}



.yellow-text{
  color: #fec96b;
}
</style>