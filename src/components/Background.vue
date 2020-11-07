<template>
  <div class="background-container">
      <div>
          <img src="@/assets/acet1.jpg" width="1920" height="800" />
           <div class="title-img">
        <h1>Academic English - International Education</h1>
        <hr width="15%" size="5px" align="center" color="red" />
      </div>

      </div>
    

      <div class="circle-container">
        <div class="circle"></div>
        &nbsp;
        <div class="circle" id="color"></div>
        &nbsp;
        <div class="circle"></div>
      </div>
    </div>
  
</template>

<script>
export default {
  name: "Background",
 
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">



.circle {
  height: 10px;
  width: 10px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  flex-direction: row;

}
#color {
  background-color: black;
}
</style>
