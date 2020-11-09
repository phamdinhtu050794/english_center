<template>
  <div class="send-container">
    <div class="colum1">
      <h1>REGISTER TO THE LEARNING PROGRAM</h1>
      <h4>
        Leave your information and ACET will help build the best English
        language pathway just for you.
      </h4>
    </div>
    <div class="colum2">
      <div class="basic">
        <h5>Basic information</h5>
        <input v-model="fullname" placeholder="First and last name..." />
        <input v-model="phone" placeholder="Phone number..." />
        <input v-model="email" placeholder="Email" />
      </div>

      <div class="select">
        <h5>Selection</h5>
        <div class="row1">
          <select v-model="selected">
            <option  disabled value="">Area</option>
            <option >Area</option>
            <option >Hanoi</option>
            <option >City. Ho Chi Minh</option>
          </select>
          <select v-model="selected1">
            <option  disabled value="">Course</option>
            <option >Academic English</option>
            <option >Secondary School English for Academic Purposes</option>
            <option >Practice IELTS</option>
            <option >English learning skills</option>
          </select>
        </div>

        <div class="row2">
          <select v-model="selected2">
            <option  disabled value="">Choose a study time</option>
            <option >Shining</option>
            <option >Dark</option>
          </select>
        </div>
      </div>

      <div class="more">
        <h2>Send Information</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SendInformation",
  data(){
    return{
      fullname:'',
      phone: '',
      email: '', 
      selected: '',
      selected1:'',
      selected2:'',
    }
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.send-container {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  background-color:rgb(245, 242, 236);
}
.colum1{
  display: flex;
  flex-direction: column;
  // justify-content: space-around;
  border: 2px;
  border-radius: 25px;
  width: 650px;
  
  
}
.colum2 {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: flex-start;
  border: 2px;
  border-radius: 25px;
  width: 600px;
  height: 500px;
  margin-left: -250px;
  background-color: white;
}

.basic{
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: flex-start;
  margin-left: 50px;
}
.basic input{
  border: 2px ;
  border-radius:50px;
  width: 40em;
  height: 4em;
  margin-bottom: 10px;
  background-color: rgb(216, 213, 209);
}
.select {
  display: flex;
  flex-direction: column;
  justify-content: space-around;

  align-items: flex-start;
  margin-left: 50px;
}
.row1  {
  border: 2px;
  border-radius: 50px;
  

}

h5{
  font-size: 20px;
}
h1{
  color: red;
}
.more{
    display: flex;
  justify-content: center;
  align-items: center;
   border: 2px;
  border-radius: 25px;
  padding: 10px;
  background-color: red;
  width: 200px;
  height: 20px;
  margin-left: 180px;
  margin-bottom: -20px;
}

</style>
