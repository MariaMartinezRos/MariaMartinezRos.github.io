<script setup lang="ts">
import { R } from 'vue-router/dist/router-CWoNjPRp.mjs'
</script>

<template>
  <div class="flex flex-col items-center justify-center gap-4">
    <h1 class="text-4xl font-bold">Index</h1>
    <p class="text-lg text-gray-600">Welcome to the landing page of this application.</p>
    <RouterLink :to="{ name: '/HomeView' }"> Go Back Home </RouterLink>
    <RouterLink :to="{ name: '/dev/' }"> Developer tools </RouterLink>
    <RouterLink :to="{ name: '/dev/', params: { Hola: 'gallery' } }"> Gallery </RouterLink>
    <RouterLink :to="{ name: '/cv/' }"> Contact me </RouterLink>
    <RouterLink :to="{ name: '/art/' }"> Art Gallery </RouterLink>
  </div>
</template>
