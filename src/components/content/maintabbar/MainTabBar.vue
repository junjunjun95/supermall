<template>
  <tab-bar>
    <tab-bar-item path="/home">
      <img slot="item-icon" src="../../../assets/img/tabbar/home.png" alt="">
      <img slot="item-active-icon" src="../../../assets/img/tabbar/home1.png" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/more">
      <img slot="item-icon" src="../../../assets/img/tabbar/category.png" alt="">
      <img slot="item-active-icon" src="../../../assets/img/tabbar/category1.png" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/shop">
      <img slot="item-icon" src="../../../assets/img/tabbar/shopcart.png" alt="">
      <img slot="item-active-icon" src="../../../assets/img/tabbar/shopcart1.png" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <img slot="item-icon" src="../../../assets/img/tabbar/profile.png" alt="">
      <img slot="item-active-icon" src="../../../assets/img/tabbar/profile1.png" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>

import TabBar from '../../common/tabbar/TabBar'
import TabBarItem from '../../common/tabbar/TabBarItem'

export default {
  name: 'MainTabBar',
  components:{
    TabBar,
    TabBarItem
  }
}
</script>

<style>

</style>