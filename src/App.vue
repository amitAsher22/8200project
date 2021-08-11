<template>
<div>
  <div class="middleText">
    <h1 class="textLeftTitle">GROW YOUR PROFITS WITH <span class="gold">GOLD</span></h1>
   <h1  class="textLeftTitle"> INVEST IN THE <span class="gold">WORLD'S</span> MOST PRECIOUS METAL</h1>
   <div class="section1">
   <div class="right"></div>
   <div class="left">
     <div class="foremLeft">
       <p class="titleLeft">start investing in the precious metal</p>
       <div class="inputMain">
       <input class="inputLeft" placeholder="Full name"/>
       <input class="inputLeft" placeholder="Email"/>
       <input class="inputLeft" placeholder="Israel(+972)"/>
       <input class="inputLeft" placeholder="Phone Number"/>
       <span class="colorText"><input type="checkbox"/> I agree to the<span class="colorLeft"> Terms and Conditions</span> and <span class="colorLeft" > <br>privet Policy </span></span>
         </div>
       <button class="buttonLeft">START NOW!</button>
     </div>
   </div>
   </div>
     <div class="blackSection">Trading gold is always trendy and worthy, it would be wise to consider gold trading to build your own fortune.<br>
Gold has been moving up and breaking new highs, and ensuring great returns to its investors</div>
  </div>

</div>
<SectionTwo/>
<SectionTree/>
<SectionFour/>
<SectionFive/>
</template>

<script>

import SectionTwo from './components/SectionTwo.vue'
import SectionTree from './components/SectionTree.vue'
import SectionFour from './components/SectionFour.vue'
import SectionFive from './components/SectionFive.vue'

export default {
  name: 'App',
  components: {
   SectionTwo,SectionTree ,SectionFour ,SectionFive
  }
}
</script>

<style>

*{
  padding: 0;
  margin: 0;
}
.gold{
  color: gold;
}
.middleText{
  text-align: center;
  padding-top: 10px;
  background-image: url("./assets/bitcon.jpg");
  max-width: 100%;
  color: white;
  background-repeat:no-repeat;
  height:50rem;
  font-weight: 400;
  
}
.section1{
 display: flex;
justify-content: space-around;
 flex-direction:row;
    flex-wrap: wrap;
    margin-top: 5%;
 

}

.left{
  display: flex;

}


.foremLeft{
  border-radius: 15px;
  background-color: white;
  display: flex;
  flex-direction: column;
    
 
 
}
.titleLeft{
  color: white;
  background-color: orange;
  text-align: center;
  margin-top: 0 ;
  padding: 23px 25px;
  border-top-left-radius: 9px;
  border-top-right-radius: 9px;
    font-size: 1em;
    font-weight: 400;
     font-family: 'Mukta', sans-serif;

  
 
}
.inputMain{
  display: flex;
 flex-direction: column; 
  padding: 25px;
  align-items: right;

 
}

.inputLeft{
  width: 80%;
  margin: 5px;
  padding:8px;
  border-radius: 4px;
  font-weight: 100;
  border-color: rgb(252, 246, 246);
  

}
.colorText{
  font-size:0.7em;
  color: black;
  font-weight: 200;
}
.colorLeft{
  color: rgb(81, 179, 245);
}
.buttonLeft{
  padding: 10px 40px;
  margin: 30px 20px;
  background-color: rgb(62, 62, 236);
  color: white;
  width: 80%;
  border-radius: 10px;
  font-weight: 100;
  font-size: 12px;
   font-family: 'Mukta', sans-serif;
}


.blackSection{
   position: relative;
    left: 0;
    top: 10%;
    width: 100%;
    background-color: rgba(0,0,0,0.8);
    color: white;
    text-align: center;
    justify-items: center;
    padding: 20px 0;
    font-weight: bold
   



}
.textLeftTitle{
  font-size: 1.4em;
}
</style>
