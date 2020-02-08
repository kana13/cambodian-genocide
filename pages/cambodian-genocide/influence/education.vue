<template>
    <div class="home">
    <Header></Header>
    <div class="title">
    Influence on Education 
    </div>
    <div class="info">
    <p>Currently, Cambodia is still rebuilding the country’s education that was destroyed during the Khmer Rouge Regime. During this time, the government completely destroyed all facilities regarding education within the country destroying the education’s key personnel. Furthermore, during the 1980s, Vietnam supported the successor of the Khmer Rouge and denied the need for the country’s education to be assisted. </p> <br></br>

    <p>Before the genocide, Cambodia had put in great efforts to improve the country’s education after the country gained it’s independence, investing more than 20% of the country’s funds to education. However, the Khmer Rouge destroyed the previous government and education was abolished from the country. The Khmer Rouge is estimated to have destroyed 90% of school buildings, libraries, contents, and equipment (Building the New Cambodia). According to the Ministry of  Education of the State of Cambodia, "75% of the teaching force, 96% of tertiary students, and 56% of elementary/secondary pupils died during the Khmer Rouge rule. The University of Phnom Penh also has stated that out of the 1000 academics and intellectuals that attended the university, only 87 survived. It took over 10 years for the country to start reconstructing once again in 1991. At that time, the country spent around 15% of the country’s funds to education but in 3 years, the percentage has dropped to 8%. </p> <br></br>

  <img src="/cambodian-genocide/education.jpg" style="width:95%;"> <br></br> 
    <p>According to the chart, most of the population has only received education until primary school. Approximately 70% of the population has only received education from primary level (2002 International Labour Organization and the National Institute of Statistics, Ministry of
Planning, Phnom Penh, Cambodia, First published 2002). The net enrollment in primary education is said to be 97% within the country, and the completion status is 90%. However, enrollment in lower secondary or middle school is only 38%, and upper secondary or high school is a mere 18%. (World Bank Document). Furthermore, only 41% of the students enrolling in middle school and 27% of those who enrolled in high school graduate. This states that while some may enroll in secondary school, there is a high drop-out rate within the country. In fact, within the ASEAN countries, Cambodia has the lowest share of adults with lower secondary education (CDRI, 2013). 

    <p>Furthermore, the education that the pupils are receiving within the country is very low. It has been researched that a teacher teaches 46 pupils at a time, which exceeds the upper limit of 40 students per teacher where they can provide quality learning to the students. (CDRI, 2014). The amount of hours spent at school is also very low, with 3 hours and 20 minutes. Compared to the international benchmark of 6~8 hours, it clearly represents the low quality of education that students are receiving. The quality of learning is represented with the data that EQAD collected. The data provides an insight of the student’s proficiency in math, reading, and writing.</p><br></br>
  <img src="/cambodian-genocide/education2.jpg" style="width:95%;"> <br></br>
    <p> As represented in the graph, the student’s proficiency levels are very low, and around half of the overall’s percentage for writing and reading is below basic level. As for the data that represents the student’s math test scores, while large urban cities have shown improvement from 2007~2013. 
While this seems to be a certain improvement for education was forbidden during the Khmer Rouge regime, compared to other countries, the level of education that most of the population is receiving is still very low. However, there is a major factor affecting the country’s education level, which is poverty. </p><br></br>
 
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