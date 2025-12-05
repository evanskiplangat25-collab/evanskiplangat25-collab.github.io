<template>
  <div class="min-h-screen bg-gray-50 dark:bg-gray-950">
    <UContainer class="py-8">
      <div class="text-center">
        <h1 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
          Welcome to My Portfolio
        </h1>
        <p class="text-xl text-gray-600 dark:text-gray-400 mb-8">
          A modern web application built with Nuxt.js
        </p>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-12">
          <UCard>
            <template #header>
              <h3 class="text-lg font-semibold">About</h3>
            </template>
            <p class="text-gray-600 dark:text-gray-400">
              Learn more about my skills and experience.
            </p>
            <template #footer>
              <UButton variant="outline" size="sm">Learn More</UButton>
            </template>
          </UCard>
          
          <UCard>
            <template #header>
              <h3 class="text-lg font-semibold">Projects</h3>
            </template>
            <p class="text-gray-600 dark:text-gray-400">
              Explore my latest work and contributions.
            </p>
            <template #footer>
              <UButton variant="outline" size="sm">View Projects</UButton>
            </template>
          </UCard>
          
          <UCard>
            <template #header>
              <h3 class="text-lg font-semibold">Contact</h3>
            </template>
            <p class="text-gray-600 dark:text-gray-400">
              Get in touch for collaborations.
            </p>
            <template #footer>
              <UButton variant="outline" size="sm">Contact Me</UButton>
            </template>
          </UCard>
        </div>

        <div class="mt-12">
          <UButton size="lg" class="mr-4">Get Started</UButton>
          <UButton variant="outline" size="lg">Learn More</UButton>
        </div>
      </div>
    </UContainer>
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