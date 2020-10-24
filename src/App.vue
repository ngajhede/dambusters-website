<template lang="pug">
Navigation
router-view
Footer
</template>

<script lang="ts">
import Navigation from '@/components/Navigation.vue'
import Footer from '@/components/Footer.vue'
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
  components: {
    Navigation, Footer
  }
})

</script>

<style lang="stylus">
#app
  font-family "Montserrat", sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
</style>
