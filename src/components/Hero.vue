<script>
  export default{
    components: {
      name: "hero"
    }
  };
</script>

<template>

<div class="relative flex flex-col items-center justify-center min-h-screen bg-cover min-w-screen"
    style="background-image:url('https://images.unsplash.com/photo-1476673160081-cf065607f449?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2944&q=80')">
    <div class="absolute inset-0 w-full h-full bg-black bg-opacity-25"></div>


    <div class="flex max-w-6xl mx-auto">
        <div class="container relative flex flex-col w-3/4 px-10 pb-1 pr-12 text-2xl text-white">
            <img class="object-cover object-center pt-5 pb-10" src="https://i.postimg.cc/7LyCsxfZ/LVC-logo-color.png" alt="Jackie Wichert" width="100" height="205">
            <h2 class="relative z-20  text-7xl font-extrabold leading-tight text-white">Welcome to<br>Lakeview Counseling
            </h2>
            <p class="relative z-20 block mt-4 text-xl">Located in Whitefish Bay, WI.<br>
             I
            started Lakeview Counseling to provide
            a warm, welcoming, and non-judgemental space that allows one to quickly
            feel comfortable and safe to process and discuss difficult
            topics.</p>
            <div class="flex mt-4">
              <a href="mailto:jackiewichert@lakeviewcounselingllc.com"
                class="flex items-center self-start justify-center px-5 py-3 mt-5 ml-5 text-base font-medium leading-tight text-indigo-500 transition duration-150 ease-in-out bg-gray-200 border-transparent rounded-lg shadow hover:bg-white focus:outline-none focus:border-gray-100 focus:shadow-outline-gray md:py-4 md:text-lg md:px-8">
                Contact Me</a>
            </div>
        </div>
    </div>
</div>

</template>

<style scoped>

</style>