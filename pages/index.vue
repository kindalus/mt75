<script lang="ts"></script>

<script lang="ts" setup>
import amenities from "~~/model/data/amenities";
</script>

<template>
  <div>
    <hero />
    <div class="content p-8">
      <h1 class="text-xl font-bold text-center">Viver no MT75</h1>
      <div class="grid grid-cols-2 gap-4 my-8">
        <amenity
          v-for="a in amenities"
          :title="a.title"
          :description="a.description"
          :imgSrc="a.imgSrc"
        />
      </div>
    </div>
  </div>
</template>

<style lang="scss"></style>
