<template>
  <div class="home1">
    <div class="picture">
    
    <img src="/cambodian-genocide/000044.JPG">
     <div class="inner_box">
      <h2><nuxt-link :to="{path:'/cambodian-genocide'}">Cambodian Genocide: Home </nuxt-link></h2>
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
  color:#F0B49E;
}

.picture .inner_box h2 a{
  color: #ffffff; 
}

</style>
