<script setup lang="ts">
import { ref } from 'vue';
import Letter from './Letter.vue';
const maxAttempts = ref(9);
const wordLength = ref(5);
</script>
<template>
    <div class="Word">
        <div class="Attempt" v-for="attemptIndex in maxAttempts" :key="attemptIndex">
            <div v-for="letterIndex in wordLength" :key="letterIndex">
                <Letter />
            </div>
        </div>
    </div>
</template>
<style scoped>
.Word {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.Attempt {
    display: flex;
    justify-content: center;
    margin: 0;
}
</style>