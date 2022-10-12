<template>
  <div class="">
    <Navbar/>
    <div class='d-flex'>
        <div class='bg-primar' style="width:20%; height:100vh"> 
          
        </div>
        <div class='' style="width:80%; height:100vh"><router-view/></div>
    </div>
    
    
    
  </div>
</template>
<script>
import Navbar from './component/nav-foot/nav_bar.vue'
export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>
<style>

</style>
