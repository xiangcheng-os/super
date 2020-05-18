
<template>
  <div id="app" class="wrapper">
    <router-view/>

    <main-tab-bar/>
  </div>
</template>

<script>
import MainTabBar from 'components/content/MainTabBar'
// import Home from 'views/home/Home'


export default {
  name: 'app',
  components: {
    MainTabBar,
    // Home
  }
}
</script>

<style>
@import "./assets/css/base.css";
</style>
