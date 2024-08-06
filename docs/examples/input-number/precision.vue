<template>
  <el-input-number v-model="num" :precision="0" :step="1" :max="10" />
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const num = ref(1)
</script>
