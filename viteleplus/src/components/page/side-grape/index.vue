<template>
  <el-menu :default-active="defaultActive" router>
    <el-menu-item index="/grape/page1">图播面板一</el-menu-item>
    <el-menu-item index="/grape/page2">图播面板二</el-menu-item>
    <el-menu-item index="/grape/page3">图播面板三</el-menu-item>
    <el-menu-item index="/grape/page4">图播面板四</el-menu-item>
    <el-menu-item index="/grape/page5">图播面板五</el-menu-item>
  </el-menu>
</template>

<script setup>
const defaultActive = '/grape/page1';
</script>