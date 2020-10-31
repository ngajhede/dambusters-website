<template lang="pug">
<div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
  <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
    <div>
      <p class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400">
        Dream Team
      </p>
    </div>
    <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
      <span class="relative inline-block">
        <svg viewBox="0 0 52 24" fill="currentColor" class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-blue-gray-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block">
          <defs>
            <pattern id="247432cb-6e6c-4bec-9766-564ed7c230dc" x="0" y="0" width=".135" height=".30">
              <circle cx="1" cy="1" r=".7"></circle>
            </pattern>
          </defs>
          <rect fill="url(#247432cb-6e6c-4bec-9766-564ed7c230dc)" width="52" height="24"></rect>
        </svg>
        <span class="relative">Welcome</span>
      </span>
      our talented team of professionals
    </h2>
    <p class="text-base text-gray-700 md:text-lg">
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem aperiam, eaque ipsa quae.
    </p>
  </div>
  <div class="grid gap-10 row-gap-8 mx-auto sm:row-gap-10 lg:max-w-screen-lg sm:grid-cols-2 lg:grid-cols-3">
    <TeamsItem v-for="member in team" :key="member.id" :name="member.name" :title="member.title" :avatar="member.avatar" />
  </div>
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import TeamsItem from './TeamsItem.vue'

export default defineComponent({
  name: 'TeamsInfo',
  components: { TeamsItem },
  data () {
    return {
      team: [{
        id: 1,
        name: 'Estevan Python',
        title: 'Junior Executive',
        avatar: 'https://robohash.org/reiciendisillumdistinctio.bmp?size=50x50&set=set1'
      }, {
        id: 2,
        name: 'Mersey Ziemens',
        title: 'Quality Control Specialist',
        avatar: 'https://robohash.org/mollitiacupiditateperspiciatis.bmp?size=50x50&set=set1'
      }, {
        id: 3,
        name: 'Marigold Martinello',
        title: 'Social Worker',
        avatar: 'https://robohash.org/etrerumexplicabo.jpg?size=50x50&set=set1'
      }, {
        id: 4,
        name: 'Boris Woodage',
        title: 'Technical Writer',
        avatar: 'https://robohash.org/veritatiscorporisillum.bmp?size=50x50&set=set1'
      }, {
        id: 5,
        name: 'Loren Beddard',
        title: 'Legal Assistant',
        avatar: 'https://robohash.org/autemconsequaturaperiam.bmp?size=50x50&set=set1'
      }, {
        id: 6,
        name: 'Faunie Sparkes',
        title: 'Nurse',
        avatar: 'https://robohash.org/natusabconsequatur.bmp?size=50x50&set=set1'
      }, {
        id: 7,
        name: 'Malinda Shorey',
        title: 'Web Designer III',
        avatar: 'https://robohash.org/explicaboestdoloribus.png?size=50x50&set=set1'
      }, {
        id: 8,
        name: 'Harv Mather',
        title: 'Geological Engineer',
        avatar: 'https://robohash.org/inreprehenderitsit.bmp?size=50x50&set=set1'
      }, {
        id: 9,
        name: 'Gabrielle Ranstead',
        title: 'Community Outreach Specialist',
        avatar: 'https://robohash.org/utpariaturad.jpg?size=50x50&set=set1'
      }, {
        id: 10,
        name: 'Bette-ann Tilt',
        title: 'Automation Specialist II',
        avatar: 'https://robohash.org/estvoluptateoptio.jpg?size=50x50&set=set1'
      }]
    }
  }
})
</script>

<style lang="stylus">
</style>
