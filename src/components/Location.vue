<script>
  export default{
    components: {
      name: "location"
    }
  };
</script>

<template>

<!-- This example requires Tailwind CSS v2.0+ -->
<div class="bg-white">

<div class="relative bg-white">
  <div class="lg:absolute lg:inset-0">
    <div class="lg:absolute lg:inset-y-0 lg:left-0 lg:w-1/2">
      <img class="h-56 w-full object-cover lg:absolute lg:h-full" src="https://i.postimg.cc/1XtGM94j/Map.png" alt="">
    </div>
  </div>
  <div class="relative px-4 pt-12 pb-16 sm:px-6 sm:pt-16 lg:mx-auto lg:grid lg:max-w-7xl lg:grid-cols-2 lg:px-8">
    <div class="lg:col-start-2 lg:pl-8">
      <div class="mx-auto max-w-prose text-base lg:ml-auto lg:mr-0 lg:max-w-lg">
        <h2 class="font-semibold leading-6 text-indigo-600">316 E. Silver Spring Dr. Suite 231</h2>
        <h3 class="mt-2 text-3xl font-bold leading-8 tracking-tight text-gray-900 sm:text-4xl">Whitefish Bay, WI</h3>

        <div class="prose prose-indigo mt-5 text-gray-500">
          <p>Turn North onto Santa Monica Blvd. from Silver Spring Dr. and turn right into the alley just past
          Starbucks. There is a 2-hour surface parking lot and a 10-hour parking structure. There is an entrance on the North side of the building, just left of the parking garage ramp. There is also an
          entrance on the South side of the building along Silver Spring Dr., marked with a large Fox Bay Building sign
          above the door. Take the stairs or elevator to the 2nd floor and follow to the left to the end.
          Lakeview Counseling is at the end of the hall on the right, Suite 231.</p>
        </div>
        <p class="mt-8 text-lg text-gray-500">Metered Street Parking On Silver Spring Dr</p>
        <div class="prose prose-indigo mt-5 text-gray-500">
          <p>Metered parking is available on E. Silver Spring Dr. Take the stairs or elevator to the 2nd
          floor and follow to the left to the end of the hallway. Lakeview Counseling is at the end of the hall on the right,
          Suite 231.</p>
        </div>
      </div>
    </div>
  </div>
</div>


</div>



</template>

<style scoped>

</style>