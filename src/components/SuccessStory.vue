<template>
  <div class="successstory-container">
    <div class="title">
      <h1> SUCCESS STORY </h1>
    </div>
    <div class="successchild">
    <SuccessChild1 class="child1"></SuccessChild1>
    <SuccessChild1 class="child1" ></SuccessChild1>
    <SuccessChild1 class="child1"></SuccessChild1>
    </div>
   

    <div class="circle-container">
      <div class="circle"></div> &nbsp;
      <div class="circle" id="color"></div> &nbsp;
      <div class="circle"></div>

    </div>
  <div class="succeschild2">
     <SuccessChild2 class="child2"></SuccessChild2>
    <SuccessChild2 class="child2"></SuccessChild2>
    <SuccessChild2 class="child2"></SuccessChild2>

  </div>
   
    <div class="more">
      <div>See All </div>
      
    </div>
  
  </div>
</template>

<script>
import SuccessChild1 from "@/components/SuccessChild1.vue";
import SuccessChild2 from "@/components/SuccessChild2.vue";

export default {
  name: 'SuccessStory',
  components: {
      SuccessChild1,
      SuccessChild2
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.successstory-container{
    background-color:white;
    border: 2px;
  border-radius: 50px;
  padding: 10px;


}
.title{
  color: red;
}
.successchild{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  
}
.succeschild2{
    display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin: 50px;
  

}
.child1{
  display: flex;
  justify-content: space-around;
  border: 2px;
  border-radius: 50px;
  padding: 10px;
  margin: 10px;
}
.child2{
   display: flex;
   flex-direction: column;
  justify-content: space-around;
  border: 2px;
  border-radius: 50px;
  padding: 10px;
  margin: 20px;

}
// .circle-container{
//   display: flex;
//   flex-direction: row;
  
//   // justify-content: space-around;

// }
.circle{
  height: 10px;
  width: 10px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  flex-direction: row;
}
#color{
  background-color: black;
}
.more{
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 10px;
}

.more div {
  width: 200px;
  border: 2px;
  border-radius: 50px;
  padding: 10px;
  background-color: red;
  // background-color: green; 
}


</style>
