
<template>
<navbar/>
<search-section/>
<Cards/>
</template>

<script >
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup

import Navbar from './components/Navbar.vue'
import SearchSection from './components/SearchSection.vue'
import Cards from './components/Cards.vue'
export default{
  name:'App',
  components:{
    Navbar,
    SearchSection,
    Cards
  }
}
</script>

<style scoped>
#app{
  background:grey;
}
template{
  background-color:#F8FAFC;
}
</style>
