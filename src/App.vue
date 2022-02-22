<template>
  <v-app>
    <Header />
    <v-main>
      <!-- hero section -->
      <HeroComponent />
      <!-- Aboutus -->
      <Aboutus />
      <!-- Portofolio -->
      <Portofolio />
      <!-- Project -->
      <Project />
      <!-- Gallery -->
      <Gallery />
      <!-- Contact -->
      <Contactus />
      <!-- Footer -->
      <Footer />
    </v-main>
  </v-app>
</template>

<script>
import Header from "./components/Header.vue"
import HeroComponent from "./components/HeroComponent.vue"
import Aboutus from "./components/Aboutus.vue"
import Portofolio from "./components/Portofolio.vue"
import Project from "./components/Project.vue"
import Gallery from "./components/Gallery.vue"
import Contactus from "./components/Contactus.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',
  components: {Footer, Contactus, Gallery, Project,Portofolio, Aboutus, HeroComponent, Header},
  data(){
    return{
      menus:[
        {title:'Home',        route:'home'},
        {title:'About Us',    route:'about-us'},
        {title:'Portofolio',  route:'portofolio'},
        {title:'Project',     route:'project'},
        {title:'Gallery',     route:'gallery'},
        {title:'Contact',     route:'contact'},
      ]
    }
  }
};
</script>
