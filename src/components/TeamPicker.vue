<template>
<div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20 mt-5">
  <div class="grid gap-10 mx-auto sm:grid-cols-2 lg:grid-cols-4 lg:max-w-screen-lg">
    <div>
      <img class="object-cover w-24 h-24 rounded-full mx-auto" :src="require('@/assets/images/classes/Pandaren_Crest.png')" alt="Raid team" />
      <div class="flex flex-col justify-center mt-2">
        <p class="text-2xl font-bold mx-auto text-white">Virnaal</p>
        <p class="mb-4 text-base mx-auto text-gray-500 mx-auto">Heroic</p>
        <p class="text-sm tracking-wide mx-auto text-gray-500 mx-auto">
          Pommy ipsum bent as a nine bob note naff off biscuits nowt, a cuppa unhand me sir hadn't done it in donkey's years sod's law.
        </p>
      </div>
    </div>
    <div>
      <img class="object-cover w-24 h-24 rounded-full mx-auto" :src="require('@/assets/images/classes/Warrior_Crest.png')" alt="Raid team" />
      <div class="flex flex-col justify-center mt-2">
        <p class="text-2xl font-bold mx-auto text-white">Ironwall</p>
        <p class="mb-4 text-base mx-auto text-gray-500 mx-auto">Mythic</p>
        <p class="text-sm tracking-wide mx-auto text-gray-500">
          Secondary fermentation degrees plato units of bitterness, cask conditioned ale ibu real ale pint glass craft beer. krausen goblet grainy ibu.
        </p>
      </div>
    </div>
    <div>
      <img class="object-cover w-24 h-24 rounded-full mx-auto" :src="require('@/assets/images/classes/Druid_Crest.png')" alt="Raid team" />
      <div class="flex flex-col justify-center mt-2">
        <p class="text-2xl font-bold mx-auto text-white">Wildwood</p>
        <p class="mb-4 text-base mx-auto text-gray-500 mx-auto">Mythic</p>
        <p class="text-sm tracking-wide mx-auto text-gray-500">
          I just closed my eyes and in a nanosecond I cured myself from this ridiculous model of disease, addiction and obsession.
        </p>
      </div>
    </div>
    <div>
      <img class="object-cover w-24 h-24 rounded-full mx-auto" :src="require('@/assets/images/classes/Shaman_Crest.png')" alt="Raid team" />
      <div class="flex flex-col justify-center mt-2">
        <p class="text-2xl font-bold mx-auto text-white">Stonewrought</p>
        <p class="mb-4 text-base mx-auto text-gray-500 mx-auto">Mythic</p>
        <p class="text-sm tracking-wide mx-auto text-gray-500">
          Est Schlitz shoreditch fashion axe. Messenger bag cupidatat Williamsburg sustainable aliqua, umami shabby chic artisan duis pickled.
        </p>
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

<style lang="stylus">
.team-picker
  background-color #141617

</style>
