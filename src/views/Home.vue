<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    
    <SuccessStory></SuccessStory>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import SuccessStory from '@/components/SuccessStory.vue'


export default {
  name: 'Home',
  components: {
    HelloWorld,
    SuccessStory,
    
  }
}
</script>
