<template lang="pug">
.teams.flex.min-h-screen.grid.grid-cols-3.container.mx-auto.mt-5.mb-5.shadow-2xl.rounded
  TeamsInfo
  TeamsList
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import TeamsInfo from '@/components/Teams/TeamsInfo.vue'
import TeamsList from '@/components/Teams/TeamsList.vue'

export default defineComponent({
  name: 'Teams',
  components: {
    TeamsInfo, TeamsList
  }
})
</script>

<style lang="stylus">
.teams
  background-color #141617
</style>
