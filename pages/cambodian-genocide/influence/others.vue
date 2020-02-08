<template>
    <div class="home">
    <Header></Header>
    <div class="title">
    Other influences. 
    </div>
    <div class="info">
      <p>The Khmer Rouge also caused several other problems within the country. People still face poverty and have inadequate amount of health care resources in the country. 74% of the adult population face poverty. </p> <br></br>

      <p>The Khmer Rouge took a huge toll on the country’s population. By observing the graph, while it seems as if it is a normal population pyramid following its structure decreasing by age group, there is a huge gap between age 15~19, and 20~24. This was because around this time, the Cambodian genocide happened which meant less child birth during that time. This caused the population in Cambodia in 2001 to be structured by young infants and children from ages 0~14 years olds that take up approximately 43% of the country’s population. The graph has also shown that 40~74 has an unusual sex ratio, where there are a more significant number of females compared to males. This was due to the fact that ⅔ of the victims of the Khmer rouge were males and ⅓ were females. The population of people that are aged 60 or older is merely 6% in the country, according to an investigation done in 2000, which indicates that there is one older adult per 4 households. </p> <br></br>
      <img src="/cambodian-genocide/population.jpg" style="width:95%;"> <br></br>
      <p>Initially, the country’s population before the Khmer Rouge Regime was approximately 7 million. During the Khmer Rouge period though, approximately 2 million were killed due to execution, diseases, starvation, and war related causes. </p> <br></br>

      <p>As for health care, compared to Asia’s average for HIV/AIDs population which is around 0.5%, Cambodia has a percentage of 2.6%. The country’s life expectancy is 56 years compared to the region’s average of 69 years, and infant mortality is 95 deaths per 1000 live births, which is far larger in number compared to the region’s average of 39 deaths. </p> <br></br>

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