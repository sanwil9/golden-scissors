<script setup>
// Import components we'll create
import Navbar from './components/Navbar.vue'
import HeroSection from './components/HeroSection.vue'
import ServicesSection from './components/ServicesSection.vue'
import AboutSection from './components/AboutSection.vue'
import WhyChooseSection from './components/WhyChooseSection.vue'
import TestimonialsSection from './components/TestimonialsSection.vue'
import FooterSection from './components/FooterSection.vue'
</script>

<template>
  <div class="app-container">
    <Navbar />
    <main>
      <HeroSection />
      <ServicesSection />
      <AboutSection />
      <WhyChooseSection />
      <TestimonialsSection />
    </main>
    <FooterSection />
  </div>
</template>

<style>
/* Global styles will be in style.css */
.app-container {
  width: 100%;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

main {
  flex: 1;
}
</style>
