<template>
  <div class="insurance">
    <Insurance></Insurance>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Insurance from '@/components/Insurance.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'home',
  components: {
    Insurance,
    Footer
  }
}
</script>