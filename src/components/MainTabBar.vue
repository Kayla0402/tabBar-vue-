<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <img slot="item_icon" src="../assets/image/tabBar/home.png" alt="">
      <img slot="item_icon_active" src="../assets/image/tabBar/homeA.png" alt="">
      <div slot="item_title">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="yellow">
      <img slot="item_icon" src="~assets/image/tabBar/friends.png" alt="">
      <img slot="item_icon_active" src="~assets/image/tabBar/friendsA.png" alt="">
      <div slot="item_title">人脉</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="red">
      <img slot="item_icon" src="../assets/image/tabBar/message.png" alt="">
      <img slot="item_icon_active" src="../assets/image/tabBar/messageA.png" alt="">
      <div slot="item_title">消息</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="green">
      <img slot="item_icon" src="../assets/image/tabBar/mine.png" alt="">
      <img slot="item_icon_active" src="../assets/image/tabBar/mineA.png" alt="">
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
