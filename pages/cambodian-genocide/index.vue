<template>
  <div class="home">
  <Header></Header>
    <div class="welcome">
      Welcome 
    </div>
    <div class="intro">
      Welcome to my website regarding the Cambodian Genocide. For my personal project, I researched about the Cambodian Genocide and how it affects current society, primarily education. I chose this topic since when I was 13, I visited Cambodia and one of the killing fields in Siem Reap, and was shocked at the time. I wanted to investigate more, and I thought that this personal project would be a great opportunity in order to understand and research deeply about this topic. My product is an article, but I have also decided to create a website that has the same information on a website so that people could obtain the information I organsied online. 
    </div> 
   
    <div class="pages">
     <div class="who"> Who started it? 
      <div class="whob">
      <button class="button1">
        <nuxt-link :to="{path:'/cambodian-genocide/who'}"> Details </nuxt-link>
      </button>
      </div>
     </div>

     <div class="what">What happened? When/Where did it occur?
      <div class="whatb">
      <button class="button3">
        <nuxt-link :to="{path:'/cambodian-genocide/what'}"> Details </nuxt-link>
      </button>
      </div>
     </div>

     <div class="edu"> Influence on education. 
      <div class="edub">
      <button class="button4">
      <nuxt-link :to="{path:'/cambodian-genocide/influence/education'}"> Details</nuxt-link>
      </button>
      </div>
     </div>
     
     <div class="others"> Influence on others. 
     <div class="othersb">
     <button class="button5">
        <nuxt-link :to="{path:'/cambodian-genocide/influence/others'}"> Details </nuxt-link>
     </button>
     </div> 
     </div>
    </div> 
    
    <div class="dummy">
     <nuxt-link :to="{path:'/cambodian-genocide'}">  Home </nuxt-link> 
    </div>
  </div>


</template>

<script>
  import Header from "~/components/Header"
  export default{
   components: {Header}
  }
</script>

<style scooped>
.pages {
    text-align: left; 
    font-family: "Times New Roman", Times, serif;

}

.home{
    background-color: #ffffff; 
    min-height: 300vh;
}

.dummy{
  min-height: 30vh; 
  position: inline-block; 
  text-align: center; 
  font-family: "Times New Roman", Times, serif;
  padding-top: 100px; 
  background-color: #000000; 
  opacity: 0.98; 
  color: #ffffff; 
}

.dummy a{
  color: #ffffff;
}

.welcome{
  font-weight: bold; 
  font-size: 25px; 
  text-align: center; 
  font-family: "Times New Roman", Times, serif;
  color: #000000; 
  padding-top: 10px;
}

.intro{
  font-size: 13px; 
  text-align: center; 
  font-family: "Times New Roman", Times, serif;
  padding-top: 10px; 
}

.who{
  padding-top: 50px; 
  background-color: #000000; 
  opacity: 0.9; 
  color: #ffffff; 
  height: 130px;
  margin-top: 30px; 
  padding-left: 15px; 
  position: inline-block; 
}

.who a{
  color: #ffffff; 
}

.what{
  padding-top: 40px; 
  background-color: #ffffff; 
  opacity: 0.9; 
  color: #000000; 
  height: 100px;
  margin-top: 30px; 
  padding-left: 15px; 
  position: inline-block;
}

.what a{
  color: #000000; 
}

.edu{
  padding-top: 50px; 
  background-color: #000000; 
  opacity: 0.9; 
  color: #ffffff; 
  height: 130px;
  margin-top: 30px; 
  padding-left: 15px; 
  position: inline-block; 
}

.edu a{
  color: #ffffff; 
}

.others{
  padding-top: 30px; 
  background-color: #ffffff; 
  opacity: 0.9; 
  color: #000000; 
  height: 120px;
  margin-top: 30px; 
  padding-left: 15px; 
  position: inline-block; 
}

.others a{
  color: #000000; 
}


.button1{
  color: #ffffff; 
  background-color: #000000; 
  display: inline-block; 
  margin-top: 5px; 
}

.button3{
  color: #000000; 
  background-color: #ffffff; 
  opacity: 0.9;
  display: inline-block; 
  margin-top: 5px; 
}


.button4{
  color: #ffffff; 
  background-color: #000000; 
  opacity: 0.9;
  display: inline-block; 
  margin-top: 5px; 
}

.button5{
  color: #000000; 
  background-color: #ffffff; 
  opacity: 0.9;
  display: inline-block; 
  margin-top: 5px; 
}

</style>
