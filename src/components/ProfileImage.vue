<template>
    <!-- <img src="IMAGE_URL" class="profile" alt="profile"/> -->
   <img :src="image" class="profile" alt="user.name" /> 
</template>


<script>   
export default {
  props:["image"],
};
</script>


<style scoped>

</style>