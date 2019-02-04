<template>
  <div class="picGrid">

    <img class="col-sm-6 col-6 noPadding" src="../assets/tiles/tile-1.jpg">
    <img class="col-sm-6 col-6 noPadding" src="../assets/tiles/tile-2.jpg">
    <img class="col-sm-6 col-6 noPadding" src="../assets/tiles/tile-3.jpg">
    <img class="col-sm-6 col-6 noPadding" src="../assets/tiles/tile-4.jpg">
    <img class="col-sm-6 col-6 noPadding" src="../assets/tiles/tile-5.jpg">
    <img class="col-sm-6 col-6 noPadding" src="../assets/tiles/tile-6.jpg">

  </div>
</template>

<script>
  export default {
    name: 'PicGrid',
    data() {
      return {

      }
    },
    computed: {},
    methods: {}
  }

</script>

<style>
  .noPadding {
    padding-left: 0px;
    padding-right: 0px;
  }
</style>