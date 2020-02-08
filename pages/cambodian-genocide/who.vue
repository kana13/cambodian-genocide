<template>
    <div class="home">
    <Header></Header>

    <div class="title">
    Who started it? 
    </div> 

     <div class="info">
        <p>
            Pol Pot was the main figure who led the Khmer Rouge that started from 1963. He took over the government in 1975 and was appointed as the prime minister in 1976 until the Khmer Rouge was overthrown by the Vietnamese during January in 1979. <br></br> 
        </p>

        <p>
            Originally named Saloth Sar, Pol Pot was born on May 19, 1925 in Kampong Thom province. He was educated in Phnom Penh, the capital city of Cambodia. He was not significant at school though, and was rather a mediocre student, and failed to attend high school. Because of this, he attended a technical school where he learnt carpentry for a year. Later on, Pol Pot went to study radio electrics abroad in Paris, France. While studying in Paris, he associated with the French Communist Party. There, he was introduced to nationalists from his country, whom later on became his allies during the Khmer Rouge Regime. <br></br> 
        </p>

        <p>
            He returned to Cambodia in 1953, and from 1956, he became a teacher at a private school until 1963. That same year, he officially changed his name from Saloth Sar to Pol Pot, and professionally became the secretary of the Communist Party of Kampuchea that was set up in 1960. From 1963-1975, Pol Pot and the other members of the Party worked on strengthening the power of the Khmer Rouge. In 1975, Pol Pot led the Khmer Rouge and overthrew the military government of Lon Nol, and in 1976, he officially became the prime minister of Cambodia. <br></br>
        </p>

        <p>
            However, in 1979, the Khmer Rouge was deposed by the Vietnamese forces, and Pol Pot as well as his followers fled to Thailand. While the Khmer Rouge still existed, their power declined over the years. In 1985, Pol Pot resigned his position as the leader of the Khmer Rouge, although he remained a significant figure in the organisation. By 1997, their power has immensely declined and during that year, he was put on house arrest. In 1998 April 15, Pol Pot passed away due to natural causes. <br></br> 
        </p>

        <img src="/cambodian-genocide/pol pot timeline.jpeg" style="width:95%;">

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
  padding-top: 50px; 
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