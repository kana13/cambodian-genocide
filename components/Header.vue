<template>
    <div class="head">
        <nuxt-link :to="{path:'/'}"> Cambodian Genocide </nuxt-link> 
    </div>

</template>

<script>
export default {
   name:"Header"
}
</script>

<style scooped>
.head{
    background-color: #E08E79;
    text-align: center; 
    min-height: 13vh;
    font-family: "Times New Roman", Times, serif;
    margin: 0, auto; 
}
.head a {
    color: #774F38; 
    font-size: 30px; 
    margin: 0, auto; 
}

</style>