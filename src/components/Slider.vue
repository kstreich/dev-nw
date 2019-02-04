<template>


  <div id="slider" class="carousel slide" data-ride="carousel">
    <!-- dot navigation -->
    <ol class="carousel-indicators">
      <li data-target="#slider" data-slide-to="0" class="active"></li>
      <li data-target="#slider" data-slide-to="1"></li>
      <li data-target="#slider" data-slide-to="2"></li>
    </ol>
    <!-- wrapper for slides -->
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="../assets/marquee/marquee-1.jpg" alt="sun set">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="../assets/marquee/marquee-2.jpg" alt="beach">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="../assets/marquee/marquee-3.jpg" alt="bridge">
      </div>
    </div>
    <!-- prev and next buttons -->
    <a class="carousel-control-prev" href="#slider" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#slider" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>



</template>

<script>
  export default {
    name: 'Slider',
    data() {
      return {

      }
    },
    computed: {},
    methods: {}
  }

</script>

<style>


</style>