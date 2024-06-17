<script setup lang="ts">
import Word from './components/Word.vue';
import Keyboard from './components/Keyboard.vue';
</script>

<template>
  <div id="Words">
    <Word />
    <Word />
    <Word />
    <Word />
  </div>
  <Keyboard />
</template>

<style scoped>
/* Display frames in 2 x 2 grid */
#Words {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1em;
}
</style>