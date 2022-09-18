<script>
  export default{
    components: {
      name: "footer"
    }
  };
</script>

<template>

<!-- This example requires Tailwind CSS v2.0+ -->
<div class="bg-white">
  <div class="mx-auto max-w-7xl py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
    <div class="text-center">
      <p class="mt-4 text-sm">
        <router-link to="/" class="font-medium text-blue-500"> Click here to return to home page </router-link>
      </p>
      <br>
      <br>
      <p class="mt-1 text-4xl font-bold tracking-tight text-gray-900 sm:text-5xl lg:text-6xl">Why I don't participate as an in network
provider for insurance plans</p><br>
      <p class="mx-auto mt-5 max-w-xl text-xl text-gray-500">
        There was a lot of thought that went into making this decision.
        It is my desire to protect your confidentiality so your diagnosis does not remain a permanent part of your medical records.
        Insurance companies can also require records reviews and obtain my private session notes and given the sensitive topics discussed
        it is my desire to protect your confidentiality.
      </p>
      <p class="mx-auto mt-5 max-w-xl text-xl text-gray-500">
        Furthermore, insurance companies can dictate the length and frequency of our sessions. This can add unnecessary pressure
        and constraints that may hinder your recovery. I want you to be in charge of your therapy, not a third party.
      </p>
    </div>
  </div>
</div>


</template>

<style scoped>

</style>