<template>
  <div class="home">
    <Hero></Hero>
    <Jackie></Jackie>
    <Services></Services>
    <Treatment></Treatment>
    <Pricing></Pricing>
    <FAQ></FAQ>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Hero.vue'
import Jackie from '@/components/Jackie.vue'
import Services from '@/components/Services.vue'
import Treatment from '@/components/Treatment.vue'
import Footer from '@/components/Footer.vue'
import FAQ from '@/components/FAQ.vue'
import Pricing from '@/components/Pricing.vue'
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
    Hero,
    Services,
    Jackie,
    Treatment,
    FAQ,
    Pricing,
    Footer
  }
}
</script>
