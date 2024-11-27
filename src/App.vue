<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div>
    <h1>Hello App!</h1>
    <nav>
      <RouterLink to="/">Go to Home</RouterLink>
      <RouterLink to="/about">Go to About</RouterLink>
    </nav>
    <main>
      <RouterView />
    </main>
  </div>
</template>

<style scoped></style>
