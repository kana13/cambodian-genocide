<template>
  <div class="home">
  <Header></Header>
    <ul class="pages">
     <li><nuxt-link :to="{path:'/cambodian-genocide/who'}"> Who </nuxt-link></li>
     <li><nuxt-link :to="{path:'/cambodian-genocide/where'}"> Where </nuxt-link></li>
     <li><nuxt-link :to="{path:'/cambodian-genocide/why'}"> Why </nuxt-link></li>
     <li><nuxt-link :to="{path:'/cambodian-genocide/what'}"> What </nuxt-link></li>
     <li><a class="influence">Influence</a></li> 
     <li><nuxt-link :to="{path:'/cambodian-genocide/influence/education'}"> Influence on Education </nuxt-link></li>
     <li><nuxt-link :to="{path:'/cambodian-genocide/influence/poverty'}"> Poverty </nuxt-link></li>
    </ul> 
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
    padding-left: 15px; 
    padding-top: 20px; 
}

.pages a{
    color: #774F38;
}

.home{
    background-image: linear-gradient(to bottom, #f1d4af, #efd7b4, #eedbba, #eddec0, #ece1c6, #e8e3c9, #e4e4cc, #e0e5cf, #d7e5d1, #cfe4d5, #c9e2d8, #c5e0dc);
    min-height: 100vh;
}


</style>
