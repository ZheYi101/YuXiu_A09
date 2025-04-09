<script setup lang="ts">
import {RouterView} from 'vue-router'
import * as echarts from 'echarts/core';
import {
  DatasetComponent,
  GridComponent,
  TransformComponent
} from 'echarts/components';
import {BarChart} from 'echarts/charts';
import {CanvasRenderer} from 'echarts/renderers';

echarts.use([
  DatasetComponent,
  GridComponent,
  TransformComponent,
  BarChart,
  CanvasRenderer
]);
</script>

<template>
  <div id="web">
    <RouterView/>
  </div>
</template>

<style scoped>
</style>
