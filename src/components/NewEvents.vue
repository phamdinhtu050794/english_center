<template>
  <div class="newevents-container">
    <div class="tiltle">
      <h1>News & Events</h1>
    </div>
    <div class="body">
      <div class="new">
        <div><h2>News</h2></div>
        <div>
          <img src="@/assets/acet2.png" width="600" height="400" />
          <h3>How to choose the best Hanoi English Center for you</h3>
        </div>
        <div>
          <h4>
            Whether you are looking for a class for IELTS preparation or simply
            choosing for English courses from elementary to high school,
            choosing a reliable Hanoi English Center is still a question ...
          </h4>
        </div>
        <div class="footer">
          <div><h4>SEE MORE</h4></div>
          <div>
            <div class="circle-container">
              <div class="circle"></div>
              &nbsp;
              <div class="circle" id="color"></div>
              &nbsp;
              <div class="circle"></div>
            </div>
          </div>
        </div>
      </div>
       <div class="events">
        <div><h2>ACET Events</h2></div>
        <div>
          <img src="@/assets/acet3.jpg" width="600" height="400" />
          <h3>How do you get high scores on the IELTS test, did you know?</h3>
        </div>
        <div>
          <h4>
           But in fact, if you know how to take the IELTS test to get high, you can still raise your IELTS score ...
          </h4>
        </div>
        <div class="footer">
          <div><h4>SEE MORE</h4></div>
          <div>
            <div class="circle-container">
              <div class="circle"></div>
              &nbsp;
              <div class="circle" id="color"></div>
              &nbsp;
              <div class="circle"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NewEvents",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.newevents-container{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    background-color: rgb(252, 126, 126);
    height: 100vh;
}
.body{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    
}
.new{
    width: 40%;
    height: 97%;
    border: 2px;
    border-radius: 25px;
    background-color: white;
}
.events{
    width: 40%;
    height: 97%;
    border: 2px;
    border-radius: 25px;
    background-color: white;
}
.footer{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.footer h4{
    color: red;
}
.circle{
  height: 10px;
  width: 10px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  flex-direction: row;
}
#color{
  background-color:red;
}
h1{
    color: white;
}
</style>
