<template>
  <input
    class="container block mx-auto rounded-full mt-8 text-2xl text-center p-2 outline-none focus:ring-4 focus:ring-green-500 focus:ring-opactiy-50"
    type="text"
    placeholder="I'm looking for..."
    v-model="searchItem"
    @change="getGifs"
  />
</template>

<script setup>
import { searchItem, getGifs } from "../helpers/useGifs";
</script>
