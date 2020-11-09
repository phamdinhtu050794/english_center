<template>
  <div class="course-container">
    <div class="row1">
      <div class="img1">
       
        <img src="@/assets/acet2.png" width="1000" height="350" />
        <div class="note">
            
          <div>
            <hr id="height" width="0px" size="5px" align="center" color="red" />
          </div>
          <div class="h">
            <h2>Academic English</h2>
            <h4>Academic English</h4>
          </div>
        </div>
      </div>
      <div class="img2">
        <img src="@/assets/acet3.jpg" width="450" height="350" />
        <div class="note">
          <div>
            <hr id="height" width="0px" size="5px" align="center" color="red" />
          </div>
          <div class="h">
            <h2>Academic English First Step</h2>
            <h4>English for junior high school</h4>
          </div>
        </div>
      </div>
    </div>
    <div class="row2">
      <div class="img3">
        <img src="@/assets/acet4.jpg" width="450" height="350" />
        <div class="note">
          <div>
            <hr id="height" width="0px" size="5px" align="center" color="red" />
          </div>
          <div class="h">
            <h2>IELTS</h2>
            <h4>Practice IELTS</h4>
          </div>
        </div>
      </div>
      <div class="img3">
        <img src="@/assets/acet5.jpg" width="450" height="350" />
        <div class="note">
          <div>
            <hr id="height" width="0px" size="5px" align="center" color="red" />
          </div>
          <div class="h">
            <h2>SkillSet</h2>
            <h4>English Language Arts Skills</h4>
          </div>
        </div>
      </div>
      <div class="img3">
        <img src="@/assets/acet1.jpg" width="450" height="350" />
        <div class="note">
          <div>
            <hr id="height" width="0px" size="5px" align="center" color="red" />
          </div>
          <div class="h">
            <h2>ACET Summer</h2>
            <h4>English Summer Camp</h4>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Course",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.row1 {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.row2 {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.note {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  justify-items: flex-start;
  //   background-color: green;
  margin-top: -120px;
}

#height {
  height: 80px;
  margin-left: 0px;
  margin-left: 10px;
}
h2,
h4 {
  color: white;
}
</style>
