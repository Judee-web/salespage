<template>
  <div class="py-[80px] relative">
    <img src="/socialmedia.png" class="absolute object-cover object-center w-[70%] left-0 right-0 bottom-0 top-0 m-auto -z-10 md:block hidden" alt="">
      <p class="font-title text-center text-[#FC881D] text-base md:text-lg">Glad You Made It</p>
    <p class="font-title font-normal text-white text-center mx-auto mt-2 md:mt-5 text-3xl md:text-5xl md:w-[680px] lg:text-6xl lg:w-[790px] px-3 md:px-0">Don't Miss This Lifetime Opportunity! Make Sure You Read All The Details Here To The Very End!</p>
    <p class="text-center font-title font-normal text-white md:w-[600px] mx-auto my-10 text-base md:text-lg px-4 md:px-0">Click the get Started Button to RESERVE YOUR SPACE NOW!</p>
    
    <div class="flex md:flex-row flex-col items-center justify-center">
        <button class="py-3 px-5 w-max text-white font-dmsans rounded-full bg-[#FC881D] shadow-xl shadow-[#d499622f] hover:bg-[#ff912a] transition-all" v-on:click.native='btnClick'>Get Started</button>
        <button class="py-3 px-5 w-max text-white font-dmsans ml-0 md:ml-6 flex items-center mt-4 md:mt-0"><img src="/play-circle.png" alt="play" class="mr-3" v-on:click.native='btn-Click'>Watch Video</button>
    </div>
            <img  src="/count.gif"/>

  </div>
</template>

<script>
export default {
  methods : {
    btnClick: function(event) {
      window.open("https://wa.link/fsg4ik");
    }
  }
}
</script>
