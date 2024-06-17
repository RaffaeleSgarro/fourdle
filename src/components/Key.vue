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
    font-size: 1em;
    font-weight: bold;
    margin: 0.1em;
    padding: 0.1em;
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