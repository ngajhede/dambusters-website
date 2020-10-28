<template lang="pug">
.teams-info.col-span-2.border-r-2.border-white
  img(:src="require('@/assets/images/teams-background.jpg')").w-full.rounded-tl-lg
  .text-white.m-3
    span Contains all the sick team info
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'TeamsInfo'
})
</script>

<style lang="stylus">
</style>
