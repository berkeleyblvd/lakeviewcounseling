<script>
  export default{
    components: {
      name: "footer"
    }
  };
</script>

<template>

<!-- This example requires Tailwind CSS v2.0+ -->
<footer class="bg-gray-900">
  <div class="mx-auto max-w-7xl overflow-hidden py-12 px-4 sm:px-6 lg:px-8">
    <nav class="-mx-5 -my-2 flex flex-wrap justify-center" aria-label="Footer">
      <div class="px-5 py-2">
        <router-link to="/" class="text-base text-gray-400 hover:text-gray-200">Home</router-link>
      </div>

      <div class="px-5 py-2">
        <router-link to="/insurance" class="text-base text-gray-400 hover:text-gray-200">Insurance</router-link>
      </div>

      <div class="px-5 py-2">
        <router-link to="/location" class="text-base text-gray-400 hover:text-gray-200">Parking & Directions</router-link>
      </div>
      <br>
    </nav>
    <p class="mt-8 text-center text-base text-gray-400">&copy; 2022 Lakeview Counseling, LLC. All rights reserved. Made in Whitefish Bay, WI with ❤️</p>
  </div>
</footer>


</template>

<style scoped>

</style>