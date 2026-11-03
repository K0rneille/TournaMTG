<script setup>
  import FormCreate from '../components/Form.vue'


  const addPlayer = (name) => {
     allPlayers
  }
</script>

<template>
  <main>

    <FormCreate @addPlayer = "addPlayer" />

  </main>
</template>
