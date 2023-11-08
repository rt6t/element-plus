<template>
  <el-input-number v-model="num" :step="1" />
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const num = ref(5)
</script>
