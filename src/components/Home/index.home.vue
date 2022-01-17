<template>
  <div>
      <Hero />
      <br>
      <missionHomeVue />
      <trainingHomeVue />
  </div>
</template>

<script>
import Hero from './hero.home.vue'
import missionHomeVue from './mission.home.vue'
import trainingHomeVue from './training.home.vue'
trainingHomeVue

export default {
    components:{
        Hero,
        missionHomeVue,
        trainingHomeVue
    }
}
</script>

<style>

</style>