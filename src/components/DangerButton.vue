<template>
  <el-button type="danger" @click="handleClick">
    <slot>Danger Button222</slot>
  </el-button>
</template>

<script setup>
// This is a test modification
const handleClick = () => {
  console.log('Danger button clicked');
};
</script>

<style scoped>
/* Add any custom styles here */
</style>