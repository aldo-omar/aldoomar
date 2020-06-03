<template>
  <div id="app">
  <!-- <div id="app"  :style="{'background-image':'url(https://aldoomar.com/images/dirt-bg.jpg)'}"> -->
  
  <div class="bg-cover bg-center h-screen" style="background-image: url(https://aldoomar.com/images/space.jpg)">
  <nav class="flex items-center justify-between flex-wrap bg-purple-600 bg-opacity-25 p-6">
  <div class="flex items-center flex-shrink-0 text-white">
    <svg xmlns="http://www.w3.org/2000/svg" id="Capa_1" enable-background="new 0 0 511.995 511.995" height="54px" viewBox="0 0 511.995 511.995" width="54px" class=""><g><g><path d="m308.167 241.52c0-28.766-23.403-52.169-52.17-52.169s-52.17 23.403-52.17 52.169c0 28.767 23.403 52.17 52.17 52.17s52.17-23.404 52.17-52.17zm-52.169 22.169c-12.225 0-22.17-9.945-22.17-22.17 0-12.224 9.945-22.169 22.17-22.169s22.17 9.945 22.17 22.169c-.001 12.225-9.946 22.17-22.17 22.17z" data-original="#000000" class="active-path" data-old_color="#000000" fill="#FFFFFF"/><path d="m425.684 424.352v-132.322l-51.65-32.948c.615-14.332.261-28.762-1.117-43.191-7.162-74.973-41.384-144.771-96.362-196.535l-20.557-19.356-20.558 19.356c-54.978 51.765-89.2 121.563-96.362 196.535-1.378 14.429-1.732 28.859-1.117 43.191l-51.65 32.948v132.321l90.003-28.282c3.744 6.784 7.752 13.436 12.017 19.945v62.315h30v-48.333h22.667v23.252h30v-23.252h22.667v48.333h30v-62.315c4.265-6.508 8.273-13.161 12.017-19.945zm-30-115.874v75.001l-46.66-14.662c10.468-24.35 17.778-49.975 21.762-76.222zm-139.694-267.28c27.301 25.706 48.392 55.971 63.081 88.684h-126.153c14.687-32.713 35.775-62.979 63.072-88.684zm-139.679 342.281v-75.001l24.898-15.883c3.983 26.247 11.293 51.872 21.762 76.222zm124.687-10.983v27.499h-27.316c-47.563-72.299-57.394-161.126-32.242-240.114h149.112c25.156 78.987 15.325 167.815-32.238 240.114h-27.316v-27.499z" data-original="#000000" class="active-path" data-old_color="#000000" fill="#FFFFFF"/><path d="m240.998 483.495h30v28.5h-30z" data-original="#000000" class="active-path" data-old_color="#000000" fill="#FFFFFF"/></g></g> </svg>
    <span class="font-semibold text-xl tracking-tight"></span>
  </div>
  <!-- <div class="block lg:hidden">
    <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
      <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title>
      <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
    </button>
  </div> -->
  <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
    <div class="text-sm lg:flex-grow">
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 font-semibold text-xl text-white hover:text-purple-100  mr-40">
        ABOUT
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 font-semibold text-xl text-white hover:text-purple-100 mr-40">
        PORFOLIO
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 font-semibold text-xl text-white hover:text-purple-100 ">
        CONTACT
      </a>
    </div>
    <!-- <div>
      <a href="#" class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0">Download</a>
    </div> -->
  </div>
</nav>
  <!-- <div id="app" class=" bg-fixed sm:bg-local md:bg-scroll lg:bg-local xl:bg-fixed" style="background-image: url(./assets/logo.png)"> -->
  <!-- <div id="app" class="h-65 bg-fixed sm:bg-local md:bg-scroll lg:bg-local xl:bg-fixed" style="background-image: url('./assets/space.png')"> -->
  <!-- <div id="app" class="h-65 bg-fixed sm:bg-local md:bg-scroll lg:bg-local xl:bg-fixed" :style="{'background-image':'url(https://example.com/bg.png)'}"> -->
    <!-- <div class="h-full" style="background-image: url('./assets/space.png');">fffff</div> -->

    
    <!-- <div class="bg-auto h-auto" style="background-image: url(img/space.png)">fff
    </div> -->
    <!-- <div class="bg-local h-a4" style="background-image: url(images/space.png)">
    </div> -->
    <!-- <div class="bg-local h-4" style='background-image: url("images/space.png");'>
    </div> -->
    <!--<div class="bg-fixed " style="background-image: url(background-image: url(img/space.png))">fff</div>-->
    <!--<div class="bg-fixed " style="background-image: url(background-image: url(images/space.png))">fff<div>-->    <!-- <div class="bg-fixed " style="background-image: url(background-image: url(./assets/logo.png)">fff</div> -->
    <!--<div class="bg-local" style="background-image: url(background-image: url(./assets/logo.png)">fff</div>-->
    <!-- <div class="bg-scroll" style="background-image: url(./assets/logo.png)">sdsddd</div> -->

    <!-- <div class="bg-scroll h-4 bg-space"> -->
    <!-- <img  alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="Welcome to my first app with Vue.js and TailwindCSS."/>
    <Header msg="Header"/>
    
    </div>
    </div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  /* margin-top: 60px;
  background-color: #00092b;
/* background-color:bisque;*/
/* background-image: url(./assets/space.png); */
}
/* .bg-space{
    background-image: url(./assets/space.png);
} */
</style>
