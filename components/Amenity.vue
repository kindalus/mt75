<script lang="ts" setup>
defineProps(["title", "description", "imgSrc"]);
</script>

<template>
  <div>
    <div class="h-20 flex justify-center">
      <img :src="imgSrc" alt="" class="h-full w-full object-cover" />
    </div>
    <div class="font-medium text-center">{{ title }}</div>
    <div class="text-sm">{{ description }}</div>
  </div>
</template>
