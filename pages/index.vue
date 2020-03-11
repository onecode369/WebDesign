<template>
  <div class="container">
    <div class="first-heading one-animate-zoom">WebDesign</div>
  </div>
</template>
<script>

export default {
  components: {
  }
}
</script>

<style>
.container {
  background-image: linear-gradient(rgba(137, 43, 226, 0.4),rgba(137, 43, 226, 0.4)) , url('~assets/main-wallpaper.jpeg');
  min-width: 100vw;
  min-height: 80vh;
  clip-path: polygon(0 0 , 100% 0, 100% 80%,0 100%);
  background-attachment: fixed;
}

.first-heading {
  font-size: 10vw;
  width: fit-content;
  padding-top: 20vh;
  margin: auto;
  color: rgba(255, 255, 255, 0.7);
}
</style>
