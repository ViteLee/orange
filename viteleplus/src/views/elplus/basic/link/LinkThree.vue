<template>
  <div>
    <el-link :icon="Edit">Edit</el-link>
    <el-link>
      Check<el-icon class="el-icon--right"><icon-view /></el-icon>
    </el-link>
  </div>
</template>

<script setup lang="ts">
import { Edit, View as IconView } from '@element-plus/icons'
</script>

<style lang="less" scoped>
.el-link {
  margin-right: 16px;
  &::last-child {
    margin-right: 0;
  }
}
</style>
