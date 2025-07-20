<template>
  <CharacterCard name="DarkKnight" :level="100" :reset="5" />
  <CharacterCard name="FairyElf" :level="100" :reset="5" />
  <CharacterCard name="SoulMaster" :level="100" :reset="5" />
  <CharacterCard name="MagicGladiator" :level="100" :reset="5" />
</template>

<script setup>
import CharacterCard from './components/CharacterCard.vue'
</script>

<style scoped>
.character-card {
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
