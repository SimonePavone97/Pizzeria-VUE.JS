<template>
  <div id="app" class="text-center">
    <header>

      <LogoComp />
      <NavComp />
      <JumboComp />

    </header>

    <main class="container">

      <PdfComp />
      <ImgComp />
      <MapComp />

    </main>

    <footer class="footr d-flex justify-content-around align-items-center">

      
      <div>
        <LogoComp />
      </div>

      <div>
        <FootComp/>
      </div>



    </footer>

  </div>
</template>

<script>
  import 'bootstrap'
  import LogoComp from './components/LogoComp.vue'
  import NavComp from './components/NavComp.vue'
  import JumboComp from './components/JumboComp.vue'
  import PdfComp from './components/PdfComp.vue'
  import ImgComp from './components/ImgComp.vue'
  import MapComp from './components/MapComp.vue'
  import FootComp from './components/FootComp.vue'

  export default {
    name: 'App',
    components: {
      LogoComp,
      NavComp,
      JumboComp,
      PdfComp,
      ImgComp,
      MapComp,
      FootComp
    }
  }
</script>

<style lang="scss">
  @import "bootstrap/dist/css/bootstrap.min.css";

  .footr {
    background-color: black;
    height: auto;

    a {
      color: white;
    }
  }
</style>