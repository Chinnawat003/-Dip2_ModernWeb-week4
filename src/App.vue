<template>
  
  <div class="text-lg bg-red-500 text-white  flex items-center p-4 shadow">
    <router-link to="/" class="flex items-center h-10 px-4 ">Home</router-link> |
    <router-link to="/about" class="flex items-center  h-10 px-4 ">About</router-link> |
    <router-link to="/addpost" class="flex items-center  h-10 px-4 ">Addpost</router-link>
  </div>

  <RouterView />
</template>

<script>
  export default{
    name:"Vue3-Blog"
  }
</script>