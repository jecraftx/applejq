<template>
    <div class="navbar bg-headbg">
       <div class="container mx-auto">
           <div class="hidden sm:flex justify-between py-3 items-center">
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-xl hover:text-white transition-all" to="/"><i class="fab fa-apple"></i></router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/">Mac</router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/">iPad</router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/iphone">iPhone</router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/">Watch</router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/">AirPods</router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/">TV & Home</router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/">Only on Apple</router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/">Support</router-link>
               <router-link class="text-headlinks opacity-80  hover:opacity-100 text-sm hover:text-white transition-all" to="/">Where to buy</router-link>
           </div>
           <div class="flex sm:hidden justify-center py-3 items-center relative">
               <i class="burger fas fa-bars text-headlinks opacity-80  hover:opacity-100 text-xl hover:text-white transition-all"></i>
                <router-link class="text-headlinks opacity-80  hover:opacity-100 text-xl hover:text-white transition-all" to="/about"><i class="fab fa-apple"></i></router-link>
           </div>
       </div>
       <div class="nav2 sticky top-0 border-b ">
           <div class="hidden sm:flex justify-between py-3 items-center">
            <router-link class="text-neblack opacity-80  hover:opacity-100 text-xl font-semibold hover:text-black transition-all" to="/">iPhone 13 Pro</router-link>
       </div>
       <div class="flex mt-2">
            <router-link class="text-price hover:opacity-100 text-sm transition-all mr-5" to="/">Overview</router-link>
            <router-link class="text-neblack hover:opacity-100 text-sm hover:text-blue-600 transition-all mr-5" to="/">Switching to iPhone</router-link>
            <router-link class="text-neblack hover:opacity-100 text-sm hover:text-blue-600 transition-all mr-5" to="/">Tech Specs</router-link>
            <button class="text-white bg-blue-600 py-1 px-3 rounded-2xl hover:opacity-100 text-sm transition-all" to="/">Buy</button>
       </div> 
       </div>
    </div>
</template>