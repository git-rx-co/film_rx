

<script>

import NavBar from './components/Global/NabBar.vue' 
import BannerMain from './components/Global/Banner.vue' 


export default {
  name: 'App',
  components: {
    NavBar,BannerMain
  }
}
</script>

<style>
 *{
  font-family: 'Poppins', sans-serif;
	font-weight: 500;
	font-style: normal;
	font-size: 14px;
  color: #ffffff;
  background: #1B252E;
 }
#app {
 
}
</style>

<template>
  <NavBar />
  <BannerMain />
  <h1>Example heading <span class="badge bg-secondary">New</span></h1>
  

</template>
