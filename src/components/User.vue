<template>
    
     
        <span class="user">
          <span class="name">{{usuario.name}}</span>
          <span class="handle">{{usuario.handle}}</span>
        </span>
     
      
</template>


<script>
import Tweet from './Tweet.vue';

   
export default {
  props:["usuario"],
};
</script>


<style scoped>

</style>