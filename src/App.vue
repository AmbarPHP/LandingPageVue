<template>
  <div id="app">
    <div class="nav-sticky">
      <Nav></Nav>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-lg-12 col-md-12 col-xs-12 text-center my-auto mx-0">
          <Feature3></Feature3>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12col-md-12 col-xs-12 text-center my-auto mx-0">
          <Carrusel></Carrusel>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12col-md-12 col-xs-12 text-center my-auto mx-0">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            At accusantium laborum natus vero distinctio fugit atque velit
            voluptatibus beatae! Aliquam praesentium placeat non maxime ab
            provident officiis veniam tempora necessitatibus.
          </p>
        </div>
      </div>

      <div class="row" id="solutions">
        <div class="col-lg-12 col-md-12 col-xs-12 text-center my-auto mx-0">
          <Embed></Embed>
        </div>
      </div>
      <div class="row" id="gallery">
        <div class="col-lg-12col-md-12 col-xs-12 text-center my-auto mx-0">
          <Gallery></Gallery>
        </div>
      </div>
      <div class="row" id="distribution">
        <div class="col-lg-12 col-md-12 col-xs-12 text-center my-auto mx-0">
          <Distribution></Distribution>
        </div>
      </div>
      <div class="row" id="maps">
        <div class="col-lg-12col-md-12 col-xs-12 text-center my-auto mx-0">
          <Maps></Maps>
        </div>
      </div>
      <div class="row" id="contact">
        <div class="col-lg-12 col-md-12 col-xs-12 text-center my-auto mx-0">
          <Footer2></Footer2>
        </div>
      </div>
      <div class="row" id="footer">
        <div class="col-lg-12col-md-12 col-xs-12 text-center my-auto mx-0">
          <Footer></Footer>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Footer2 from "./components/Footer2.vue";
import Footer from "./components/Footer.vue";
import Nav from "./components/Nav.vue";
import NavScroll from "./components/NavScroll.vue";
import Contact from "./components/Contact.vue";
import Distribution from "./components/Distribution.vue";
import Feature3 from "./components/Feature3.vue";
import Feature4 from "./components/Feature4.vue";
import Embed from "./components/Embed.vue";
import Maps from "./components/Maps.vue";
import Gallery from "./components/Gallery.vue";
import Carrusel from "./components/Carrusel.vue";

export default {
  name: "app",
  components: {
    Footer2,
    Footer,
    Nav,
    NavScroll,
    Contact,
    Distribution,
    Feature3,
    Feature4,
    Gallery,
    Carrusel,
    Embed,
    Maps
  },
  data() {
    return {
      msg: "Welcome to Manglar Fruit"
    };
  }
};
</script>

<style lang="scss">
$color-complementario: #891e67;
$color-resaltado: #00be00;
$background-color: #fff;

html,
body {
  height: 100%;
  margin: 0;
}

#app {
  //background-color: $background-color; //#262e37;
  background: url(https://www.pexels.com/photo/snow-covered-mountain-1755243.jpg)
    no-repeat 50% 50%;
  color: #fff;
  font-family: "Montserrat", sans-serif; //tipo de fuente
  width: 100%; //las unidades del viewport se dividen en 100 partes de vw
  margin-left: 0px;
  height: 900vh; //muy importante multiplicar por el numero de sessiones, porque 100 es el tamaño del viewport
}

h1,
h2 {
  font-weight: normal;
  font-size: 28px;
  font-weight: bold;
  line-height: 1.2307;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

//color del menu

.nav-sticky {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  //background-color: yellow;
  background-color: #891e67;
  padding: 25px;
  font-size: 20px;
  z-index: 11;
  margin-bottom: 20px;
}
</style>
