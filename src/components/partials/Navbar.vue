<script>
export default {
name:'Navbar'
}
</script>


<template>
  <div class="d-flex">
    <nav class="my-4">
    <ul>
      
      <li class="menu-item">
        <span class="yellow-text">HOME</span>
      </li>
      <li class="menu-item">
        <span>MISSION</span>
      </li>
      <li class="menu-item">
        <span>CAUSES <i class="fa-solid fa-chevron-down"></i></span>
      </li>
      <li class="menu-item">
        <span>JOURNAL</span>
      </li>
      <li class="menu-item bg-yellow">
        <span>DONATE</span>
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
  }
}



.yellow-text{
  color: #fec96b;
}
</style>