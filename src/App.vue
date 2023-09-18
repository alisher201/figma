<template>
  <div>
    <Navbar/>
    <Main/>
    <Brand/>
    <Project/>
    <Team/>
    <Popular/>
    <Getting/>
    <Footer/>
  </div>
</template>

<script setup>
// import Navbar from './components/Navbar.vue'
import Navbar from './components/Navbar.vue'
import Main from './components/main1.vue'
import Brand from './components/Brands.vue'
import Project from './components/Projects.vue'
import Team from './components/Team.vue'
import Popular from './components/home.vue'
import Getting from './components/let.vue'
import Footer from './components/footer.vue'
</script>

<style lang="scss" scoped>
*{
  margin:0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;

}
</style>