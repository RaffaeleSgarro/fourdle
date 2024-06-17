<script setup lang="ts">
const props = defineProps({
    letter: String
});
</script>
<template>
    <div class="Key">{{ props.letter }}</div>
</template>
<style scoped>
.Key {
    font-size: 2em;
    font-weight: bold;
    margin: 0.5em;
    padding: 0.5em;
    border: 1px solid black;
    display: inline-block;
    text-align: center;
    width: 1.5em;
    height: 1.5em;
    line-height: 1.5em;
    border-radius: 0.5em;
    background-color: lightblue;
    color: white;
}
</style>