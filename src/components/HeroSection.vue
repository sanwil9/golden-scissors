<script setup>
// No script needed for this component
</script>

<template>
  <section class="pt-28 pb-16 border-b border-gray-200">
    <div class="container mx-auto px-4">
      <div class="flex flex-col md:flex-row items-center justify-between">
        <!-- Left side - Image -->
        <div class="w-full md:w-1/2 mb-8 md:mb-0">
          <div class="rounded-lg overflow-hidden shadow-lg">
            <img 
              src="https://images.unsplash.com/photo-1580618672591-eb180b1a973f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8aGFpcmN1dHxlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&w=800&q=80" 
              alt="Professional haircut" 
              class="w-full h-auto rounded-lg"
            />
          </div>
        </div>
        
        <!-- Right side - Content -->
        <div class="w-full md:w-1/2 md:pl-12 flex flex-col items-center md:items-start">
          <div class="text-center md:text-left mb-8">
            <div class="flex items-center mb-8">
              <div class="relative">
                <img src="../assets/FILE_1182.svg" alt="All Cuts Logo" class="h-20 md:h-24 w-auto logo-rotate">
              </div>
              
              <div class="ml-4 flex flex-col">
                <span class="bg-black text-white px-3 py-1 rounded text-sm font-bold">FOR KIDS & ADULTS</span>
                <span class="text-sm text-black font-medium mt-1">MURFREESBORO TENNESSEE</span>
              </div>
            </div>
            <h2 class="text-3xl md:text-4xl text-gray-800 font-bold mt-6">The ultimate kids' cut experience</h2>
          </div>
          <button class="bg-red hover:bg-light-red text-white font-bold py-4 px-12 rounded-full text-xl transition duration-300 mt-4 shadow-md w-full md:w-auto">
            BOOK NOW
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.logo-rotate {
  transform: rotate(86deg);
  transform-origin: center;
  transition: transform 0.3s ease;
}

.bg-red {
  background-color: #ff0000;
}

.hover\:bg-light-red:hover {
  background-color: #ff3333;
}
</style>
