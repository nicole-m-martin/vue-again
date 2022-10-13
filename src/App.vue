<template>
  <div>
    <ul>
      <li><RouterLink :to="{ name: 'home' }">Home</RouterLink></li>
      <li><RouterLink :to="{ name: 'about' }">About</RouterLink></li>
    </ul>
  </div>
  <router-view />
</template>

<script setup>
import { RouterView } from 'vue-router';
</script>
