<script setup>
import { ref } from 'vue';
import logo from '../assets/FILE_1182.svg';
const isMenuOpen = ref(false);

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value;
};
</script>

<template>
  <nav class="bg-white border-b border-gray-200 fixed w-full z-50">
    <div class="w-full px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
      <!-- Left: Navigation Links -->
      <div class="hidden md:flex items-center space-x-4">
        <a href="#" class="text-black hover:text-red px-3">Home</a>
        <a href="#" class="text-black hover:text-red px-3">About</a>
        <a href="#" class="text-black hover:text-red px-3">Services</a>
        <a href="#" class="text-black hover:text-red px-3">Contact</a>
        <button class="bg-red text-white px-4 py-2 rounded hover:bg-light-red">Find Location</button>
      </div>

      <!-- Center: Logo -->
      <div class="flex items-center justify-center">
        <img src="../assets/FILE_1182.svg" alt="All Cuts Logo" class="h-10 w-auto logo-rotate">
        
        <div class="ml-2 flex flex-col items-start">
          <span class="text-xs bg-black text-white px-2 py-0.5 rounded">FOR KIDS & ADULTS</span>
          <span class="text-xs text-black">MURFREESBORO TENNESSEE</span>
        </div>
      </div>

      <!-- Right: Location Button -->
      <div class="hidden md:block">
        <button class="bg-red text-white px-4 py-2 rounded hover:opacity-80">MURFREESBORO TN</button>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden">
        <button @click="toggleMenu" class="text-white focus:outline-none">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path v-if="!isMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
            <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
          </svg>
        </button>
      </div>
    </div>

    <!-- Mobile Menu -->
    <div v-if="isMenuOpen" class="md:hidden bg-white w-full border-t border-gray-200">
      <div class="w-full px-4 py-3">
        <div class="flex flex-col space-y-3">
          <a href="#" class="text-black hover:text-red py-2">Home</a>
          <a href="#" class="text-black hover:text-red py-2">About</a>
          <a href="#" class="text-black hover:text-red py-2">Services</a>
          <a href="#" class="text-black hover:text-red py-2">Contact</a>
          <button class="bg-red text-white px-4 py-2 rounded hover:bg-light-red w-full">Find Location</button>
          <button class="bg-black text-white px-4 py-2 rounded hover:opacity-80 w-full mt-2">MURFREESBORO TN</button>
        </div>
      </div>
    </div>
  </nav>
  
  <!-- Spacer to prevent content from hiding under fixed navbar -->
  <div class="h-20"></div>
</template>

<style scoped>
nav {
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.logo-rotate {
  transform: rotate(86deg);
  transform-origin: center;
  transition: transform 0.3s ease;
}
</style>
