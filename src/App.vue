<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/featured">Featured</RouterLink>
    </nav>
  </header>
  <RouterView />
</template>

<style lang="sass" scoped>
  nav
    display: flex
    align-items: center
    gap: 1rem
    padding: 1rem
</style>