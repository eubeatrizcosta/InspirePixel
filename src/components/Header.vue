<script setup>
import { Icon } from "@iconify/vue";
import logo from '../assets/logo.png';


</script>

<template>
<header>
    <a href="">
        <img :src="logo" alt="Logo Inspire Pixel">
        <Icon class="logo" icon="material-symbols:logo" />
    </a>
   <nav>
    <ul>
    <li>
        <a href="">
            <img :src="pesquisa" alt="">
            <Icon class="search-icon" icon="material-symbols:search" width="40"/> 
            <!-- <Icon icon="coleção:nomeDoIconeEmIngles" -->
        </a>
    </li>
    <li>
        <a href="">Início</a>
    </li>
    <li>
        <a href="">Galeria</a>
    </li>
    <li>
        <a href=""> Favoritos</a>
    </li>
    <li>
        <a href="">
            <img :src="pessoa" alt="">
            <Icon class="user-icon" icon="material-symbols:person" width="40"/>
        </a>
    </li>
    </ul>
   </nav>
</header>
</template>

<style scoped lang="scss">


header{
    //border: solid;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    margin: 9rem;
    margin-top: 1rem;
padding: 2rem;
} 
ul {
      display: flex;
        gap: 64px;
       // border: solid;
        flex-wrap: wrap;
        list-style: none;
        align-items: center;
        
}

    a{
        text-decoration: none;
        color: black;
        font-weight: 500;
        font-size: 24px;
    }
.user-icon, .search-icon{
    color: pink;
}
</style>