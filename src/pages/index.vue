<script setup lang="ts">
const name = ref('')

const router = useRouter()
const go = () => {
  if (name.value)
    router.push(`/hi/${encodeURIComponent(name.value)}`)
}
</script>

<template>
  <div class="bg-gray-50 h-screen">
    <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:py-16 lg:px-8 lg:flex lg:items-center lg:justify-between">
      <div>
        <h2 class="text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">
          Vitesse Lite
          <span class="inline-block text-indigo-600">Tailwind</span>
        </h2>
        <p class="mt-5 text-xl text-gray-500">
          Opinionated Vite Starter Template with Tailwind.<br>
          Based on <a rel="noreferrer" class="underline decoration-indigo-500 underline-offset-2" href="https://github.com/antfu/vitesse-lite" target="_blank">
            Vitesse Lite by Anthony Fu.
          </a>
        </p>
      </div>
      <div class="mt-8 flex lg:mt-0 lg:flex-shrink-0">
        <div class="flex rounded-md shadow-sm">
          <input
            id="input"
            v-model="name"
            autocomplete="false" type="text" name="company-website"
            class="focus:ring-indigo-500 py-3 focus:border-indigo-500 flex-1 block w-full rounded-md rounded-r-md border-gray-300 mr-2" placeholder="What's your name?" @keydown.enter="go"
          >
        </div>
        <div class="inline-flex rounded-md shadow">
          <button
            class="inline-flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700"
            :disabled="!name"
            @click="go"
          >
            Go
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
