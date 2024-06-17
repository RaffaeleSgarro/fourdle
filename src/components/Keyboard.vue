<script setup lang="ts">
import Key from './Key.vue';
</script>
<template>
    <div class="Keyboard">
        <div>
            <Key :letter="'Q'" />
            <Key :letter="'W'" />
            <Key :letter="'E'" />
            <Key :letter="'R'" />
            <Key :letter="'T'" />
            <Key :letter="'Y'" />
            <Key :letter="'U'" />
            <Key :letter="'I'" />
            <Key :letter="'O'" />
            <Key :letter="'P'" />
        </div>
        <div>
            <Key :letter="'A'" />
            <Key :letter="'S'" />
            <Key :letter="'D'" />
            <Key :letter="'F'" />
            <Key :letter="'G'" />
            <Key :letter="'H'" />
            <Key :letter="'J'" />
            <Key :letter="'K'" />
            <Key :letter="'L'" />
        </div>
        <div>
            <Key :letter="'Z'" />
            <Key :letter="'X'" />
            <Key :letter="'C'" />
            <Key :letter="'V'" />
            <Key :letter="'B'" />
            <Key :letter="'N'" />
            <Key :letter="'M'" />
        </div>
    </div>
</template>
<style scoped>
.Keyboard {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 1em;
}
</style>