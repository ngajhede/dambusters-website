<template lang="pug">
.nav.bg-black
  Navigation
router-view
FooterSimple
</template>

<script lang="ts">
import Navigation from '@/components/Navigation.vue'
import FooterSimple from '@/components/FooterSimple.vue'
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
  components: {
    Navigation, FooterSimple
  }
})

</script>

<style lang="stylus">
#app
  font-family 'Roboto', sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
</style>
