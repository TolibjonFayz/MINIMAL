<template>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Oswald:wght@200;300;400;500;600;700&family=Source+Serif+4:ital,opsz,wght@0,8..60,200;0,8..60,300;0,8..60,400;0,8..60,500;1,8..60,200;1,8..60,300;1,8..60,400;1,8..60,500&display=swap"
    rel="stylesheet"
  />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;1,100;1,200;1,300;1,400;1,500&display=swap"
    rel="stylesheet"
  />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Vollkorn:ital,wght@0,400;0,500;0,600;1,400;1,500;1,600&display=swap"
    rel="stylesheet"
  />
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
    integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />
  <Navbar />
  <Makingbsoioo />
  <Getintouch />
  <Howwmbt />
  <RecentProjects />
  <Ourteam />
  <Comments />
  <Lestgetintouch />
  <Footer />
</template>

<script setup>
import Navbar from "./components/NavbarComponent.vue";
import Makingbsoioo from "./components/Makingbsoioo.vue";
import Getintouch from "./components/Getintouch.vue";
import Howwmbt from "./components/Howwmbt.vue";
import RecentProjects from "./components/RecentProjects.vue";
import Ourteam from "./components/Ourteam.vue";
import Comments from "./components/Comments.vue";
import Lestgetintouch from "./components/Lestgetintouch.vue";
import Footer from "./components/Footer.vue";
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
