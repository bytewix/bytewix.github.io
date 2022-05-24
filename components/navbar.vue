<template>
  <div>
      <!-- Navbar Start Here -->
        <div class="flex justify-between items-center mx-16 my-10 bg-white py-2 relative">
            <div>
                <!-- <h1 class="text-2xl font-bold text-gray-600 tracking-wider">Byte<span class="text-primary">Wix.</span></h1> -->
                <a href="#heroPage">
                    <img class="w-52" src="../assets/images/logo_in.jpeg" alt="">
                </a>
            </div>

            <div class="hidden lg:flex items-center gap-x-8 z-30">
            
                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="#service">Services</a>
                
                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="#whyus">Why Us</a>           
            
                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="#leadership">Leadership</a>

                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="">Our Products</a>
            
                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="#projects">Projects</a>
            
                    <a class="font-semibold text-primary bg-gray-200 px-3 py-3 transform hover:scale-110 rounded-md shadow-md" href="#contucUs">Contact Us</a>              
            </div>


            <div class="lg:hidden flex items-center gap-x-8">
                <div>
                    <svg @click="menuToggle" xmlns="http://www.w3.org/2000/svg" class="text-gray-600 h-7 w-7" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </div>
            </div>
        </div>
        <!-- Navbar End Here -->
        <div class="w-full">
            <div v-if="menus" class="absolute flex flex-col w-full items-start bg-gray-200 py-4 px-16 gap-x-8 z-30">
        
                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="#service">Services</a>
                
                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="#whyus">Why Us</a>           
            
                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="#leadership">Leadership</a>

                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="">Our Products</a>
            
                    <a class="hover:bg-gray-200 duration-500 transform hover:scale-110  hover:shadow-md font-semibold px-3 py-3 rounded-md text-gray-600" href="#projects">Projects</a>
            
                    <a class="font-semibold text-primary bg-gray-200 px-3 py-3 transform hover:scale-110 rounded-md shadow-md" href="#contucUs">Contact Us</a>              
            </div>
        </div>

  </div>
</template>

<script>
export default {
    name:'navbar',
    data(){
        return{
            menus:false
        }

    },
    methods:{
        menuToggle(){
            this.menus = !this.menus
        }
    }

}
</script>

<style>

</style>