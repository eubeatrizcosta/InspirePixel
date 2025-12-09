<script setup>
import fotografo from '../assets/fotografo.png';
</script>
<template>
    <div class="banner">
        <div class="text-banner">
    <h1> Onde a paisagem <br> vira <span> inspiração</span>.</br></h1>
     <p> Explore paisagens, cores e luzes que inspiram novas histórias <br>através da fotografia.</br> </p>
</div>


<div class="img-banner">
    <img :src="fotografo" alt="Fotógrafo com câmera">
    </div>
</div>
</template>


<style scoped lang="scss">

.banner {
    //border: solid;
    display: flex;
    align-items: center;
    justify-content: 
center;
margin: 2rem;
gap: 20rem;
    
}

img{
width: 100%;



 }
 .text-banner{
    //border: solid;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;


 }
h1{
    font-style: Bold;
    font-size: 60px;
    font-weight: 800;
    line-height: 170%;

    

    span{
        font-size: 85px;
        color: #E1306C;
        line-height: 100%;
    }
}

p{
    font-size: 20px;
    font-weight: 500px;
}
</style>