<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  name: 'App',
  components: {
    Header,
}
}
</script>

<style>
.container {
  width: 80%;
  margin: 0 auto;
}
</style>
