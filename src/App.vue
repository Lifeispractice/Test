<template>
  <div id="app">
    <router-view></router-view>
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
  @import "./assets/css/base.css";
</style>
<!--
118.12-(掌握)tabbar-基本结构的搭建(Av59594689,P118).mp4
119.13-(掌握)tabbar-TabBar和TabBarItem组件封装(Av59594689,P119).mp4
120.14-(掌握)tabbar-给TabBarItem传入active图片(Av59594689,P120).mp4
121.15-(掌握)tabbar-TabBarItem和路由结合效果(Av59594689,P121).mp4
122.16-(掌握)tabbar-TabBarItem的颜色动态控制(Av59594689,P122).mp4
123.17-(了解)知识回顾(Av59594689,P123).mp4

## 一、Vue Cli
### 1.1.runtime-compiler和runtime-only的区别
  - ESLint到底是什么？（代码检测）
  - template => ast => render => vdom => 真实DOM
  - render:(h)=>h,=>createElement
### 1.2.Vue Cli3
  - 如何通过CLI3创建项目
  - CLI3的目录结构
  - 配置文件：1.Vue UI 2.隐藏的配置文件 3.自定义 Vue.config.js
## 二、Vue-Router
### 2.1.什么是前端路由
- 后端渲染\后端路由
- 前后端分离
- SPA\前端路由
### 2.2.路由的基本配置
- 安装vue-router
- Vue.use->创建VueRouter对象->挂载到Vue实例上
- 配置映射关系：1.创建组件 2.配置映射关系 3.使用 router-link/router-view
### 2.3.细节处理
- 默认路由：redirect
- mode：history
- router-link->tag/replace/active-class
### 2.4.动态路由
- /user/：id
- this.￥route.params.id
-
-


## 三、Vuex


 -->
