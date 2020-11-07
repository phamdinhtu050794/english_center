<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <Background></Background>
    <Introduce></Introduce>
    <SuccessStory></SuccessStory>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import SuccessStory from '@/components/SuccessStory.vue'
import Background from '@/components/Background.vue'
import Introduce from '@/components/Introduce.vue'


export default {
  name: 'Home',
  components: {
    HelloWorld,
    SuccessStory,
    Background,
    Introduce
    
  }
}
</script>
