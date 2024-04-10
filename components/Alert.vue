<template>
 <div class="bg-green-500 rounded px-2 py-1 text-white mb-2">
   {{props.msg}}
 </div>
</template>

<script setup lang="ts">
import { defineProps } from 'vue'
const props = defineProps<{
  msg: string
}>();
</script>
<style scoped></style>
