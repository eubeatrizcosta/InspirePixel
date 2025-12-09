<script setup>
import { Icon } from "@iconify/vue";
</script>

<template>
    <footer>
        <div class="footer">
            <div class="contact">
        <h1> <a href=""> <img :src="contato" alt="">
            <Icon class="contact" icon="material-symbols:contact-page-sharp" width="60" color="#E1306C"/>  </a>
        </h1>
        <h2> contato@inspiralens.com </h2>
        <h2>Central de ajuda </h2>
    <h2> Rio de Janeiro - Brasil</h2>    
    </div>

<div class="about">
    <h1> <a href=""> <img :src="sobre" alt="">
        <Icon class="about" icon="material-symbols:contacts-product" width="60" color="#E1306C"/> </a>
        </h1>
    <h2> Politicas </h2>
    <h2> Politicas de privacidade </h2>
    <h2> Blog </h2>
</div>
<div class="novidades">
<h1> Assine nossa newsletter</h1>
<div class="button">
    <input type="email" placeholder="Digite seu e-mail"/>
<button> Inscrever-se </button>
</div>
</div>
</div>
    </footer>

</template>

<style scoped lang="scss">
.contact{
    display: flex;
    flex-direction: column;
    gap: 12px;
}
   .about {
    display: flex;
    flex-direction: column;
    gap: 12px;
    
   }
.footer{
    //border: solid;
    flex-wrap: wrap;
    display: flex;
    margin: 9rem;
    margin-top: 1rem;
    padding: 2rem;
    gap: 4rem;
}

button {
    width: 200px;
    height: 50px;
    background-color: #E1306C;
    border-radius: 8px;
    color: white;
    font-size: 16px;
    font-weight: 600;
    border: none;
    cursor: pointer;
    margin-top: 26px;
     &:hover {
        background-color: #c12761;
     }

    }

    input{
    
        width: 425px;
height: 50px;
        background-color: #FFFFFF;
border-radius: 5px;
        display: flex;
        flex-direction: column;
        border-radius: 8px;
        border: 2px solid #E1306C;
margin-top:  26px;


        &::placeholder{
            padding-left: 17px;
            font-size: 20px;
        width: 100%;
  padding: 14px 16px;
  font-size: 16px;
  color: #333;
            font-weight: 500;
        }
            

    }

    .novidades{
        display: flex;
        flex-direction: column;
        justify-content: center;
    
    }

</style>