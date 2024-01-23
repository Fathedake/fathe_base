<script setup lang="ts">

import { ref } from 'vue'

import Button from 'primevue/button';

const count = ref(0)

function increment() {
  count.value++
}
</script>

<template>
  <Button  @click="increment" label="Primary" rounded>  {{ count }} </Button>
</template>
