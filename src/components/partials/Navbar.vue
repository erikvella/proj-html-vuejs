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
      
      <li class="menu-item">
        <a href="#" class="yellow-text">HOME</a>
      </li>
      <li class="menu-item">
        <a href="#">MISSION</a>
      </li>
      <li class="menu-item">
        <a href="#">CAUSES <i class="fa-solid fa-chevron-down"></i></a>
      </li>
      <li class="menu-item">
        <a href="#">JOURNAL</a>
      </li>
      <li class="menu-item bg-yellow">
        <a href="#">DONATE</a>
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