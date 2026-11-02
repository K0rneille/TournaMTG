<script setup>

defineEmits(['addPlayer'])

import { ref } from 'vue';

const playerName = ref("") ;

</script>

<template>

    <form action="" @submit.prevent="$emit( 'addPlayer', playerName)">

        <label for="name">nom : {{ playerName }} </label>
        <input type="text" id="name" name="name" autofocus placeholder="name" v-model="playerName" >
        <button type="submit">
            
            submit
        
        
        </button>

        
    </form>



</template>


<style scoped lang="scss"></style>