<template>
  <main>
    <Jumbotron />
    <SectionCloud />
    <SectionSpeciality />
    <SectionStats />
    <SectionClient />
    <SectionTalk />
  </main>
</template>

<script>

import Jumbotron from './Jumbotron.vue'
import SectionCloud from './Section_Cloud.vue'
import SectionSpeciality from './Section_Speciality.vue'
import SectionStats from './Section_Stats.vue'
import SectionClient from './Section_Client.vue'
import SectionTalk from './Section_Talk.vue'


export default {
  name: 'Main',
  components: {
    Jumbotron,
    SectionCloud,
    SectionSpeciality,
    SectionStats,
    SectionClient,
    SectionTalk
  }
}
</script>

<style lang="scss" scoped>
  main{
    width: 100%;
  }
</style>