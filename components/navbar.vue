<template >
  <div class="w-full h-20 mx-auto px-20 py-3 bg-red-600 flex flex-wrap justify-center items-center ">
      <div class="w-1/3">
        <a href="https://github.com/TanatornZ" target="_blank" class="ml-4 text-lg font-medium">Github</a>
     </div>
     <div class="w-1/3 flex justify-center items-center" @click="$router.push('/')">
        <button class="text-3xl font-medium text-white">SNEAKER</button>
     </div>
     <div class="w-1/3 flex justify-end" @click="$router.push('/Profile')">
        <button class="mr-4 text-lg font-medium ">Profile</button>

     </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>