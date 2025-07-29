<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100">
    <!-- Header -->
    <header class="bg-white shadow-sm border-b border-gray-200">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between items-center py-6">
          <div class="flex items-center">
            <h1 class="text-2xl font-bold text-gray-900">Simple Nuxt</h1>
          </div>
          <nav class="hidden md:flex space-x-8">
            <a href="#" class="text-gray-500 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">Home</a>
            <a href="#" class="text-gray-500 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">About</a>
            <a href="#" class="text-gray-500 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">Contact</a>
          </nav>
        </div>
      </div>
    </header>

    <!-- Main Content -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
      <!-- Hero Section -->
      <div class="text-center mb-16">
        <h1 class="text-4xl md:text-6xl font-bold text-gray-900 mb-6">
          Welcome to <span class="text-blue-600">Simple Nuxt</span>
        </h1>
        <p class="text-xl text-gray-600 max-w-3xl mx-auto mb-8">
          A modern, fast, and simple Nuxt.js application built with Vue 3 and Tailwind CSS.
        </p>
        <div class="flex flex-col sm:flex-row gap-4 justify-center">
          <button class="bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-8 rounded-lg transition duration-200">
            Get Started
          </button>
          <button class="border border-gray-300 hover:border-gray-400 text-gray-700 font-semibold py-3 px-8 rounded-lg transition duration-200">
            Learn More
          </button>
        </div>
      </div>

      <!-- Features Section -->
      <div class="grid md:grid-cols-3 gap-8 mb-16">
        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-200">
          <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center mb-4">
            <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
            </svg>
          </div>
          <h3 class="text-lg font-semibold text-gray-900 mb-2">Fast Performance</h3>
          <p class="text-gray-600">Built with Nuxt 4 for optimal performance and developer experience.</p>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-200">
          <div class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center mb-4">
            <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zM21 5a2 2 0 00-2-2h-4a2 2 0 00-2 2v12a4 4 0 004 4h4a2 2 0 002-2V5z"></path>
            </svg>
          </div>
          <h3 class="text-lg font-semibold text-gray-900 mb-2">Modern Design</h3>
          <p class="text-gray-600">Beautiful UI components styled with Tailwind CSS for a modern look.</p>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-200">
          <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center mb-4">
            <svg class="w-6 h-6 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
            </svg>
          </div>
          <h3 class="text-lg font-semibold text-gray-900 mb-2">Easy Development</h3>
          <p class="text-gray-600">Simple and intuitive development workflow with hot reload and TypeScript support.</p>
        </div>
      </div>

      <!-- CTA Section -->
      <div class="bg-blue-600 rounded-lg p-8 text-center">
        <h2 class="text-3xl font-bold text-white mb-4">Ready to get started?</h2>
        <p class="text-blue-100 mb-6 max-w-2xl mx-auto">
          Start building your next web application with this simple and powerful Nuxt.js template.
        </p>
        <button class="bg-white text-blue-600 hover:bg-gray-100 font-semibold py-3 px-8 rounded-lg transition duration-200">
          Start Building
        </button>
      </div>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white mt-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div class="text-center">
          <p class="text-gray-400">&copy; 2024 Simple Nuxt. Built with ❤️ using Nuxt.js and Tailwind CSS.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
useHead({
  title: 'Simple Nuxt App',
  meta: [
    { name: 'description', content: 'A modern, fast, and simple Nuxt.js application built with Vue 3 and Tailwind CSS.' }
  ]
})
</script> 