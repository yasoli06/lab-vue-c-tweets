<script setup>
  import { defineProps } from 'vue';

  const props = defineProps({
    userData: {
      type: Object,
      required: true
    }
  })
</script>

<template>
   <div>
        <span class="user">
          <span class="name">{{ userData.name }}</span>
          <span class="handle">{{ userData.handle }}</span>
        </span>
    </div>
</template>

<style scoped>
</style>