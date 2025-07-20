<template>
  <div class="card">
    <h2>{{ name }}</h2>
    <p>Szint: {{ level }}</p>
    <p>Reset: {{ reset }}</p>
  </div>
</template>

<script>
export default {
  name: 'CharacterCard',
  props: {
    name: String,
    level: Number,
    reset: Number
  }
}
</script>

<style scoped>
.card {
  color: #00ffcc;
  font-family: Arial, sans-serif;
  padding: 1rem;
  border: 2px solid #00ffcc;
  border-radius: 8px;
  width: fit-content;
  margin: 2rem auto;
  background-color: #1a1a1a;
}
</style>
