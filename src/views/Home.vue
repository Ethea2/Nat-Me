<template>
  <section id="sect1">
      <div class="div1">
        <h1 class="head1" data-aos="fade-right">Nathan Andres</h1>
        <p data-aos="fade-right" data-aos-delay="500">
          An aspiring web developer ☁️ who is eager to learn best practices and interesting technologies.
          He is also interested in learning how to contribute to open source projects and would like
          to start some of his own in the future 🗞️.
        </p>
        <p data-aos="fade-right" data-aos-delay="800">
          He has a multitude of interests, varying from gaming all the way to music. He has been playing
          in a band as a guitar player for years now 🎸. He is also an avid competitive gamer 🎮, who is a 
          strong advocate about E-sports 🖥️.
        </p>
      </div>
      <img src="https://scontent.fmct5-1.fna.fbcdn.net/v/t1.6435-9/141425065_10157395168806503_8495656523964962047_n.jpg?_nc_cat=106&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=AIbiuzodO00AX-La6-U&tn=f9d_IIJwo19Wy6SA&_nc_ht=scontent.fmct5-1.fna&oh=23a97593fae1a6992631b0c47ffc5b00&oe=61C2FBE0" 
      width="400" data-aos="fade-left">
  </section>
  <section id="sect2">
    <div class="div2">
      <h1 class="head2" data-aos="fade-left">Hobbies ⌨️</h1>
      <p data-aos="fade-left" data-aos-delay="500">
        I am in love with programming 💻. I enjoy doing random stuffs with it; increasing my productivity through it; 
        making a website with it; watching fun videos about it; making apps with it. To me it just feels like the possibilities
        are endless.
      </p>
      <p data-aos="fade-left" data-aos-delay="800">
        I love gaming 🎲! I am a very competitive person in everything, I try to learn things fast like lightning 🌩️.
        For me competition is important, it pushes people to be better. Everytime I find peers with similar passion,
        I suddenly get the urge to learn more and do better than when I did before!  
      </p>
    </div>
      <img id="img2" src="https://scontent.fmct5-1.fna.fbcdn.net/v/t1.6435-9/67401749_10156483165733549_7207754489116229632_n.jpg?_nc_cat=107&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=jlHW7VX9IcEAX_IOggE&_nc_ht=scontent.fmct5-1.fna&oh=78712cc0125657447c176a54514d639c&oe=61C48D60"
      width="500" data-aos="fade-right">
  </section>
  <section id="sect3">
    <div class="div3">
      <h1 data-aos="fade-right">Real Life 🧐</h1>
      <p data-aos="fade-right" data-aos-delay="500">
        Outside the computer I am an active band member 🥁. I commit my free time to learning songs
        that we play in gigs when we're invited 🎶. I also jog from time to time to stay fit and motivated 🎽.
      </p>
      <p data-aos="fade-right" data-aos-delay="800">
        I also spend a lot of time with my family 👪. Being a single child I'm really close to my parents.
        I also go out with my friends a lot 🧑‍🤝‍🧑. I am an extrovert who likes to have people around me time to time.
        I like drinking in coffee shops and going out window shopping techy products.
      </p>
    </div>
    <img id="img3" src="https://scontent.fmct5-1.fna.fbcdn.net/v/t1.6435-9/133579257_10157813601493549_6783098443652416118_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=Zd1jMBB3HFAAX_OKPXE&_nc_ht=scontent.fmct5-1.fna&oh=7be80bbb8b2ba4cdbd0da5ed5f6085e1&oe=61C1F319"
    width="550" data-aos="fade-left">

  </section>
</template>

<script>

export default {
  name: "Home", 
  components: {},
  data(){
    return{
      showDiv1:false,
    }
  },
  methods:{

  },
  mounted(){
    AOS.init({
      duration: 1000,
      offset: 300
    });
    this.showDiv1 = true;
  }
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
  border-radius: 10px;
}

h1{
  float:left;
  font-weight: bold;
  position:relative;
  font-size: 55px;
}

div{
  display:inline-block;
  position: relative;
  margin: 0 auto;
}

#img2{
  float:left;
  left: -300px;
  bottom: 450px;
}

#img3{
  left: 300px;
  bottom: 250px;
}

.div1{
  right: 300px;
}

 .div2{
  right: -300px;
  bottom: 150px;
 }

 .div3{
   right: 300px;
   top: 60px;
 }

.head1{
  float:left;
  right: 10px;
  font-size: 60px;
}

.head2{
  float:right;
  left: 10px;
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