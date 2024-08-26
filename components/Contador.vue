<script setup>
import { ref } from 'vue'

const contador = ref(0)
</script>

<template>
<h1>El contador es: {{ contador }}</h1>
<UCard>
  <UButton @click="contador++">Incrementar</UButton>
  <UButton @click="contador--">Decrementar</UButton>
</UCard>
</template>