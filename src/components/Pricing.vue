<script>
  export default{
    components: {
      name: "footer"
    }
  };
</script>

<template>

<!-- This example requires Tailwind CSS v2.0+ -->
<div class="bg-gray-100">
  <div class="pt-12 sm:pt-16 lg:pt-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center">
        <h2 class="text-3xl tracking-tight font-bold text-gray-900 sm:text-4xl lg:text-5xl">Payment Rates</h2>
        <p class="mt-4 text-xl text-gray-600"></p>
      </div>
    </div>
  </div>
  <div class="mt-8 bg-white pb-16 sm:mt-12 sm:pb-20 lg:pb-28">
    <div class="relative">
      <div class="absolute inset-0 h-1/2 bg-gray-100"></div>
      <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="max-w-lg mx-auto rounded-lg shadow-lg overflow-hidden lg:max-w-none lg:flex">
          <div class="flex-1 bg-white px-6 py-8 lg:p-12">
            <h3 class="text-2xl font-bold text-gray-900 sm:text-3xl sm:tracking-tight">Private Pay</h3>
            <p class="mt-6 text-base text-gray-500">I have choosen to no participate as in an in network provider for any insurance
            plans. I accept credit, debit, and HSA/FSA. Clients will be billed after each session with a provided card on file.</p>
            <p class="mt-4 text-md ">
              <router-link to="/insurance" class="font-medium text-gray-500 underline"> Learn why I don't participate as an in network provider for insurance plans </router-link>
            </p>
            <div class="mt-8">
              <div class="flex items-center">
                <h4 class="flex-shrink-0 pr-4 bg-white text-base font-semibold text-indigo-600">Session details</h4>
                <div class="flex-1 border-t-2 border-gray-200"></div>
              </div>
              <ul role="list" class="mt-8 space-y-5 lg:space-y-0 lg:grid lg:grid-cols-2 lg:gap-x-8 lg:gap-y-5">
                <li class="flex items-start lg:col-span-1">
                  <div class="flex-shrink-0">
                    <!-- Heroicon name: mini/check-circle -->
                    <svg class="h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <p class="ml-3 text-md text-gray-700">50-minute sessions</p>
                </li>

                <li class="flex items-start lg:col-span-1">
                  <div class="flex-shrink-0">
                    <!-- Heroicon name: mini/check-circle -->
                    <svg class="h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <p class="ml-3 text-md text-gray-700">Virtual or in-person</p>
                </li>

                <li class="flex items-start lg:col-span-1">
                  <div class="flex-shrink-0">
                    <!-- Heroicon name: mini/check-circle -->
                    <svg class="h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <p class="ml-3 text-md text-gray-700">Personalized approach</p>
                </li>

                <li class="flex items-start lg:col-span-1">
                  <div class="flex-shrink-0">
                    <!-- Heroicon name: mini/check-circle -->
                    <svg class="h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <p class="ml-3 text-md text-gray-700">Collaboratively created treatment goals</p>
                </li>
              </ul>
            </div>
          </div>
          <div class="py-8 px-6 text-left bg-gray-50 lg:flex-shrink-0 lg:flex lg:flex-col lg:justify-left lg:p-12">

            <div class="mt-4 flex items-left justify-left text-5xl tracking-tight font-bold text-gray-900">
              <span> $135 </span>
              <span class="ml-3 text-xl font-medium text-gray-500 tracking-normal"> initial assessment </span>
            </div>
            <div class="mt-4 flex items-left justify-left text-5xl tracking-tight font-bold text-gray-900">
              <span> $120 </span>
              <span class="ml-3 text-xl font-medium text-gray-500 tracking-normal"> per session </span>
            </div>
            <div class="mt-6">
              <div class="rounded-md shadow">
                <a href="mailto:jackie@lakeviewcounselingllc.com" class="flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-white bg-gray-800 hover:bg-gray-900"> Contact Me </a>
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

