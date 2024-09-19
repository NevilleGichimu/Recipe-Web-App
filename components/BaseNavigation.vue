<script setup lang="ts"></script>

<template>
  <header class="py-4 border-b">
    <nav class="flex container items-center">
      <NuxtLink to="/" class="flex gap-1 items-center">
        <img width='56px', densities="x1" src="../assets/icon-green.png" format="webp" alt="" />
        <span class="text-3xl font-bold">Recipes</span>
      </NuxtLink>
      <ul class="flex gap-6 ml-auto text-xl font-bold capitalize">
        <li>
         <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">About</NuxtLink>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped></style>