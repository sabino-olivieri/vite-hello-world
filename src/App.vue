<script>
import AppTitle from './components/AppTitle.vue';
import AppBanner from './components/AppBanner.vue';
import AppImage from './components/AppImage.vue';

export default {

  components: {
    AppTitle,
    AppBanner,
    AppImage,
  },

  data() {
    return {

    }
  },
}
</script>

<template>

  <div class="container">

    <AppTitle />
    <AppImage />
  </div>

</template>

<style>
.container {
  width: 70%;
  margin: 20px auto;
  background-color: bisque;
  text-align: center;
  border-radius: 10px;
  padding: 20px;
  font-family: 'Courier New', Courier, monospace;
}
</style>
