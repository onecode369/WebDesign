<template>
  <div class="one-card fonts-card-main">
    <div class="fonts-title color-main2">
      {{ title }}
    </div>
    <div class="fonts-thumbnail">
      <img class="fonts-thumbnail-img" :src="thumbnail" alt="thumbnail">
    </div>
    <div class="fonts-download">
      <a :href="link">Download font</a>
    </div>
  </div>
</template>

<script>
export default {
  props : {
    title : String,
    thumbnail : String,
    description : String,
    link : String
  }
}
</script>

<style scoped>
.fonts-title {
  font-size : 32px;
  padding : 10px 20px;
}

.fonts-thumbnail-img {
  width : 100%;
  margin :auto;
}

.fonts-download {
  padding : 10px;
  font-size : 20px;
}

a {
  text-decoration : none;
}
</style>
