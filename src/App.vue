<template>
  <div id="app">
    <router-view></router-view>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="deepPink">
        <img slot="item-icon" src="./assets/img/tabbar/sy.svg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/syHover.svg" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="#00f">
        <img slot="item-icon" src="./assets/img/tabbar/fl.svg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/flHover.svg" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart">
        <img slot="item-icon" src="./assets/img/tabbar/gwc.svg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/gwcHover.svg" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile">
        <img slot="item-icon" src="./assets/img/tabbar/wo.svg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/woHover.svg" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>
<script>
  import TabBar from './components/tabbar/TabBar'
  import TabBarItem from './components/tabbar/TabBarItem'
  export default {
    name: 'App',
    components: {
      TabBar,
      TabBarItem
    }
  }

</script>
<style>
  @import "./assets/css/base.css";

</style>
<!--
118.12-(掌握)tabbar-基本结构的搭建(Av59594689,P118).mp4
119.13-(掌握)tabbar-TabBar和TabBarItem组件封装(Av59594689,P119).mp4
120.14-(掌握)tabbar-给TabBarItem传入active图片(Av59594689,P120).mp4
121.15-(掌握)tabbar-TabBarItem和路由结合效果(Av59594689,P121).mp4
122.16-(掌握)tabbar-TabBarItem的颜色动态控制(Av59594689,P122).mp4
123.17-(了解)知识回顾(Av59594689,P123).mp4
-->
