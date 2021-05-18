<template>
  <div class="v-main-wrapper">
    <v-menu />
    <v-top />
  </div>
</template>

<script>
import vMenu from  './v-menu'
import VTop from "./v-top";
export default {
  name: "v-main-wrapper",
  components: {
    VTop,
    vMenu
  }
}
</script>

<style scoped>
  .v-main-wrapper{
    display: flex;
    max-width: 1140px;
    margin: 0 auto;
  }
</style>