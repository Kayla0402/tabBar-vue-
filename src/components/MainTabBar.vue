<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <img slot="item_icon" src="../assets/image/tabBar/1.png" alt="">
      <img slot="item_icon_active" src="../assets/image/tabBar/1_1.png" alt="">
      <div slot="item_title">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="yellow">
      <img slot="item_icon" src="~assets/image/tabBar/1.png" alt="">
      <img slot="item_icon_active" src="~assets/image/tabBar/1_1.png" alt="">
      <div slot="item_title">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="red">
      <img slot="item_icon" src="../assets/image/tabBar/1.png" alt="">
      <img slot="item_icon_active" src="../assets/image/tabBar/1_1.png" alt="">
      <div slot="item_title">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="green">
      <img slot="item_icon" src="../assets/image/tabBar/1.png" alt="">
      <img slot="item_icon_active" src="../assets/image/tabBar/1_1.png" alt="">
      <div slot="item_title">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import tabBar from 'components/tabBar/TarBar'
  import tabBarItem from 'components/tabBar/TabBarItem'

  export default {
    name: "MainTabBar",
    components: {
      tabBar,
      tabBarItem
    }
  }
</script>

<style scoped>

</style>
