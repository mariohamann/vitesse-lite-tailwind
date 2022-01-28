<script setup lang="ts">
const props = defineProps<{ name: string }>()
const router = useRouter()
</script>

<template>
  <div class="bg-gray-50 h-screen">
    <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:py-16 lg:px-8 lg:flex lg:items-center lg:justify-between">
      <div>
        <h2 class="text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">
          Hi
          <span class="inline-block text-indigo-600">{{ props.name }}!</span>
        </h2>
        <p class="mt-5 text-xl text-gray-500">
          This is a dynamic route,<br>
          brought to you by Vue.
        </p>
      </div>
      <div class="mt-8 flex lg:mt-0 lg:flex-shrink-0">
        <div class="inline-flex rounded-md shadow">
          <button
            class="inline-flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700"
            @click="router.back()"
          >
            Back
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
