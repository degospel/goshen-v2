<template>
  <div>
    <partner-hero/>
    <tribe/>
    <community/>
    <upsell-courses/>
  </div>
</template>

<script>
import Community from '~/components/Partner/community.vue'
import partnerHero from '~/components/Partner/partner-hero.vue'
import tribe from '~/components/Partner/tribe.vue'
import UpsellCourses from '~/components/Partner/upsell-courses.vue'
export default {
  components: {
    partnerHero,
    tribe,
    Community,
    UpsellCourses
  }
}
</script>

<style>

</style>
