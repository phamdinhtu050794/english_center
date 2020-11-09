<template>
  <div class="teaching-container">
    <div>
        <h1>TEACHING STAFF</h1>
    </div>
    <div class="img-container">
        <div class="img">
            <img src="@/assets/avatar1.jpg" width="300" height="400">
            <h3>Name</h3>
            <h4>Service</h4>
        </div>
         <div class="img">
            <img src="@/assets/avatar1.jpg" width="300" height="400">
            <h3>Name</h3>
            <h4>Service</h4>
        </div>
         <div class="img">
            <img src="@/assets/avatar1.jpg" width="300" height="400">
            <h3>Name</h3>
            <h4>Service</h4>
        </div>
         <div class="img">
            <img src="@/assets/avatar1.jpg" width="300" height="400">
            <h3>Name</h3>
            <h4>Service</h4>
        </div>
    </div>
    <div class="see">
        <div>See All</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TeachingStaff',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.teaching-container{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}
.img-container{
    display: flex;
    flex-direction: row;
    justify-content: center;
}
.img{
    border: 2px ;
    background-color: aquamarine;
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
