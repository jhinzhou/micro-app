<script setup>
import { ref } from 'vue'

</script>

<template>
  <div style="width:200px;height:200px;">
    <h1>主应用</h1>
    <WujieVue name="micro1" url="http://127.0.0.1:5174" style="width:100%;height:100%;"></WujieVue>
    <WujieVue name="micro2" url="http://127.0.0.1:5175" style="width:100%;height:100%;"></WujieVue>
  </div>
</template>

<style scoped>

</style>
