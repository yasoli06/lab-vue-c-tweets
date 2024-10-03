<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  message: {
    type: String,
    required: true,
  }
});

</script>

<template>
    <div>
        <p class="message">{{ message }}</p>
    </div>
</template>

<style scoped>
</style>