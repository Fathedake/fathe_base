<script setup lang="ts">

import { ref } from 'vue'

import Button from 'primevue/button';
import Card from 'primevue/card';

const count = ref(0)

function increment() {
  count.value++
}
</script>

<template>
  <Button  @click="increment" label="Primary" rounded>  {{ count }} </Button>

<Card style="width: 25em;margin-top:2px;">
  <template #content>
      <p class="m-0">
          Fathe
      </p>
  </template>
 
</Card>
</template>
