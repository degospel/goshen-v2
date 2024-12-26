<template>
  <div>
    <Hero/>
    <Heroimg/>
    <bridge-section/>
    <testimonial/>
    <grow-web-3/>
    <faqs-section/>
    <newsletter/>
  </div>
</template>

<script>
import Hero from "~/components/Home/hero-section.vue"
import Heroimg from "~/components/Home/hero-img.vue"
import BridgeSection from '~/components/Home/bridge-section.vue'
import Testimonial from '~/components/Home/testimonial.vue'
import GrowWeb3 from '~/components/Home/grow-web3.vue'
import FaqsSection from '~/components/Home/faqs-section.vue'
import Newsletter from '~/components/Home/newsletter.vue'
export default {
  components: {
    Hero,
    Heroimg,
    BridgeSection,
    Testimonial,
    GrowWeb3,
    FaqsSection,
    Newsletter
  }
}
</script>
