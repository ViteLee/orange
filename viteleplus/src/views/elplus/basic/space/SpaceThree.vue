<template>
  <el-slider v-model="size" />
  <el-space wrap :size="size">
    <el-card v-for="i in 2" :key="i" class="box-card" style="width: 250px">
      <template #header>
        <div class="card-header">
          <span>Card name</span>
          <el-button class="button" type="text">Operation button</el-button>
        </div>
      </template>
      <div v-for="o in 4" :key="o" class="text item">{{ 'List item ' + o }}</div>
    </el-card>
  </el-space>
</template>

<script setup lang="ts">
import { ref } from 'vue-demi';
const size = ref(20);

</script>
