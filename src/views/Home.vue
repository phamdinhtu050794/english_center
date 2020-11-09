<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <Background></Background> <br>
    <Introduce></Introduce> <br>
    <SendInformation></SendInformation><br>
    <Course></Course> <br>
    <SuccessStory></SuccessStory>
    <TeachingStaff></TeachingStaff>
    <NewEvents></NewEvents>
    <TestEnglish></TestEnglish>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import SuccessStory from '@/components/SuccessStory.vue'
import Background from '@/components/Background.vue'
import Introduce from '@/components/Introduce.vue'
import SendInformation from '@/components/SendInformation.vue'
import Course from '@/components/Course.vue'
import TeachingStaff from '@/components/TeachingStaff.vue'
import NewEvents from '@/components/NewEvents.vue'
import TestEnglish from '@/components/TestEnglish.vue'


export default {
  name: 'Home',
  components: {
    HelloWorld,
    SuccessStory,
    Background,
    Introduce,
    SendInformation,
    Course,
    TeachingStaff,
    NewEvents,
    TestEnglish
    
  }
}
</script>
