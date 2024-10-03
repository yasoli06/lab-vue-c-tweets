<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  time: {
    type: String,
    required: true,
  }
});

</script>


<template>
    <div>
        <span class="timestamp">{{ time }}</span>
    </div>
</template>