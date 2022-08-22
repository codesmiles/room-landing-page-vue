<template>
  <div class="container">
    <Nav />
    <Hero />
    <ShopNow />
    <div class="img1-sec">
      <img src="./assets/images/image-about-dark.jpg" />
    </div>

    <About />
    <div class="img2-sec">
      <img src="./assets/images/image-about-light.jpg" alt="" />
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from "./components/Footer";
import Nav from "./components/Nav";
import About from "./components/About.vue";
import Hero from "./components/Hero.vue";
import ShopNow from "./components/ShopNow.vue";

export default {
  name: "App",
  components: { Footer, Nav, Hero, ShopNow, About },
  data() {
    return {};
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=League+Spartan:wght@300;400;600;700&display=swap");
body {
  margin: 0;
  padding: 0;
  font-size: 12px;
  font-family: "League Spartan", sans-serif;
}
.img2-sec img,
.img1-sec img {
  width: 100%;
}
.attribution {
  font-size: 11px;
  text-align: center;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}
</style>
