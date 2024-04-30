<script>
import AppTitle from './components/AppTitle.vue'

export default {

  components: {
    AppTitle,
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
