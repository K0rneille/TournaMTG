<script setup>
  import FormCreate from '../components/Form.vue'


  const addPlayer = (name) => {
    console.log(name)
  }
</script>

<template>
  <main>

    <FormCreate @addPlayer = "addPlayer" />

  </main>
</template>
