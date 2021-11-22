<template>
 <div class="topnav">
    <h1>Nat Me!</h1>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About Me</router-link>
</div> 
<!--<div class="container">
    <div id="nav">

    </div>
</div> -->

<router-view/>
</template>

<script>
export default {

}
</script>

<style scoped>
h1{
    position:relative;
    left: 20px;
    float: left;
    font-family: 'Open Sans Condensed', sans-serif;
    color: rgb(0, 0, 0);
}

.topnav {
  background-color: #D1D3D4;
  overflow: hidden;
}

.topnav a{
  float: right;
  color: #696969;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  margin: 0px 2px auto;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
  border-radius: 10px;
}

.topnav a.router-link-exact-active {
  background-color: #A5E5D9;
  color: black;
  border-radius: 10px;
}


</style>
<!-- 
    Color Palettes:
        #000000 - super black
        #6D6E71 - super gray
        #D1D3D4 - super light gray
        #FFFFFF - super white
        #A5E5D9 - super light cyan -->