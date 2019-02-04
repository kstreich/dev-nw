<template>
  <div id="app">
    <!-- <div class="row container-fluid">
      <p class="col-lg-1 col-sm-1">Home</p>
      <p class="col-lg-1 col-sm-1">Portfolio</p>
      <p class="col-lg-8 spacing col-sm-1">devNorthwest</p>
      <p class="col-lg-1 col-sm-1">About</p>
      <p class="col-lg-1 col-sm-1">Contact</p>
    </div> -->

    <div class="row container-fluid navBar">
      <p>Home</p>
      <p>Portfolio</p>
      <p class="spacing">devNorthwest</p>
      <p>About</p>
      <p>Contact</p>
    </div>



    <router-view />
  </div>
</template>

<style>
  .spacing {
    text-align: center
  }

  .navBar {
    display: flex;
    justify-content: space-around;

  }
</style>