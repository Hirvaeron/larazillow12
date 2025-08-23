<script setup>
import { ref } from 'vue';
const counter = ref(0);
setInterval(() => counter.value++, 1000);
</script>
<template>
    <h1 class="text-3xl">Hello {{ counter }}!</h1>
</template>
