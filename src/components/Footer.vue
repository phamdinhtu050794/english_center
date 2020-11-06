<template>
  <div class="footer-container">
    <div class="header-footer">
      <div class="title">
        <h1>ACET</h1>
      </div>
      <div class="body">
        <div class="colum">
          <div class="colum1">
            <ul class="center">
              
              <div><h3>HANOI ACET CENTER</h3></div>
              <li>
                ACET Dao Duy Anh - Ocean Park Building, 01 Dao Duy Anh <br />
                Tel: 024 3976 5268 - Fax: 024 3976 5266
              </li>
              <br />
              <li>
                ACET Ngoc Khanh - Number 15-17 Ngoc Khanh, Ba Dinh <br />
                Tel: 024 3732 5303 - Fax: 024 3732 5304
              </li>
              <li> Email:<a
                href="http://info-hn@acet.edu.vn"
                target="_blank"
                rel="noopener"
                >info-hn@acet.edu.vn</a
              >
              </li>
            </ul>
            <ul class="center">
              <div><h3>HO CHI MINH ACET CENTER</h3></div>
              <li>
                ACET Vo Thi Sau - Number 187 Vo Thi Sau, District 3 <br />
                Tel: 028 3932 6202 - Fax: 028 3932 6208
              </li>
              <br />
              <li>
                ACET Le Van Sy - Number 226 Le Van Sy, Tan Binh <br />
                Tel: 028 3991 2999 - Fax: 028 3991 7556
              </li>
              <li>Email:<a
                href="http://info-hcm@acet.edu.vn"
                target="_blank"
                rel="noopener"
                >info-hcm@acet.edu.vn</a
              >
              </li>
            </ul>
          </div>
          <div class="colum2">
            <ul class="center">
              <div><h3>Why Choose ACET</h3></div>
              <li><a href="#"> Reasons for choosing ACET</a></li>
              <li><a href="#">Academic English - Academic English</a></li>
              <li><a href="#">Privilege students</a></li>
              <li><a href="#">International certificate</a></li>
              <li><a href="#">Teachers</a></li>
            </ul>
            <ul class="center">
             <div> <h3>IELTS test and study abroad</h3></div>
              <li><a href="#">IELTS test</a></li>
              <li><a href="#">Study abroad</a></li>
            </ul>
            <ul class="center">
             <div> <h3>Accompany with ACet</h3></div>
              <li><a href="#">Success Story</a></li>
              <li><a href="#">News</a></li>
              <li><a href="#">Events and Offers</a></li>
            </ul>
          </div>
          <div class="colum3">
            <ul class="center">
             <div> <h3>Study program</h3></div>
              <li><a href="#">English for Academic Purposes</a></li>
              <li><a href="#">Practice IELTS</a></li>
              <li><a href="#">Secondary School English for Academic Purposes</a></li>
              <li><a href="#">English Language Arts Skills</a></li>
              <li><a href="#">ACET Summer</a></li>
            </ul>
            <ul class="center">
             <div> <h3>Training association</h3></div>
              <li><a href="#">School link</a></li>
              <li><a href="#">Enterprise association</a></li>
            </ul>
            <ul class="center">
             <div> <h3>Contact</h3></div>
              <li>ACET Vo Thi Sau:<a href="#" > 028 3932 6202</a></li>
              <li>ACET Le Van Sy:<a href="#" >028 3991 2999</a></li>
              <li>ACET Dao Duy Anh:<a href="#" >024 3976 5268</a></li>
              <li>ACET Ngoc Khanh:<a href="#" >024 3732 5303</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="footer-footer">
      
     
      <h3>
        &#169; Copyright: 2020 MuaTheme.com . All rights reserved. <br />
        Designed by TrustWeb.vn
      </h3>
    </div>
  </div>
</template>

<script>

export default {
  name: "Footer",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.footer-container {
  background-color: rgb(247, 54, 54);
}
.colum {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  color: white;
  font-size: 16px;
}
.center {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
 
}
.center li, div  {
  text-align: left;
  color: white;
}

.footer-footer{
  text-align: left;
}
a{
  color: white;
}
.colum1{
  background-color: rgb(134, 7, 7);
  width: 400px;
}
</style>
