<template>
  <div class="home">
    <Slider></Slider>
    <PicGrid></PicGrid>
  </div>
</template>

<script>
  import Slider from '@/components/Slider.vue'
  import PicGrid from '@/components/PicGrid.vue'

  export default {
    name: 'home',
    components: {
      Slider,
      PicGrid
    }
  }
</script>

<style>


</style>