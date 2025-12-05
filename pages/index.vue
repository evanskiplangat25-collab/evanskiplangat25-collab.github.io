<template>
  <div class="min-h-screen bg-gray-50">
    <div class="container mx-auto px-4 py-8">
      <div class="text-center">
        <h1 class="text-4xl font-bold text-gray-900 mb-4">
          Welcome to My Portfolio
        </h1>
        <p class="text-xl text-gray-600 mb-8">
          A modern web application built with Nuxt.js
        </p>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-12">
          <div class="bg-white p-6 rounded-lg shadow-md">
            <h3 class="text-lg font-semibold mb-2">About</h3>
            <p class="text-gray-600">
              Learn more about my skills and experience.
            </p>
          </div>
          
          <div class="bg-white p-6 rounded-lg shadow-md">
            <h3 class="text-lg font-semibold mb-2">Projects</h3>
            <p class="text-gray-600">
              Explore my latest work and contributions.
            </p>
          </div>
          
          <div class="bg-white p-6 rounded-lg shadow-md">
            <h3 class="text-lg font-semibold mb-2">Contact</h3>
            <p class="text-gray-600">
              Get in touch for collaborations.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// Page metadata
useHead({
  title: 'Home - My Portfolio',
  meta: [
    { name: 'description', content: 'Welcome to my portfolio website built with Nuxt.js' }
  ]
})
</script>