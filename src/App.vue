<template>
  <div id="app">
    <router-view/>
    <main-tab-bar/>
  </div>
</template>

<script>
  import MainTabBar from './components/MainTabBar'
  export default {
    name: 'App',
    components: {
      MainTabBar
    }
  }
</script>

<style>
  @import "assets/css/base.css";
  .tab_bar_item img{
    width: 24px;
    height: 24px;
    background-color: bisque;
    vertical-align: middle;
  }
  .active{
    color:red
  }
</style>
