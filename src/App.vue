<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <!-- 头部组件 -->
    <NavHeader/>
    <!-- 中间内容区域 -->
    <div id="main">

    </div>

    <NavFooter/>
  </div>
</template>

<script>
import NavHeader from "./components/NavHeader.vue";
import NavFooter from './components/NavFooter.vue'

export default {
  name: "App",
  components: {
    NavHeader,
    NavFooter
  }
};
</script>

<style>
#main{
  width: 1200px;
  height: 1000px;
  background: hotpink;
  margin: 0 auto;
  margin-top: 100px;
}
</style>
