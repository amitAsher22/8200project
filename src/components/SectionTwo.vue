<template>
  <div>
      <div class="AllImgs">
           <img class="imgSign" src="../assets/paypal.png"/>
           <img  class="imgSign" src="../assets/visa.png"/>
          <img class="imgSign" src="../assets/master.png"/>
          <img class="imgSign" src="../assets/ssl.png"/>
         
      </div>
      <div class="middle">
          <div class="left">
              <h3 class="titleMAIN">INVEST IN<span class="GoldTitle"> GOLD</span>, INVEST IN <span class="GoldTitle">YOU</span> </h3>
             heroku logs --tail <p class="text1">What’s stopping you from trading gold?<br>
                  Perhaps lack of knowledge and experience?<br>
                  If so, our educational package is exactly what<br>
                  you've been searching for. Including an A-Z<br>
                  training course with everything you need<br>
                  to know to start trading NOW!</p>
                  <h4 class="text2">Start earning the knowledge with our<br>
                     educational package</h4>
                     <button class="buttonMain">START NOW!</button>
          </div>
            <div class="right">
              <img class="imgRight" src="../assets/people.png"/>
          </div>
         
      </div>
      <div class="footerBox">
          <div class="goldBox">
              <img class="symbolImg" src="../assets/mobile.png"/>
              <h3>Videos & Articles</h3>
              <p>All the subjects in our course<br>
                 come with follow along<br>
               <span class="textBlack">training videos</span> and articles.</p>
          </div>
          <div class="goldBox">
              <img class="symbolImg" src="../assets/monitor.png"/>
              <h3>Gold E-book</h3>
              <p>An A-Z book on with<br>
                 everything <span class="textBlack">you want</span>  and<br>
                 don't want to know <span class="textBlack">about</span> <br>
                <span class="textBlack"> gold</span>,it's uses and <span class="textBlack">how to</span> <br>
                <span class="textBlack">profit</span> from it.</p>
          </div>
            <div class="goldBox">
              <img class="symbolImg" src="../assets/gold.png"/>
              <h3>Gold training course</h3>
              <p>Our course is carefully<br>
                constructed by the <span class="textBlack">best gold</span> <br>
                <span class="textBlack">traders</span>  in the field</p>
          </div>
        
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.AllImgs{
       
    padding: 10px 0;
    display: flex;
    justify-content: center;
  
       
    
}
.imgSign{
    width: 6%;
    min-width: 60px;

}
.imgRight{
    min-width: 200px;
    width: 100%;
}
.middle{
    display: flex;
    flex-direction: row;
    justify-content: space-around;

}
@media screen and (max-width: 992px){
    .middle{
        display: flex;
        flex-direction: column;
    }
}
.left{
    display: flex;
    flex-direction: column;
    text-align: center;
     justify-content: center;
     align-items: center;
}

.footerBox{
    display: flex;
    flex-direction: row;
    justify-content: center;
    padding: 50px;
}
@media screen and (max-width: 992px){
    .footerBox{
        display: flex;
        flex-direction: column;
    }
}
.goldBox{
    color: white;
    background-color: rgb(255, 197, 5);
    padding: 50px 50px;
    margin:5px ;
    flex-wrap:wrap-reverse;
     align-items: center;
     text-align: center;

}

.symbolImg{
    height: 50px;
}
.titleMAIN{
    font-size: 1.9rem;
    font-weight: bolder;
}
.GoldTitle{
color: gold;
}
.text1{
    font-weight: 600;
      letter-spacing: 1px;
      font-family: 'Mukta', sans-serif;
      margin-bottom: 30px;
      
}
.text2{
   font-weight: bolder; 
   font-size: 1.5rem;
     border-spacing: 5em;
}
.buttonMain{
 padding: 10px 40px;
  margin: 30px 20px;
  background-color: rgb(62, 62, 236);
  color: white;
  width: 50%;
  border-radius: 10px;
  font-weight: 100;
  font-size: 12px;
   font-family: 'Mukta', sans-serif;
}

.textBlack{
    color: black;
  
     
}
</style>