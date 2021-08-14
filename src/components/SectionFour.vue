<template>
  <div>
      <div class="sectionLast">
      <div class="div11"></div>
      <div class="div22">
          <h2 class="titleLeft">Invest In GOLD, Invest In YOU</h2>
          <input class="input" type="text" placeholder="Full Name"/>
          <input class="input" type="email" placeholder="Email"/>
          <input class="input" type="text" placeholder="Israel(+972)"/>
          <input class="input" type="number" placeholder="Phone Number"/><br>
          <span class="colorText"><input type="checkbox"/> I agree to the<span class="colorLeft"> Terms and Conditions</span> and <span class="colorLeft" > <br>privet Policy </span></span>
          <div><button class="buttonMiddle1">START NOW!</button></div>
      </div>
        
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

.sectionLast{
    background-image: url("../assets/img-bg.jpg");
    background-position: center;
    display: flex;
    flex-direction: column;
    text-align: center;
    align-items: center;
    padding-bottom:40px ;
    padding: 30px;
}
.div22{
    
    background-color: #ffffff;
    border-radius: 10px;
}
.div11{
    width: 300px;
    height: 300px;
    
}

.buttonMiddle1{
   padding: 10px 20px;
  margin: 20px 10px;
  background-color: rgb(62, 62, 236);
  color: white;
  width: 30%;
  border-radius: 10px;
  font-weight: 100;
  font-size: 12px;
   font-family: 'Mukta', sans-serif;
}


@media screen and (max-width: 992px){
    .buttonMiddle1{
      width: 40%;
    }
}



.input{
     width: 30%;
  margin: 5px;
  padding:8px;
  border-radius: 4px;
  font-weight: 100;
  border-color: rgb(162, 163, 162);
  outline: none;
   border-style:solid;
border-width:small;
}
</style>