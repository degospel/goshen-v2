<template>
  <div>
    <community-hero/>
    <join-us/>
    <future/>
    <community-partners/>
  </div>
</template>

<script>
import communityHero from '~/components/Community/community-hero.vue'
import CommunityPartners from '~/components/Community/community-partners.vue'
import Future from '~/components/Community/future.vue'
import JoinUs from '~/components/Community/join-us.vue'
export default {
  components: {
    communityHero,
    JoinUs,
    Future,
    CommunityPartners,
  },

}
</script>

<style>

</style>
