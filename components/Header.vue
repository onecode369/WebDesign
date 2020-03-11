<template>
  <div>
<div class="one-sidebar one-bar-block one-card one-animate-right color-main2-bg" style="display:none;right:0;width:20rem" id="rightMenu">
  <button @click="closeRightMenu()" class="one-bar-item one-button one-xxxlarge" style="text-align:right;color:#FFF">&times;</button>
  <nuxt-link to="/colors" class="nuxt-link one-bar-item one-button">Colors</nuxt-link>
  <nuxt-link to="/fonts" class="nuxt-link one-bar-item one-button">Fonts</nuxt-link>
</div>

<div class="color-main2-bg one-container">
  <div class="one-xxlarge one-left" style="color:#FFF;margin-top:5px">WebDesign</div>
  <button class="one-button color-main2-bg one-xxlarge one-right menu" style="color:#FFF" @click="openRightMenu()">&#9776;</button>
</div>
  </div>
</template>

<script>
export default {
  methods:{
    openRightMenu() {
      document.getElementById("rightMenu").style.display = "block";
    },
    closeRightMenu() {
      document.getElementById("rightMenu").style.display = "none";
    }
  }
}
</script>

<style scoped>
.one-bar-item:hover{
  background-color: rgb(122, 59, 182) !important;
}

.one-bar-item {
  color: #FFF !important;
  font-size: 20px;
}

.menu:hover {
  background-color: rgb(122, 59, 182) !important;
  color: #FFF !important;
}

.nuxt-link{
  text-decoration: none !important;
}
</style>

<style>
.color-main1-bg{
  background-color: #9ACD32;
}

.color-main1 {
  color: #9ACD32;
}

.color-main2-bg{
  background-color: #8A2BE2;
}

.color-main2 {
  color: #8A2BE2;
}

.color-main3-bg{
  background-color: #FF5349;
}

.color-main3 {
  color: #FF5349;
}
</style>
