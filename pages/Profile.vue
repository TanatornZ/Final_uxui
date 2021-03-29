<template>
  <div>
      <center class="mt-10 ">
      <img class="h-52 w-52 rounded-full border-4 shadow-2xl" :src="users.image" alt="">
      <div class="text-2xl mt-5">id : {{users.username}}</div>
      <div class="text-2xl mt-3"> {{users.firstname}} {{users.lastname}} </div>
      <div class="text-xl mt-3" >Age : {{users.age}}</div>
      </center>
  </div>
</template>

<script>
import user from "@/static/user.json"
export default {
  data:() => {
    return( {
      users:user
    })
  }

}
</script>

<style>

</style>