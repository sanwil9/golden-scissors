<script setup>
// Props for customization
const props = defineProps({
  width: {
    type: String,
    default: 'auto'
  },
  height: {
    type: String,
    default: 'auto'
  },
  rotation: {
    type: Number,
    default: 45 // Default rotation angle in degrees
  }
});
</script>

<template>
  <div class="logo-container" :style="`transform: rotate(${rotation}deg);`">
    <img 
      src="../assets/FILE_1182.svg" 
      alt="All Cuts Logo" 
      :width="width" 
      :height="height"
    />
  </div>
</template>

<style scoped>
.logo-container {
  display: inline-block;
  transform-origin: center;
  transition: transform 0.5s ease;
}
</style>
