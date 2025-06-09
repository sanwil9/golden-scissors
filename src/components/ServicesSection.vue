<script setup>
// No script needed for this component
</script>

<template>
  <section class="py-16 border-b border-gray-200">
    <div class="w-full px-4">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Our Services Panel -->
        <div class="bg-yellow-600 text-white rounded-lg p-8 shadow-md transform transition-transform hover:scale-105 relative overflow-hidden md:h-[500px] flex flex-col">
          <!-- Background image with overlay -->
          <div class="absolute inset-0 bg-cover bg-center opacity-10" style="background-image: url('https://images.unsplash.com/photo-1560066984-138dadb4c035?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8aGFpciUyMHNhbG9ufGVufDB8fDB8fHww&auto=format&fit=crop&w=800&q=60');"></div>
          
          <div class="relative z-10 flex flex-col flex-grow">
            <h2 class="text-3xl font-bold mb-4 text-white">Our Services</h2>
            <p class="mb-6 flex-grow">
              We offer top-quality haircuts for both kids and adults in a friendly, 
              professional environment. Whether you're looking for a classic cut, a modern 
              style, or a special occasion look, our skilled barbers ensure every client leaves looking 
              and feeling their best.
            </p>
            <button class="bg-red text-white px-8 py-3 rounded-full hover:bg-light-red transition duration-300 font-bold mt-auto">
              SEE SERVICES
            </button>
          </div>
        </div>

        <!-- Our Location Panel -->
        <div class="bg-red-500 text-white rounded-lg p-8 shadow-md transform transition-transform hover:scale-105 relative overflow-hidden md:h-[500px] flex flex-col">
          <!-- Background image with overlay -->
          <div class="absolute inset-0 bg-cover bg-center opacity-10" style="background-image: url('https://images.unsplash.com/photo-1560066984-138dadb4c035?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8aGFpciUyMHNhbG9ufGVufDB8fDB8fHww&auto=format&fit=crop&w=800&q=60');"></div>
          
          <div class="relative z-10 flex flex-col flex-grow">
            <h2 class="text-3xl font-bold mb-4 text-white">Our Location</h2>
            <p class="mb-6 flex-grow">
              Visit us at All Cuts for Kids & Adults conveniently located at 1011 B Memorial Blvd
              Murfreesboro, TN 37129. Walk-ins welcome or book your appointment 
              today. We look forward to seeing you.
            </p>
            <button class="bg-white text-red px-8 py-3 rounded-full hover:bg-light-red transition duration-300 font-bold mt-auto">
              FIND LOCATION
            </button>
          </div>
        </div>

        <!-- Career Panel -->
        <div class="bg-blue-600 text-white rounded-lg p-8 shadow-md transform transition-transform hover:scale-105 relative overflow-hidden md:h-[500px] flex flex-col">
          <!-- Background image with overlay -->
          <div class="absolute inset-0 bg-cover bg-center opacity-10" style="background-image: url('https://images.unsplash.com/photo-1560066984-138dadb4c035?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8aGFpciUyMHNhbG9ufGVufDB8fDB8fHww&auto=format&fit=crop&w=800&q=60');"></div>
          
          <div class="relative z-10 flex flex-col flex-grow">
            <h2 class="text-3xl font-bold mb-4 text-white">Career</h2>
            <p class="mb-6 flex-grow">
              We're looking for passionate and skilled individuals who love working with 
              kids and adults to create a fun, welcoming salon experience. 
              Apply today and take the next step in your career with All Cuts for Kids and 
              Adults!
            </p>
            <button class="bg-white text-red px-8 py-3 rounded-full hover:bg-gray-100 transition duration-300 font-bold mt-auto">
              APPLY TODAY
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Component-specific styles */
</style>
