<script setup>
import { RouterLink, RouterView } from 'vue-router'



// player logic 

class player{
  constructor(name){
    this.name = name;

    this.score = 0;
    this.getScore = ()=> {
      return score
    }
    this.delete = ()=>{
      this = null;
    }
    
  }
}

AllPlayers = [];


</script>

<template>
  <header>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
  </header>

  <RouterView />


</template>

<style scoped> 


</style>
