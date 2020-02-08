<template>
    <div>
        <div class="fixed" id="fixed">
            <h2><nuxt-link :to="{path:'/cambodian-genocide'}"> Cambodian Genocide </nuxt-link> </h2>
        </div>
        <div class="navbar">
            <img src="/cambodian-genocide/000030.JPG" style="width:100%;">
            <div class="centered">
                <h2><nuxt-link :to="{path:'/cambodian-genocide'}"> Cambodian Genocide </nuxt-link> </h2>
            </div>    
            
        </div>
    </div>
</template>

<script>
export default {

   
   name:"Header",
   mounted() {
       window.onscroll = () => {
           this.scrollFunction()
       };
   },
   methods: {
       scrollFunction() {
            if (document.body.scrollTop > 80 || document.documentElement.scrollTop > 80) {
                document.getElementById("fixed").style.display = "block";
            } else {
                document.getElementById("fixed").style.display = "none";
            }
       },
   },

}
</script>

<style scooped>

.navbar{
  position:relative;
}

.navbar .centered{
  position:absolute;
  background-color:#ffffff; 
  opacity: 0.7;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%);
  padding:35px;
  text-align:center;
}

.navbar .centered h2{
  font-family: "Times New Roman", Times, serif;
  text-align:center;
  font-size: 26px;
  font-weight:normal;
  color:#F0B49E;
}

.navbar .centered h2 a{
  color: #000000; 
}

.fixed {
    position: fixed;
    z-index: 100;
    top: 0;
    left: 0;
    width: 100%;
    background: #000000;
    padding: 10px;
}

.fixed a{
    color: #ffffff;
}





</style>