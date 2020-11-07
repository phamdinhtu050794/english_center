<template>
  <div class="header-container">
      
    <div class="logo">
      <h1>idp| IELTS</h1>
    </div>
    <div class="menu">
      <div class="dropdown">
        <h3>Why Choose ACET</h3>
            <ul class="dropdown-content">
                <li><a href="#">The reason for choosing acet</a></li>
                <li><a href="#">Academic English</a></li>
                <li><a href="#">Teaching staff</a></li>
                <li><a href="#">International certificate</a></li>
                <li><a href="#">Privilege students</a></li>
                <li><a href="#">School link</a></li>
            </ul>
      </div>
      <div class="dropdown">
        <h3>Course</h3>
            <ul class="dropdown-content">
                <li><a href="#">Academic English</a></li>
                <li><a href="#">Practice IELTS</a></li>
                <li><a href="#">Academic English for junior high school</a></li>
                <li><a href="#">English learning skills</a></li>
                <li><a href="#">Enterprise training</a></li>
            </ul>
      </div>
      <div class="dropdown">
        <h3>New & Events</h3>
            <ul class="dropdown-content">
                <li><a href="#">News</a></li>
                <li><a href="#">Success Story</a></li>
                <li><a href="#">Experience learning IELTS</a></li>
                
            </ul>
      </div>
      <div class="dropdown">
        <h3>IDP IELTS & Study Abroad</h3>
            <ul class="dropdown-content">
                <li><a href="#">IELTS test at ADP</a></li>
                <li><a href="#">IDP consulting abroad</a></li>
            </ul>
      </div>
      <div class="dropdown">
        <h3>Recruitment</h3>
            <ul class="dropdown-content">
                <li><a href="#">teacher</a></li>
                <li><a href="#">Staff</a></li>
            </ul>
      </div>
      <div class="more">
        <h3>Contact</h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.menu {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.menu h3 {
  border: 2px;
  border-radius: 50px;
  padding: 10px;
  margin: 10px;
}
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
//   min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  padding: 12px 16px;
  z-index: 1;
  width: 200px;
  height: auto;
  border-radius: 25px ;
}


.dropdown:hover .dropdown-content {
  display: block;
}
a{
    font-size: 16px;
    color: black;
    //    color: #FFFFFF;
    text-decoration: none;
}
.more{
    display: flex;
  justify-content: center;
  align-items: center;
   border: 2px;
  border-radius: 25px;
  padding: 10px;
  background-color: red;
  width: 100px;
  height: 30px;
  margin-bottom: 10px;
}
.dropdown-content li {
    text-align: left;
}
</style>
