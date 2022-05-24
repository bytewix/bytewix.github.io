<template>
  <div id="leadership" class="h-96">
    <div class="relative" style="background-image: url('../assets/images/bgClint.png');">
        <img class="hidden lg:block absolute mt-16 -top-96 z-0" src="../assets/images/bgClint.png" alt="">
        <div class="mx-16 mt-6">
            <h1 class="text-2xl font-bold text-gray-700 uppercase dark:text-white lg:text-4xl">What Our <span class="text-primary">Client Say</span></h1>
            <p class="mt-2 mr-10 text-gray-500 text-sm font-semibold dark:text-gray-400">Bytes are a worldwide based Creative Agency. We specialize <br> in sofware development and Use Experience Design.</p>
        </div>
        <div class="mx-16">
            <user v-for="index in 1" :key="index"></user>
        </div>
    </div> 

  </div>
</template>

<script>
import user from '../components/user_img.vue'
export default {
    components:{
        user
    }

}
</script>

<style>

</style>