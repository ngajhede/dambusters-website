<template>
<header class="w-full text-gray-700 bg-black shadow-sm body-font">
  <div class="container flex flex-col items-start mx-auto md:flex-row">
    <a href="#_" class="flex items-center font-medium text-gray-900 title-font md:mb-0">
      <img class="w-auto h-20" :src="require('@/assets/images/TheDambusters.png')" />
    </a>
    <nav class="flex items-center justify-center text-base mt-6 md:ml-auto">
      <a href="#_" class="mr-5 font-medium hover:text-gray-900">HOME</a>
      <a href="#_" class="mr-5 font-medium hover:text-gray-900">TEAMS</a>
      <a href="#_" class="font-medium hover:text-gray-900">APPLY</a>
    </nav>
    <div class="items-center h-full pl-6 mt-6 ml-6 border-l border-gray-200">
      <a href="#_" class="mr-5 font-medium hover:text-gray-900">LOGIN</a>
    </div>
  </div>
</header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Navigation'
})

</script>

<style lang="stylus">
</style>
