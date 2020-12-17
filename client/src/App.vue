<template>
  <div id="app">
    <Navbar/>
    <img src="./assets/log.png" style="width: 140px;margin-top: 45px;">
    <router-view/>
  </div>
</template>

<script>

import Navbar from './components/Navbar'

export default {
  name: 'App',
  components:{
    Navbar
  } 
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body{
	background-color:white;
	background: url(./assets/bod.jpg) no-repeat;
	width:100%;
	height:100%;
	background-size: cover;
	background-attachment: fixed;
	color:white;
}
</style>
