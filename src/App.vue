<template>
  <cp1-vue ref="cp1"></cp1-vue>
  <cp2-vue :el="cp1"></cp2-vue>
</template>
<script lang="ts" setup>
import { ref } from 'vue'
import cp1Vue from './components/cp1.vue';
import cp2Vue from './components/cp2.vue';
const cp1  = ref<typeof cp1Vue>()
</script>
<style lang="less" scoped>
</style>