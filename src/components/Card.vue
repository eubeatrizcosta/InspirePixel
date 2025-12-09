<script setup>
defineProps(["imagem"]);
//o que é o defineProps
//é uma função do vue que permite receber dados em comunicação de componentes
</script>

<template>

    <div class="card">
        <img :src="imagem" alt="Imagem do card">
    </div>
    
</template>

<style scoped lang="scss">
.card{
    //border: solid;
    width: 30vw;
    border-radius: 10vw;
      background: #fff;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  transition: .3s ease;
  cursor: pointer;

  &:hover {
    transform: translateY(-6px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.25);
  }

   
    img{

       width: 100%;
    height: 200px;
    object-fit: cover;
  }
        border-radius: 10px;
    }

    

</style>