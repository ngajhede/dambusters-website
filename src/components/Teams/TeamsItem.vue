<template>
  <div class="flex">
    <img class="object-cover w-20 h-20 mr-4 rounded-full shadow bg-gray-200" :src="avatar" alt="Person" />
    <div class="flex flex-col justify-center">
      <p class="text-lg font-bold text-gray-300">{{ name }}</p>
      <p class="text-sm text-gray-600">{{ title }}</p>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'TeamsItem',
  props: {
    name: {
      type: String,
      default: 'Name'
    },
    title: {
      type: String,
      default: 'Title'
    },
    avatar: {
      type: String,
      default: 'https://3znvnpy5ek52a26m01me9p1t-wpengine.netdna-ssl.com/wp-content/uploads/2017/07/noimage_person.png'
    }
  }
})
</script>
