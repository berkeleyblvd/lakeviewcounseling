<script>
  export default{
    components: {
      name: "contact"
    }
  };
</script>

<template>

<div class="relative bg-white">
  <div class="lg:absolute lg:inset-0">
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img class="h-56 w-full object-cover lg:absolute lg:h-full" src="https://images.unsplash.com/photo-1556761175-4b46a572b786?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1567&q=80" alt="">
    </div>
  </div>
  <!-- This example requires Tailwind CSS v2.0+ -->
<div class="bg-white">
  <div class="mx-auto max-w-7xl py-16 px-4 sm:px-6 lg:px-8">
    <div class="mx-auto max-w-lg md:grid md:max-w-none md:grid-cols-2 md:gap-8">
      <div>
        <h2 class="text-2xl font-bold text-gray-900 sm:text-3xl sm:tracking-tight">Office</h2>
        <div class="mt-3">
          <p class="text-lg text-gray-500">Our office is located in the Fox Bay office building in the heart of
           Whitefish Bay.</p>
        </div>
        <div class="mt-9">
          <div class="flex">
            <div class="flex-shrink-0">
              <!-- Heroicon name: outline/phone -->
              <svg class="h-6 w-6 text-gray-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
              </svg>
            </div>
            <div class="ml-3 text-base text-gray-500">
              <p>+1 (555) 123 4567</p>
              <p class="mt-1">Regular  Hours: Tuesday & Thursday 10am to 4pm</p>
              <p class="mt-1">Evening Hours: Tuesday & Thursday 5pm to 8pm</p>
              <p class="mt-1">Additional availability upon request</p>
            </div>
          </div>
          <div class="mt-6 flex">
            <div class="flex-shrink-0">
              <!-- Heroicon name: outline/envelope -->
              <svg class="h-6 w-6 text-gray-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
              </svg>
            </div>
            <div class="ml-3 text-base text-gray-500">
              <p>jackie@lakeviewcounselingllc.com</p>
            </div>
          </div>
          <div class="mt-6 flex">
            <div class="flex-shrink-0">
              <!-- Heroicon name: outline/envelope -->
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 text-gray-400">
                <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
              </svg>

            </div>
            <div class="ml-3 text-base text-gray-500">
              <p>316 E. Silver Spring Drive</p>
              <p>Suite 231</p>
              <p>Whitefish Bay, WI 53217</p>
            </div>
          </div>
        </div>
      </div>
      <div class="mt-12 sm:mt-16 md:mt-0">
        <h2 class="text-2xl font-bold text-gray-900 sm:text-3xl sm:tracking-tight">Technical Support</h2>
        <div class="mt-3">
          <p class="text-lg text-gray-500">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Magni, repellat error corporis doloribus similique, voluptatibus numquam quam, quae officiis facilis.</p>
        </div>
        <div class="mt-9">
          <div class="flex">
            <div class="flex-shrink-0">
              <!-- Heroicon name: outline/phone -->
              <svg class="h-6 w-6 text-gray-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
              </svg>
            </div>
            <div class="ml-3 text-base text-gray-500">
              <p>+1 (555) 123 4567</p>
              <p class="mt-1">Mon-Fri 8am to 6pm PST</p>
            </div>
          </div>
          <div class="mt-6 flex">
            <div class="flex-shrink-0">
              <!-- Heroicon name: outline/envelope -->
              <svg class="h-6 w-6 text-gray-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
              </svg>
            </div>
            <div class="ml-3 text-base text-gray-500">
              <p>support@example.com</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

</div>


</template>

<style scoped>

</style>