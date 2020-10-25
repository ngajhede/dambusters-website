<template lang="pug">
HeroCulture
.container.mx-auto
  .blog-posts
    Card.inline-block.mx-3
    Card.inline-block.mx-3
    Card.inline-block.mx-3
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HeroCulture from '@/components/HeroCulture.vue'
import Card from '@/components/Card.vue'

export default defineComponent({
  name: 'Home',
  components: {
    Card, HeroCulture
  }
})
</script>
