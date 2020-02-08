<template>
  <div class="home1">
    <div class="picture">
    
    <img src="/cambodian-genocide/000044.JPG">
     <div class="inner_box">
      <h2>Cambodian Genocide</h2>
      <button class="homeb"><nuxt-link :to="{path:'/cambodian-genocide'}">Home </nuxt-link></button>
     </div>    
    </div>
  </div>
</template>

<script>
  export default{

  }
</script>

<style scooped>

.picture{
  position:relative;
}
.picture .inner_box{
  position:absolute;
  background-color:#000000; 
  opacity: 0.7;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%);
  padding:35px;
  text-align:center;
}

.picture .inner_box h2{
  font-family: "Times New Roman", Times, serif;
  text-align:center;
  font-size: 26px;
  font-weight:normal;
  color:#ffffff;
}

.picture .inner_box h2 a{
  color: #ffffff; 
}

.homeb{
  background-color: #000000;
  width: 50%;
  text-align: center; 
  font-size: 15px; 
  margin-top: 15px; 
}
.homeb a{
   color: #ffffff;
}
</style>
