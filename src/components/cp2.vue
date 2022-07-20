<template>
    <div>cp2</div>
    <div>{{data.null}}</div>
</template>
<script lang="ts" setup>
import { onMounted, ref } from 'vue'
defineProps<{
    el: any
}>()
const data = ref<any>()
onMounted(() => {
    console.log('cp2')
})
</script>
<style lang="less" scoped>
</style>