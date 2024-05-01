<script setup lang="ts">
function onItemInteraction(e: MouseEvent | Event) {}
</script>

<template>
  <div v-on="{ click: onItemInteraction, keydown: onItemInteraction }"></div>
</template>
