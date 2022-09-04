<template>
  <div class="insurance">
    <Insurance></Insurance>
  </div>
</template>

<script>
// @ is an alias to /src
import Insurance from '@/components/Insurance.vue'

export default {
  name: 'Home',
  components: {
    Insurance
  }
}
</script>