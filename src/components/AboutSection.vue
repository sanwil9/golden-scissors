<script setup>
// No script needed for this component
</script>

<template>
  <section class="py-24 bg-red-600 w-full">
    <div class="w-full px-4">
      <div class="bg-white rounded-xl p-12 shadow-xl mx-auto max-w-full">
        <div class="flex flex-col md:flex-row items-center justify-between max-w-7xl mx-auto">
          <!-- Left side - Content -->
          <div class="w-full md:w-1/2 mb-12 md:mb-0 pr-0 md:pr-16">
            <h2 class="text-5xl font-bold mb-8 text-center md:text-left">About Us</h2>
            
            <div class="flex items-center mb-6">
              <h3 class="text-3xl font-bold">
                All Cuts for Kids & Adults — More Than Just a Haircut
              </h3>
            </div>
            
            <p class="text-gray-700 mb-10 text-xl leading-relaxed">
              At All Cuts for Kids & Adults, we believe a great haircut can make someone's day — no matter their age! Whether it's 
              your child's first trim or your regular style refresh, we're here to make every visit comfortable, fun, and memorable.
            </p>
            
            <div class="text-center md:text-left">
              <button class="bg-white hover:bg-gray-100 text-red border-2 border-red px-10 py-3 rounded-full transition duration-300 font-medium text-lg">
                READ MORE
              </button>
            </div>
          </div>
          
          <!-- Right side - Image -->
          <div class="w-full md:w-1/2">
            <div class="rounded-xl overflow-hidden shadow-xl">
              <img 
                src="https://images.unsplash.com/photo-1503951914875-452162b0f3f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" 
                alt="Child getting a haircut" 
                class="w-full h-auto"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Component-specific styles */
</style>
