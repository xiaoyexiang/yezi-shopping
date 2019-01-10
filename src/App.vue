<template>
  <div id="app">
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
  html, body {
    position: relative;
    width: 100%;
    height: 100%;
  }
  #app {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: 10;
    width: 100%;
    height: 100%;
    background: #f4f6f8;
  }
</style>
