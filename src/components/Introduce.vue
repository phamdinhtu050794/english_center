<template>
  <div class="introduce-container">
    <div>
        <h1>ACADEMIC ENGLISH - INTERNATIONAL EDUCATION</h1>
        <h4>Being a pioneer in providing English Academic For International Education with more than 15 years of experience in English <br>
            training and IELTS preparation according to Australian standards in Vietnam. Here, we always keep in mind that learning <br>
            English is not only about learning a new language, but also learning how to think, explore knowledge, learn soft skills and a <br>
            living capital to confidently integrate into the school environment. internships and success in global working environment</h4>
    </div>
    <div>
        <h1>ACET - THE FIRST HOUSE OF ACADEMIC ENGLISH</h1>
        <div class="number-review">
            <div class="box">
                <div class="number">
                    <h1>16</h1>
                </div>
                <h4>YEARS OF EXPERIENCE <br> IN ENGLISH TRAINING <br> AND IELTS TRAINING</h4>
            </div>
            <div class="box">
                <div class="number">
                    <h1>156</h1>
                </div>
                <h4>PROFESSIONAL <br> LANGUAGE TEACHERS <br> FROM US, UK, <br> AUSTRALIA ...</h4>
            </div>
            <div class="box">
                <div class="number">
                    <h1>250000</h1>
                </div>
                <h4>PEOPLE TESTED ONLINE ENGLISH <br> LEVELS <br>
                        50,000 STUDENTS STUDYED HERE</h4>
            </div>
            <div class="box">
                <div class="number">
                    <h1>80</h1>
                </div>
                <h4>% OF STUDENTS GET <br> AN IELTS SCORE OF <br> 6.0 OR HIGHER</h4>
            </div>

        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Introduce',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.introduce-container{
    background-color:beige;
}
h1{
    color: red;
}
.number-review{
    display: flex;
    flex-direction: row;
    justify-content: center;
    
    // background-color: white;
  
}
.number{
    font-size: 30px;
    // width: 200px;
    // height: 100px;
    // background-color: white;
   
}
.number h1{
    color: black;
    // width: 100px;
    background-color:white;
    display: flex;
    justify-content: space-around;
     border: 2px;
  border-radius: 0px;
  padding: 10px;
  margin: 20px;
  
}
.box{
    width: auto;
    height: 300px;
    // background-color: green;
    margin: 20px;
}

</style>
