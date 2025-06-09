<script setup>
// No script needed for this component
</script>

<template>
  <footer class="bg-black text-white py-12">
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
        <!-- Logo and Book Now Button -->
        <div class="flex flex-col items-center md:items-start">
          <div class="mb-4 bg-white">
            <img src="../assets/FILE_1182.svg" alt="All Cuts Logo" class="h-64 md:h-64 w-auto logo-rotate p-6">
            <span class="ml-2 text-xs bg-red text-white px-2 py-1 rounded">FOR KIDS & ADULTS</span>
          </div>
          <button class="bg-red hover:bg-light-red text-white px-8 py-3 rounded-full transition duration-300 w-full md:w-auto">
            BOOK NOW
          </button>
        </div>

        <!-- Quick Links -->
        <div>
          <h3 class="text-lg font-bold mb-4 flex items-center text-white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-red" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
            Quick Links
          </h3>
          <ul class="space-y-2">
            <li><a href="#" class="hover:text-red transition duration-200">Home</a></li>
            <li><a href="#" class="hover:text-red transition duration-200">About Us</a></li>
            <li><a href="#" class="hover:text-red transition duration-200">Services</a></li>
            <li><a href="#" class="hover:text-red transition duration-200">Careers</a></li>
            <li><a href="#" class="hover:text-red transition duration-200">Contact Us</a></li>
          </ul>
        </div>

        <!-- Hours of Operation -->
        <div>
          <h3 class="text-lg font-bold mb-4 flex items-center text-white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-red" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
            OPENING HOURS
          </h3>
          <ul class="space-y-1">
            <li>Monday: 10 AM–7 PM</li>
            <li>Tuesday: Closed</li>
            <li>Wednesday: 10 AM–7 PM</li>
            <li>Thursday: 10 AM–7 PM</li>
            <li>Friday: 9 AM–7 PM</li>
            <li>Saturday: 9 AM–7 PM</li>
            <li>Sunday: 9 AM–4 PM</li>
          </ul>
        </div>

        <!-- Visit Us -->
        <div>
          <h3 class="text-lg font-bold mb-4 flex items-center text-white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-red" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd" />
            </svg>
            Visit Us
          </h3>
          <address class="not-italic mb-4">
            Golden Scissors<br />
            1011 B Memorial Blvd<br />
            Murfreesboro, TN 37129
          </address>
          <p class="mb-2 flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-2 text-red" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
            </svg>
            Phone: <a href="tel:615-689-9108" class="hover:text-red">615-689-9108</a>
          </p>
          <p class="mb-2 flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-2 text-red" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
            </svg>
            Email: <a href="mailto:allcutsforkidsandadults@gmail.com" class="hover:text-red">allcutsforkidsandadults@gmail.com</a>
          </p>
          <div class="mt-4 flex space-x-4">
            <a href="https://www.facebook.com/profile.php?id=100012496934554&mibextid=LQQJ4d" class="text-white hover:text-red">
              <span class="sr-only">Facebook</span>
              <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" />
              </svg>
            </a>
            <a href="https://www.instagram.com/goldenscissors._" class="text-white hover:text-red">
              <span class="sr-only">Instagram</span>
              <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path fill-rule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z" clip-rule="evenodd" />
              </svg>
            </a>
            <a href="https://www.tiktok.com/@goldenscissorsbarber" class="text-white hover:text-red">
              <span class="sr-only">TikTok</span>
              <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path d="M12.53.02C13.84 0 15.14.01 16.44 0c.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z" />
              </svg>
            </a>
          </div>
        </div>
      </div>
      
      <div class="mt-12 pt-8 border-t border-gray-700 text-center text-sm">
        <p>© 2025 Golden Scissores Barber Shop Kids & Adults | Designed with love and precision ✂️</p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.logo-rotate {
  transform: rotate(86deg);
  transform-origin: center;
  transition: transform 0.3s ease;
}
</style>
