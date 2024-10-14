<template>
  <div
    class="min-h-screen bg-gradient-to-b from-[#0b1c29] to-[#0d8ac0] text-white flex justify-center items-center p-4 md:p-0"
  >
    <div
      class="max-w-5xl w-full min-h-fit h-[500px] md:h-[600px] text-start bg-gradient-to-b from-[#0b1c29] to-[#1f415e] shadow-2xl rounded-2xl flex flex-col md:flex-row "
    >
      <div class="w-full md:w-1/2 p-10 flex flex-col justify-between">
        <div>
          <div class="anton-regula">
            <div class="text-lg flex items-center gap-2">
              <h1 class="font-bold text-blue-400">HELLO</h1>
              <div class="border-b border-white w-[80%]"></div>
            </div>

            <h1 class="text-2xl mb-4">
              I'M Panuwat
              <span class="text-cyan-500 font-bold">{</span>POND
              <span class="text-cyan-500 font-bold">}</span> Petseekeaw
            </h1>
          </div>
          <p class="text-xl md:text-2xl text-blue-300 font-semibold mb-6">
            <i class="fa-regular fa-circle-dot"></i> Frontend Developer
          </p>
          <p class="text-gray-300 pl-4">
            I graduated with a Bachelor's degree in Computer Science from Khon
            Kaen University.
          </p>
        </div>

        <div class="text-center mt-6 md:mt-0">
          <button
            class="border-2 border-blue-500 text-blue-400 hover:bg-gradient-to-r from-blue-400 to-blue-600 hover:text-white/80 font-semibold py-3 px-8 rounded-lg transition-all duration-300"
          >
            เข้าสู่หน้าเว็บไซต์
          </button>
        </div>

        <div class="flex justify-center md:justify-start space-x-4 mt-6 md:mt-0">
          <nuxt-link to="https://github.com/panuwat-pnd" class="transform hover:scale-125 transition duration-300">
            <i class="fa-brands fa-github text-3xl opacity-80 hover:opacity-100"></i>
          </nuxt-link>
          <nuxt-link
            to="https://www.linkedin.com/in/panuwat-petseekeaw-950897332/"
            class="transform hover:scale-125 transition duration-300"
          >
            <i class="fa-brands fa-linkedin text-3xl opacity-80 hover:opacity-100"></i>
          </nuxt-link>
        </div>
      </div>
      <div
        class="w-full md:w-1/2 p-6 md:p-10 flex items-center justify-center overflow-hidden relative"
      >
        <img
          src="https://hips.hearstapps.com/hmg-prod/images/cat-puns-64ef515f6036a.jpg?crop=0.668xw:1.00xh;0.167xw,0&resize=1200:*"
          alt=""
          class="w-full h-full rounded-lg object-cover bg-center "
        />
        <!-- <div
          class="absolute inset-0 bg-gradient-to-t from-[#00000066] to-transparent rounded-lg"
        ></div> -->
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
// No additional JavaScript or TypeScript required for this layout
</script>

<style scoped>
/* Add custom styles if necessary */
</style>