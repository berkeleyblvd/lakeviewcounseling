<template>
  <div class="location">
    <Location></Location>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Location from '@/components/Location.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'home',
  components: {
    Location,
    Footer
  }
}
</script>