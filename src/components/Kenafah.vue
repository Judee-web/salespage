<template>
  <div class="pt-56 md:pt-96 pb-40 flex flex-col lg:flex-row justify-between items-center container mx-auto">

      <div class="px-7 md:px-0 md:w-[450px]">

          <div class="flex items-center mb-5">
          <div class="w-[45px] border border-[#FC881D]"></div>
          <p class="font-title font-semibold text-[#FC881D] ml-3">What you'll be getting in this free masterclass</p>
          </div>

          <p class="text-3xl font-title font-bold">Click the get access button to see if you qualify for the free gift</p>
          <p class="font-title text-base py-8"></p>
          
          <button class="py-4 px-6 bg-[#0D0E25] rounded-full text-white font-dmsans flex items-center shadow-lg hover:bg-[#212238] transition-all" v-on:click.native='btnClick' >Get Access Now <img src="/arrow.png" class="ml-3" ></button>
      </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:mt-0 mt-28">

        <div class="w-[290px] bg-[#0D0E25] text-white rounded-lg p-9">
            <div class="flex items-center">
                <p class="font-title font-semibold ml-5">You'll get access to my</p>
            </div>
            <p class="font-title mt-7">
               My years of experience summerized for you
            </p>
        </div>

        <div class="w-[290px] rounded-lg p-9">
            <div class="flex items-center">
                <p class="font-title font-semibold ml-5">Also</p>
            </div>
            <p class="font-title mt-7">
               Free ebook designed for you worth #5000 naira for FREE

            </p>
        </div>

                <div class="w-[290px] rounded-lg p-9">
            <div class="flex items-center">
                <p class="font-title font-semibold ml-5">You'll also get</p>
            </div>
            <p class="font-title mt-7">
                My step to step guide on how you can do same for yourself
            </p>
        </div>

            <div class="w-[290px] border-t border-l p-9">
            <div class="flex items-center">
                <p class="font-title font-semibold ml-5">Lastly</p>
            </div>
            <p class="font-title mt-7">
             you'll get access to my community of students
            </p>
        </div>


    </div>
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
