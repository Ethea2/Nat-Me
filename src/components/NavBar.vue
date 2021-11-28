<template>
 <div class="topnav">
      <h1 class="webTitle animate__animated" @click="redirect" :class="{animate__pulse:hoverOverTitle}"
      @mouseenter="enterTitle" @mouseleave="leaveTitle">Nat Me!</h1>
      <router-link to="/" class="animate__animated" :class="{animate__pulse:hoverOverHome}"
      @mouseenter="enterHome" @mouseleave="leaveHome">Home</router-link>
      <router-link to="/about" class="animate__animated" :class="{animate__pulse:hoverOverAbout}"
      @mouseenter="enterAbout" @mouseleave="leaveAbout">About Me</router-link>
   <!--
   <router-view v-slot="{ Component }">
    <transition name="fade" mode="in-out">
      <component :is="Component"></component>
    </transition>
    </router-view> -->
</div>
   <router-view />
</template>

<script>
export default {
  data(){
    return{
      hoverOverTitle: false,
      hoverOverHome: false,
      hoverOverAbout: false
    }
  },
  methods:{
    redirect(){
      this.$router.push({name: 'Home'})
    },
    enterTitle(){
      this.hoverOverTitle = true;
    },
    leaveTitle(){
      this.hoverOverTitle = false;
    },
    enterHome(){
      this.hoverOverHome = true;
    },
    leaveHome(){
      this.hoverOverHome = false;
    },
    enterAbout(){
      this.hoverOverAbout = true;
    },
    leaveAbout(){
      this.hoverOverAbout = false;
    }
  },
  mounted(){
    AOS.init();
  }
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

.webTitle{
  cursor:pointer;
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s ease;
}


.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}


</style>
<!-- 
    Color Palettes:
        #000000 - super black
        #6D6E71 - super gray
        #D1D3D4 - super light gray
        #FFFFFF - super white
        #A5E5D9 - super light cyan -->