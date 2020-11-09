<template>
  <div class="testenglish-container">
   <div>
       <div class="img">
           <img src="@/assets/thuvien.jpg">
       </div>
       <div>
           <div>
               <h1>Test your English online</h1>
           <h3>Do you know your current English level?</h3>
           </div>
           <div class="see">
               <div>Sign up for the test</div>
           </div>
       </div>

   </div>
   <div class="partner">
       <hr width="10%"  />
       <h2>Our partner</h2>
       <hr width="10%"  />
   </div>
   <div class="logo-container">
       <div class="logo">LoGo</div>
       <div class="logo">LoGo</div>
       <div class="logo">LoGo</div>
       <div class="logo">LoGo</div>
   </div>
  </div>
</template>

<script>
export default {
  name: 'TestEnglish',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.partner{
    display: flex;
    flex-direction: row;
    justify-content: center;
}
.partner hr{
    height: 0px;
}

.logo-container{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}

.see{
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 10px;
}

.see div {
  width: 200px;
  border: 2px;
  border-radius: 50px;
  padding: 10px;
  background-color: red;
  // background-color: green; 
}
</style>
