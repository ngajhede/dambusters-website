<template>
<nav class="font-sans flex flex-col text-center sm:flex-row sm:text-left sm:justify-between py-4 px-6 bg-black shadow sm:items-baseline w-full">
  <div class="mb-2 sm:mb-0">
    <a href="/" class="text-2xl no-underline text-white">The Dambusters</a>
  </div>
  <div>
    <a href="/#home" class="text-lg no-underline text-gray-700 hover:text-red-600 ml-2">Home</a>
    <a href="/#teams" class="text-lg no-underline text-gray-700 hover:text-red-600 ml-2">Teams</a>
    <a href="/#apply" class="text-lg no-underline text-gray-700 hover:text-red-600 ml-2">Apply</a>
    <a href="/#about" class="text-lg no-underline text-gray-700 hover:text-red-600 ml-2">About</a>
  </div>
</nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Navigation'
})

</script>
