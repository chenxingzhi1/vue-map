<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script setup lang="ts">
// import { onUnmounted } from 'vue'

let map: Map<any, any> | null = new Map()

for (let i = 0; i < 1000000; i++) {
  map.set(i, { label: 'label' + i, value: i })
}

// onUnmounted(()=>{
//   map = null
// })
</script>