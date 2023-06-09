<script setup>
// import { RouterView } from "vue-router";
</script>

<template>
  <div>Website Helper</div>
</template>

<style scoped>
/* nunito-sans-regular - latin */
@font-face {
  font-family: "Nunito Sans";
  font-style: normal;
  font-weight: 400;
  src: url("./assets/fonts/nunito-sans-v12-latin-regular.eot"); /* IE9 Compat Modes */
  src: local(""),
    url("./assets/fonts/nunito-sans-v12-latin-regular.eot?#iefix")
      format("embedded-opentype"),
    /* IE6-IE8 */ url("./assets/fonts/nunito-sans-v12-latin-regular.woff2")
      format("woff2"),
    /* Super Modern Browsers */
      url("./assets/fonts/nunito-sans-v12-latin-regular.woff") format("woff"),
    /* Modern Browsers */
      url("./assets/fonts/nunito-sans-v12-latin-regular.ttf") format("truetype"),
    /* Safari, Android, iOS */
      url("./assets/fonts/nunito-sans-v12-latin-regular.svg#NunitoSans")
      format("svg"); /* Legacy iOS */
}

body {
  height: 100vh;
  width: 100vh;
}
main {
  height: 100%;
  width: 100%;
  justify-content: center;
  font-family: "Nunito Sans";
}
</style>
