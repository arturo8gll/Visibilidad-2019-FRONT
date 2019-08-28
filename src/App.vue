<template>
  <div id="app">
    <div class="line"></div>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div class="line">
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
body{
  margin: 0;
  padding: 0;
  text-align: center;
}
img{
  margin-top: 50px;
  width: 400px;
}
.line{
  width: 100%;
  height: 35px;
  background-color: #1A415D;
  box-shadow:         0px 16px 16px 0px rgba(50, 50, 50, 0.19);
}
.footer{
  width: 100%;
  background-color: #1A415D;
  font-family: 'Open Sans', sans-serif;
  font-size: 12px;
}
</style>
