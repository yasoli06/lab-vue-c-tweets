<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  image: {
    type: String,
    required: true,
  }
});

</script>


<template>
      <div>
        <img
      :src="image"
      class="profile"
      alt="profile"
    />
    </div>
</template>