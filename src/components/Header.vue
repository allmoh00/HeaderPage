<template>
  <main class="pt-2 pb-4 bg-cover bg-center" style="background-image: url('./assets/tz 1.png')">
    <div class="flex justify-between items-center mb-4 ">
      <!-- Left-aligned logo with specific size -->
      <img src="../assets/tcdc.png" alt="ushirika" class="w-18 h-20 opacity-80"> 
      
      <div class="text-center mb-6">
        <h1 class="text-lg font-semibold text-cyan-500">THE UNITED REPUBLIC OF TANZANIA</h1>
        <h3 class="text-lg font-bold text-cyan-500">eGOVERNMENT RESEARCH, INNOVATION, AND DEVELOPMENT CENTER</h3>
      </div>

      <!-- Right-aligned logo with specific size -->
      <img src="../assets/egalogo.png" alt="eGA Logo" class="w-18 h-20 opacity-80"> 
    </div>

    <!-- Heading Section -->
   
    <div class="bg-alphachain  bg-cyan-700 flex justify-between items-center px-20 py-5">
      <ul class="flex justify-end">
        <a aria-current="page" href="/" class="router-link-active target="_blank rel="router-link-exact-active">
          <button class="rounded-md font-ubuntu text-base font-bold w-28 h-10 mx-2 hover:bg-alphachain " style="color: rgb(255, 255, 255); background-color: rgb(255, 161, 64);"> 
            Home
           </button>
          </a>
          <a href="https://ubunifu.ega.go.tz//">
            <button class="rounded-md font-ubuntu text-base font-bold w-28 h-10 mx-2 hover:bg-alphachain" style="color: rgb(255, 255, 255); background-color: transparent;"> 
              contact 
            </button>
          </a>
          <a href="https://www.ega.go.tz/">
            <button class="rounded-md font-ubuntu text-base font-bold w-28 h-10 mx-2 hover:bg-alphachain" style="color: rgb(255, 255, 255); background-color: transparent;"> 
              About
             </button>
            </a>
            <a href="https://alphachain.all.co.tz/dapps">
              <button class="rounded-md font-ubuntu text-base font-bold w-28 h-10 mx-2 hover:bg-alphachain" style="color: rgb(255, 255, 255); background-color: transparent;"> 
                Wallet
               </button>
              </a>
            </ul>
    </div>
  </main>

  <div class="app-header bg-gray-800 text-white p-4">
    <div class="flex justify-between items-center">
      <!-- Left side content if any, otherwise empty -->
      
      
      <!-- Navigation Section aligned to the right -->
      <!-- <nav class="navigation">
        <ul class="flex space-x-4 justify-end">
          <li><a href="/Home" class="hover:underline ">Home</a></li>
          <li><a href="/about" class="hover:underline ">About</a></li>
          <li><a href="/contact" class="hover:underline ">Contact</a></li>
        </ul>
      </nav> -->
      
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue';

// Example of using ref (not needed for this static component)
const example = ref('Header Example');
</script>

<style scoped>
.app-header {
  /* Scoped styles for header */
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 794px;
  flex-shrink: 0;
  background: url('../assets/tz 1.png'), lightgray -620px -0.031px / 132.275% 100.008% no-repeat;
}

.logo img {
  height: 10px;
  width: 10px;
}
bg-alphachain {
  background-color: rgba(16, 64, 80, 0.87);
}

.navigation ul {
  list-style-type: none;
}

.navigation a {
  color: white;
  text-decoration: none;
}

.navigation a:hover {
  text-decoration: underline;
}

</style>
