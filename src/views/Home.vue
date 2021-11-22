<template>
  <section id="sect1">
    <div class="div1">
      <h1 class="head1">Nathan Andres</h1>
      <p class="p1">
        An aspiring web developer who is eager to learn best practices and interesting technologies.
        He is also interested in learning how to contribute to open source projects and would like
        to start some of his own in the future.
      </p>
      <p>
        He has a multitude of interests, varying from gaming all the way to music. He has been playing
        in a band as a guitar player for years now. He is also an avid competitive gamer, who is a 
        strong advocate about E-sports.
      </p>
    </div>
    <img src="https://scontent.fmct5-1.fna.fbcdn.net/v/t1.6435-9/141425065_10157395168806503_8495656523964962047_n.jpg?_nc_cat=106&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=AIbiuzodO00AX-La6-U&tn=f9d_IIJwo19Wy6SA&_nc_ht=scontent.fmct5-1.fna&oh=23a97593fae1a6992631b0c47ffc5b00&oe=61C2FBE0" 
    width="400">
  </section>
  <section id="sect2">
    <h1>Lorem Ipsum</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum rem vitae
      nostrum quis aperiam aut porro, asperiores similique tempore sit et beatae
      distinctio quae impedit facere corporis sequi facilis dolor!
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum rem vitae
      nostrum quis aperiam aut porro, asperiores similique tempore sit et beatae
      distinctio quae impedit facere corporis sequi facilis dolor!
    </p>
  </section>
  <section id="sect3">
    <h1>Lorem Ipsum</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum rem vitae
      nostrum quis aperiam aut porro, asperiores similique tempore sit et beatae
      distinctio quae impedit facere corporis sequi facilis dolor!
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum rem vitae
      nostrum quis aperiam aut porro, asperiores similique tempore sit et beatae
      distinctio quae impedit facere corporis sequi facilis dolor!
    </p>
  </section>
</template>

<script>

export default {
  name: "Home",
  components: {},
};

</script>

<style scoped>
section {
  padding: 400px;
}

p {
  font-size: 20px;
}

img{
  float: right;
  position: relative;
  left: 200px;
  bottom:400px;
}

.div1{
  display:inline-block;
  position: relative;
  right: 300px;
  margin: 0 auto;
}

.head1{
  float:left;
  font-weight: bold;
  position:relative;
  right: 10px;
  font-size: 60px;
}

#sect1 {
  background: no-repeat;
  background-position: center;
  background-size: cover;
  width: 100%;
  color: rgb(0, 0, 0);
  background-image: url("../assets/circles.svg");
}

#sect2 {
  background: no-repeat;
  background-position: center;
  background-size: cover;
  width: 100%;
  color: white;
  background-image: url("../assets/wave.svg");
}

#sect3 {
  background: no-repeat;
  background-size: cover;
  width: 100%;
  color: black;
  background-image: url("../assets/peaks.svg");
}
</style>