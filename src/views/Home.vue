<template lang="pug">
HeroCulture(name="home")
.container.mx-auto
  .teams(name='teams')
    TeamPicker
  .about-us(name='about-us')
    FAQList
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HeroCulture from '@/components/HeroCulture.vue'
import Card from '@/components/Card.vue'
import TeamPicker from '@/components/TeamPicker.vue'
import FAQList from '@/components/FAQList.vue'

export default defineComponent({
  name: 'Home',
  components: {
    Card, HeroCulture, TeamPicker, FAQList
  }
})
</script>

<style lang="stylus">
body
  background-color #0a0a0a
</style>
