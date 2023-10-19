<script>
import Navbar from './partials/Navbar.vue';

export default {
    name: 'Header',
    components: {
       Navbar 
      }
}
</script>

<template>
  <header>
    <div class="top-bar">
      <Navbar />
    </div>
  </header>
</template>



<style lang="scss" scoped>
header{
  height: 800px;

}
</style>