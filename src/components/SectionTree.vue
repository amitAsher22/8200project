<template>
  <div>
      <div  class="textMiddle" >
      <span><h1 class="titleTree">LIMITED TIME OFFER</h1></span>
      <span><h3 class="parText">Gain the experience via our DEMO trading account with $10,000 virtual money</h3></span>
      </div>
      <div>
      <span  ><button class="buttonDown" >START LEARNING</button></span>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.textMiddle{
  
     background-image: url("../assets/ocen.jpg"); 
     background-repeat: repeat-x;
     background-repeat: no-repeat;
     background-position: center;
     width: 100%;
     text-align: center;
     padding: 30px 0;
     margin-bottom: 5px;
    
}

.titleTree{
  color: white;
  font-size: 500;
  font-weight: 600;
  font-family: 'Mukta', sans-serif;
}
.parText{
  color: white;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
}
.buttonDown{
position: relative;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
  background-color: rgb(62, 62, 236);
  color: #f5deb3;
   width: 20%;
   min-width: 25%;
   border-radius: 10px;
  font-weight: 100;
    padding: 10px 40px;
  font-size: 12px;
   font-family: 'Mukta', sans-serif;
}

@media screen and (max-width: 992px){
    .buttonDown{
 width: 50%
    }
}

</style>