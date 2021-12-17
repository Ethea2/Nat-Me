<template>
<section class="main-page">
  <section class="title">
    <h1 class="section-title">Coding Projects!</h1>
  </section>
  <section class="project-section">
    <div class="container-1">
      <div class="box-1">
        <div class="title-container" data-aos="fade-right">
          <h1>Aryan Bot</h1>
        </div>
        <p class="project-description">Lore ipsum dolor sit amet, consectetur adipisicing elit. Ea corrupti dolores porro corporis laboriosam, rerum amet ratione, quod dolorum officiis doloribus, eius cupiditate modi repellat? Maxime officiis provident minima quis!</p>
      </div>
      <div class="box-2">
        <h1 data-aos="fade-up-left">GIF</h1>
      </div>
    </div>
  </section>
  <section class="project-section">
    <div class="container-2">
      <div class="box-1">
        <div class="title-container" data-aos="fade-right">
          <h1>Shape Shifter</h1>
        </div>
        <p class="project-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea corrupti dolores porro corporis laboriosam, rerum amet ratione, quod dolorum officiis doloribus, eius cupiditate modi repellat? Maxime officiis provident minima quis!</p>
      </div>
      <div class="box-2">
        <h1 data-aos="fade-up-left">GIF</h1>
      </div>
    </div>
  </section>
  <section class="project-section">
    <div class="container-3">
      <div class="box-1">
        <div class="title-container" data-aos="fade-right">
          <h1>Lola Helper</h1>
        </div>
        <p class="project-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea corrupti dolores porro corporis laboriosam, rerum amet ratione, quod dolorum officiis doloribus, eius cupiditate modi repellat? Maxime officiis provident minima quis!</p>
      </div>
      <div class="box-2">
        <h1 data-aos="fade-up-left">GIF</h1>
      </div>
    </div>
  </section>
</section>
</template>

<script>
export default {
  mounted(){
    AOS.init({
      duration: 1000,
      offset: 300
    });
  }

}
</script>

<style scoped>
.main-page {
  background: no-repeat;
  background-position: center;
  background-size: cover;
  background-image: url("../assets/circle-bg.svg");
  color:white;
}
.title{
  padding:50px 0px 0px 0px;
}
.section-title{
  font-size: 60px;
  font-weight: bold;
}
.project-section{
  padding:200px 0 200px 0;
}
.project-section div{
  border: 1px solid black;
}
.container-1, .container-2, .container-3{
  display: flex;
  border: 1px solid rgb(255, 0, 0);
  flex:wrap;
}
.box-1{
  flex: 1.5;
}
.box-2{
  flex: 1;
}
.project-description{
  font-size: 25px;
}
.title-container h1{
  font-size: 40px;
  font-weight: bold;
}


</style>