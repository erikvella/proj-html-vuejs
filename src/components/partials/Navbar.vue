<script>
export default {
name:'Navbar'
}
</script>


<template>
  <div class="d-flex">
    <nav class="my-4">
    <ul>
      <li class="yellow-text">
        HOME
      </li>
      <li>
        MISSION
      </li>
      <li>
        CAUSES <i class="fa-solid fa-chevron-down"></i>
      </li>
      <li>
        JOURNAL
      </li>
    
    </ul>
  </nav>

  <div class="yellow-badge my-5 donate">
    <span>DONATE</span>
  </div>

  </div>


</template>


<style lang="scss" scoped>
.yellow-badge{
  background-color: #fec96b;
}

ul{
  list-style: none;
  display: flex;
  li{
    margin: 25px;
    color: white;
  }
}

.donate{
  height: 25px;
  color: white;
}

.yellow-text{
  color: #fec96b;
}
</style>