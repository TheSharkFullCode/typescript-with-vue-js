<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>

  <h1 class="flex justify-center text-5xl">{{ msg }}</h1>

  <div class="card">
    
    <button type="button" @click="count++" class="border-[3px] rounded border-[pink] bg-[#53dcb5] p-5">count is {{ count }}</button>

  </div>


</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
