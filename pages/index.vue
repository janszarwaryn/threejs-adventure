<script setup>
useHead({
  title: 'Home',
  meta: [
    //{name: 'description', content: ''},
    //{property: 'og:description', content: ''},
    //{property: 'og:image', content: ''},
  ]
});
</script>


<template>
  <div class="container w100 d-flex jc-center fd-column">
    <a href="https://github.com/janszarwaryn/threejs-adventure" target="_blank" title="Johnny GitHub">
      <img src="/img/favicon.png" class="logo" alt="logo">
    </a>
    <h1>ThreeJS adventure</h1>
    <p>Exercise projects and recaps while learning Three.js with
      <a href="https://threejs-journey.com/" target="_blank"><strong>ThreeJS Journey</strong></a></p>
  </div>
</template>

<style scoped>
.logo {width:60px;}
.container {min-height:100vh; padding-bottom:15vh;}
</style>
