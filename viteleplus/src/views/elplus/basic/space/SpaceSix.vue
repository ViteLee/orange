<template>
  <div
    style="
      width: 240px;
      margin-bottom: 20px;
      padding: 8px;
      border: 1px solid #ccc;
    "
  >
    <el-space>
      string
      <el-button>button</el-button>
      <el-card>
        <template #header>header</template>
        body
      </el-card>
    </el-space>
  </div>
  <div
    style="
      width: 240px;
      margin-bottom: 20px;
      padding: 8px;
      border: 1px solid #ccc;
    "
  >
    <el-space alignment="flex-start">
      string
      <el-button>button</el-button>
      <el-card>
        <template #header>header</template>
        body
      </el-card>
    </el-space>
  </div>
  <div
    style="
      width: 240px;
      margin-bottom: 20px;
      padding: 8px;
      border: 1px solid #ccc;
    "
  >
    <el-space alignment="flex-end">
      string
      <el-button>button</el-button>
      <el-card>
        <template #header>header</template>
        body
      </el-card>
    </el-space>
  </div>
</template>
