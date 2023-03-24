<script setup>
import { ref } from 'vue'
const contador1 = ref(0)
const contador2 = ref(0)
</script>
<template>
  <div class="container">
    <button class="btn btn-primary">OK</button>
    <div class="mt-4">
      <div>
        <button class="btn btn-primary" @click="contador1--">-</button>
        <span class="mx-3 fs-4">{{ contador1 }}</span>
        <button class=" btn btn-primary" @click="contador1++">+</button>
      </div>
      <div>
        <button class="btn btn-dark" @click="contador2--">-</button>
        <span class="m-3 fs-4">{{ contador2 }}</span>
        <button class="btn btn-dark" @click="contador2++">+</button>
      </div>
    </div>
  </div>
</template>
