<script setup>
// No script needed for this component
</script>

<template>
  <section class="py-24 bg-red">
    <div class="w-full px-4">
      <div class="bg-white rounded-xl p-12 shadow-xl mx-auto max-w-full">
        <div class="flex flex-col md:flex-row items-center justify-between max-w-7xl mx-auto">
          <!-- Left side - Image -->
          <div class="w-full md:w-1/2 mb-12 md:mb-0">
            <div class="rounded-xl overflow-hidden shadow-xl">
              <img 
                src="https://images.unsplash.com/photo-1559599101-f09722fb4948?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" 
                alt="Child getting a haircut" 
                class="w-full h-auto"
              />
            </div>
          </div>
          
          <!-- Right side - Content -->
          <div class="w-full md:w-1/2 md:pl-16">
            <h2 class="text-5xl font-bold mb-8">Why Choose Us</h2>
            
            <div class="flex items-center mb-6">
              <h3 class="text-3xl font-bold">
                More Than Just a Haircut — It's an Experience
              </h3>
            </div>
            
            <p class="text-gray-700 mb-10 text-xl leading-relaxed">
              At All Cuts for Kids & Adults, we believe every haircut should be an experience to remember! Whether it's your child's 
              first time or a fresh new style for you, we create a fun, welcoming space where kids can smile and adults can relax. 
              Our skilled stylists are dedicated to delivering styles that suit all ages — making every visit quick, easy, and 
              enjoyable. At All Cuts, we don't just cut hair — we create memories.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Component-specific styles */
</style>
