<template>
  <div id="zheXiantu"></div>
  <div id="app"></div>
</template>

<script>
import { makeZheXianTu } from './myEchart.js';

export default {
  name: 'App',
  mounted() {
    makeZheXianTu();
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
