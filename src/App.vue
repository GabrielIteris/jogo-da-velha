<template>
  <div id="app">
    <a>Projeto para ajudar povo Berberie</a>
    <jv id="table"></jv>
    <span> AJUDE O POVO BERBERIE </span>
  </div>
</template>

<script>
import jv from '@/views/jv'
export default {
  name: 'app',
  components: { jv }
}
</script>

<style>
a {
  display: flexbox;
  text-decoration: floralwhite;
  color: white;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  justify-content: center;
}
#app {
  font-family: Courier New, Courier, monospace;
  float: left;
  margin: 20px;
  padding: 50px;
  height: 1360px;
  width: 880px;
  min-width: 370px;
  min-height: 580px;
  background-color: burlywood;
}

#table {
  display: flexbox;
  justify-content: flex-end;
}
</style>