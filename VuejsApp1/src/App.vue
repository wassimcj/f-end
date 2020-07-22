<template>
    <div id="app" class="bg-purple-100 w-screen h-screen p-20">
    
  
  <div id="nav0">
      
        <ul class="flex">
<li class="mr-6">
    <a class="text-black hover:text-blue-800 pl-48 pb-20" href="#">Personal</a>
  </li>
  <li class="mr-6">
    <a class="text-gray-500 hover:text-blue-400 pl-16 pb-20" href="#">Business</a>
  </li>
 <li class="mr-6">
    <a class="text-gray-500 hover:text-blue-800 pl-32 pb-20" href="#">About</a>
  </li>
  <li class="mr-6">
    <a class="text-gray-500 hover:text-blue-800 pl-10 pb-20" href="#">Pricing</a>
  </li>
  <li class="mr-6">
    <a class="text-gray-500 hover:text-blue-800 pl-10 pb-20" href="#">FAQ</a>
  </li>
  <li class="mr-6">
    <a class="text-gray-500 hover:text-blue-800 pl-10 pb-20" href="#">Contact Us</a>
  </li>
  <li class="mr-6">
    <a class="text-gray-500 hover:text-blue-800 pl-40 pb-20" href="#">Login</a>
  </li>
  
    <li class="mr-6">
    <a class="bg-gray-300 hover:bg-gray-400 text-gray-500 py-4 px-8 rounded-full" href="#">Join now</a>
  </li>
  </ul>  
    </div>  
    <div id="nav1"> 
<lo class="mr-6">
    <a class="text-black text-6xl pt-64" ><br>Just drive.<br> We'll do the rest.</a>
  </lo> 
  <lo class="mr-6">
    <a class="text-gray-600 " ><br>All-inclusive, usage-based car subscriptions.</a>
  </lo> 
  <br>
  <lo class="mr-6">
    <input class="placeholder-gray-500 mt-12 placeholder-opacity-80 bg-purple-100" placeholder="Phone number..." />
    <button class="bg-purple-900 hover:bg-purple-800 text-white py-4 px-8 rounded-full"> Get started </button>

    <div class="absolute inset-y-3/4 bg-right-top   ">
    <img class="relative h-64 " :src="require('@/assets/drive.jpg')" >

    </div>  
     </lo> 
   </div> 

  <div>
    
    
    </div>
        


    


    <router-view/> 
    
    </div>
    
</template>

<script>
    import home from './components/Home.vue';

    export default {
     
    
    };
</script>

<style lang="scss"> 
</style>

