<template>
  <div>
    <el-link href="https://element.eleme.io" target="_blank">default</el-link>
    <el-link type="primary">primary</el-link>
    <el-link type="success">success</el-link>
    <el-link type="warning">warning</el-link>
    <el-link type="danger">danger</el-link>
    <el-link type="info">info</el-link>
  </div>
</template>

<style lang="less" scoped>
.el-link {
  margin-right: 16px;
  &::last-child {
    margin-right: 0;
  }
}
</style>