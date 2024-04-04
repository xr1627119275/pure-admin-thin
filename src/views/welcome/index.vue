<script setup lang="ts">
import { pcaTextArr } from "element-china-area-data";
import { ref } from "vue";
defineOptions({
  name: "Welcome"
});
import { RegionSelects } from "v-region";
</script>

<template>
  <h1>地区选择</h1>
  <RegionSelects />
</template>
