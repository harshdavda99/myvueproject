<template>
  <div class="">
    <Navbar/>
    <Footer/>
    <!-- <div class='d-flex'> -->
        <!-- <div class='bg-primary' style="width:20%; height:100vh"> <SideNavbar/></div> -->
        <!-- <div class='' style="width:80%; height:100vh"><router-view/></div> -->
    <!-- </div> -->
    
    
    
  </div>
</template>
<script>
import Navbar from './component/nav-foot/nav_bar.vue'
// import SideNavbar from './component/nav-foot/side-nav.vue'
// import Footer from './component/nav-foot/foot-bar.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    // Footer,
    // SideNavbar
  }
}
</script>
<style>

</style>
