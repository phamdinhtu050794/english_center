<template>
  <!-- <div class="container"> -->
  <div class="child1-container">
    <div class="information">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. In hac habitasse
      platea dictumst vestibulum rhoncus. Dolor sit amet consectetur adipiscing
      elit ut. Integer quis auctor elit sed vulputate mi sit. Senectus et netus
      et malesuada fames ac turpis egestas. Tellus elementum sagittis vitae et
      leo duis ut diam. Volutpat diam ut venenatis tellus in metus vulputate eu.
      Turpis egestas integer eget aliquet nibh. Ut lectus arcu bibendum at
      varius vel. Gravida cum sociis natoque penatibus et. Blandit cursus risus
      at ultrices mi tempus imperdiet.
    </div>
    <div class="arrow-down">
      <div></div>
    </div>
    <div>
      <img src="@/assets/avatar.jpg" width="100" height="100" />
      <div class="name">Nguyen Van A</div>
      <div>Hanoi Law University - IELTS 8.0</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SuccessChild1",
  props: {
    // msg: String
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.child1-container {
  display: flex;
  flex-direction: column;
  // justify-content: space-around;
  border-radius: 50px 50px 50px 50px;
}
.information {
  background-color: red;
  border: 2px;
  border-radius: 25px;
  padding: 10px;
}
.arrow-down {
  display: flex;

  justify-content: center;
  align-items: center;
}
.arrow-down div {
  width: 0;
  height: 0;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-top: 20px solid #f00;
}
img {
  background: white;
  border-radius: 50%;
  border: 2px solid black;
  height: 150px;
  margin: 20px;
  padding: 10px;
  text-align: center;
  width: 150px;
}
</style>
