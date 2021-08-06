<template>
  <div class="bg-gradient-to-r from-purple-300 to-blue-200">
    <div class="w-10/12 m-auto py-12 min-h-screen flex items-center justify-center">
      <div class="bg-white shadow overflow-hidden sm:rounded-lg pb-8">
        <div class="border-t border-gray-200 text-center pt-8 px-4">
          <h1 class="text-7xl md:text-9xl font-bold text-purple-400">404</h1>

          <template v-if="error.statusCode !== 404">
            <h2 class="text-4xl md:text-6xl font-medium py-6">oops! Page not found</h2>
            <p class="text-sm md:text-2xl pb-8 px-6 font-medium">Oops! The page you are looking for does not exist. It might have been moved or deleted.</p>
          </template>

          <template v-else>
            <h2 class="text-4xl md:text-6xl font-medium py-6">oops! An error occurred</h2>
            <p class="text-sm md:text-2xl pb-8 px-6 font-medium">Oops! The page you are looking for does not exist or occurred.</p>
          </template>

          <NuxtLink to="/" class="block md:inline-block bg-gradient-to-r from-purple-400 to-blue-500 hover:from-pink-500 hover:to-orange-500 text-white font-semibold px-6 py-3 rounded-md md:mr-6 mb-3 md:md-0">Home page</NuxtLink>

          <a href="#" class="block md:inline-block bg-gradient-to-r from-red-400 to-red-500 hover:from-red-500 hover:to-red-500 text-white font-semibold px-6 py-3 rounded-md">
            Contact Us
          </a>

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['error'],
  layout: 'error' // you can set a custom layout for the error page
}
</script>
