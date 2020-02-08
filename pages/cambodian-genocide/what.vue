<template>
    <div class="home">
    <Header></Header>
    <div class="title">
        What is the cambodian genocide? 
    </div> 


        <div class="info">
        <p>The Communist Party of Kampuchea, also known as the Khmer Rouge, took over the country of Cambodia from 1975-1979. The Khmer Rouge was created by Pol Pot, who was also the prime minister during this time. During this time, the Khmer Rouge caused a genocide that would be considered to be one of the biggest genocides. </p> <br></br>

        <p>The Cambodian Genocide was led by Pol Pot and the Khmer Rouge, in which their desire was to create an agarian society. In order to make this possible, they started executing all intellects, including teachers, doctors, scientists, monks, those who were religious, and anyone who had been educated at least once in their life. Moreover, they executed the children of the people they have killed in order to make sure there would be no intellects. Not only did they execute intellects, but they also executed people who could not work anymore, as well as any person who had connections with the military or the past government. There were also people who were executed even when they have not caused any crimes. This was done by torturing them and constantly accusing them of committing the listed crimes, and because of this, most of the people would lie in order to be able to finally be free from the torture that they were in. Starvation was also another common thing during this period, and many died due to this. Because of the significant number of deaths, killing fields were made in order to store the skeletons of the dead. Currently, there are over 200 killing fields in the country of Cambodia. </p> <br></br>
         
         <img src="/cambodian-genocide/000045.JPG" style="width:95%;"> <br></br>

        <p> The Khmer Rouge took place from 1975-1979. The Khmer Rouge Regime took over the capital city of Cambodia, Phnom Penh in 1975, April 17. However, in around 1978 December, neighboring country Vietnam invaded Cambodia and on January 7th, Phnom Penh was captured, putting an end to the 4 year-rule of the Khmer Rouge. </p>
        
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

<style>
.home{
    background-color: #ffffff; 
    min-height: 100vh;
}

.title{
  padding-top: 30px; 
  background-color: #ffffff; 
  opacity: 0.9; 
  color: #000000; 
  height: 100px;
  padding-left: 10px; 
  position: inline-block; 
  font-family: "Times New Roman", Times, serif;
}

.info{
    font-family: "Times New Roman", Times, serif;
    padding-left: 10px; 
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

</style>