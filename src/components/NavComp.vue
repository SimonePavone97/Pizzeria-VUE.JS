<template>
  <div class="container d-flex justify-content-center text-uppercase fw-bold">

    <a href="#"><i class="fa-solid fa-house"></i>Home</a>
    <a href="#C4"><i class="fa-solid fa-pizza-slice"></i>le nostre pizze</a>
    <a href="#C5"><i class="fa-solid fa-location-dot"></i>dove siamo</a>
    <a href="#C6"><i class="fa-solid fa-location-dot"></i>orari</a>


  </div>
</template>

<script>
  export default {
    name: 'NavComp',

  }
</script>


<style scoped lang="scss">
  a {
    text-decoration: none;
    color: black;
  }

  i {
    padding-right: 10px;
    padding-left: 10px;
    color: red;
  }

</style>