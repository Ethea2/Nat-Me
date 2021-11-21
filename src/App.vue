<template>
  <NavBar />
</template>


<script>
import NavBar from './components/NavBar.vue'

export default {
  components:{ NavBar }  
}
</script>

<style>
body{
   background: rgb(243, 243, 243);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

<!-- 
    Color Palettes:
        #000000 - super black
        #6D6E71 - super gray
        #D1D3D4 - super light gray
        #FFFFFF - super white
        #A5E5D9 - super light cyan -->