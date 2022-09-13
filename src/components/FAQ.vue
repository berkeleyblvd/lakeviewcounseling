<script>
  export default{
    components: {
      name: "faq"
    }
  };
</script>

<template>

<!-- This example requires Tailwind CSS v2.0+ -->
<div class="bg-gray-200">
  <div class="max-w-7xl mx-auto py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
    <div class="lg:max-w-2xl lg:mx-auto lg:text-center">
      <h2 class="text-3xl font-bold tracking-tight text-gray sm:text-4xl">Frequently asked questions</h2>
      <p class="mt-4 text-gray-600">If you still have questions, please feel free to contact me directly.</p>
    </div>
    <div class="mt-20">
      <dl class="space-y-10 lg:space-y-0 lg:grid lg:grid-cols-2 lg:gap-x-8 lg:gap-y-10">
        <div>
          <dt class="font-semibold text-gray">How long will I be in therapy?</dt>
          <dd class="mt-3 text-gray-600">This depends on you and your goals. Typically, the average length is 8-12 sessions, but
          sometimes I see clients for fewer sessions or for years.</dd>
        </div>

        <div>
          <dt class="font-semibold text-gray">Do you provide in person or virtual sessions?</dt>
          <dd class="mt-3 text-gray-600">Both. If you prefer or need to meet virtually, I will send a link prior to the session.</dd>
        </div>

        <div>
          <dt class="font-semibold text-gray">Can I schedule more than one session a week?</dt>
          <dd class="mt-3 text-gray-600">Yes. Your treatment plan is dictated by you and not insurance companies so you have flexibility in scheduling. Therefore, you can do two sessions a week, two hour sessions, every other week, etc.</dd>
        </div>
      </dl>
    </div>
  </div>
</div>


</template>

<style scoped>

</style>