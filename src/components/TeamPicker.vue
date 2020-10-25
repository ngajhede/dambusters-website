<template>
<div class="text-center transform scale-75">
  <div class="xl:p-18 xl:m-auto">
      <div class="grid xl:grid-cols-3">
          <div class="z-10 pb-20 mt-20 bg-white border-2 rounded-lg shadow-xl xl:p-20 xl:ml-1 hover:shadow-2xl">
              <div class="w-2/6 p-4 m-auto mt-12 border-4 border-red-600 rounded-full xl:mt-0">
                  <img :src="require('@/assets/images/WoW_icon.svg')"/>
              </div>
              <h3 class="mt-8 text-4xl font-bold">Wildwood</h3>
              <h3 class="mt-6 mb-6 text-4xl font-semibold text-purple-400">10/12 Mythic</h3>
              <ul class="space-y-6 text-xl">
                  <li>30-Day Trial</li>
                  <li>500GB Bandwidth</li>
                  <li>200H DiskSpaces&#8482;</li>
                  <li>5 Course Submissions</li>
              </ul>
              <button
                  class="w-5/6 h-16 mt-12 text-xl font-semibold text-white bg-red-400 rounded xl:mb-6">Apply</button>
          </div>
          <div
              class="z-10 pb-20 mt-20 transform scale-110 bg-white border-2 rounded-lg shadow-xl xl:p-20 xl:ml-1 hover:shadow-2xl">
              <div class="w-2/6 p-4 m-auto mt-12 border-4 border-red-600 rounded-full xl:mt-0">
                  <img :src="require('@/assets/images/WoW_icon.svg')"/>
              </div>
              <h3 class="mt-8 text-3xl font-bold">Ironwall</h3>
              <h3 class="mt-6 mb-6 text-4xl font-semibold text-purple-400">11/12 Mythic</h3>
              <ul class="space-y-6 text-xl">
                  <li>Wed, Thur, Sundays</li>
                  <li>19:45-23:00 Realm Time</li>
                  <li>Loot Council</li>
              </ul>
              <button class="w-5/6 h-16 mt-12 text-xl font-semibold text-white bg-red-400 rounded xl:mb-6">Apply</button>
          </div>
          <div class="pb-20 mt-20 bg-white border-2 rounded-lg shadow-xl xl:p-20 xl:ml-1 hover:shadow-2xl">
              <div class="w-2/6 p-4 m-auto mt-12 border-4 border-red-600 rounded-full xl:mt-0">
                  <img :src="require('@/assets/images/WoW_icon.svg')"/>
              </div>
              <h3 class="mt-8 text-3xl font-bold">Stonewrought</h3>
              <h3 class="mt-6 mb-6 text-4xl font-semibold text-purple-400">10/12 Mythic</h3>
              <ul class="space-y-6 text-xl">
                  <li>Incl. Medium package</li>
                  <li>Unlimited Bandwidth</li>
                  <li>2.4TB DiskSpaces&#8482;</li>
                  <li>Unlimited Submissions</li>
              </ul>
              <button
                  class="w-5/6 h-16 mt-12 text-xl font-semibold text-white bg-red-400 rounded xl:mb-6">Order</button>
          </div>
      </div>
  </div>
</div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'TeamPicker',
  components: {

  }
})
</script>
