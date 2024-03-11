<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
    <div>
      <RouterLink to="/servicos"> Servicos </RouterLink>
      <RouterLink to="/sobre"> Quem Somos </RouterLink>
    </div>
    <div>
      <img src="/logo.png">
      <RouterLink to="/"> micro floripa </RouterLink>
    </div>
    <div>
      <RouterLink to="/planos"> Planos </RouterLink>
      <RouterLink to="/contato"> Contato </RouterLink>
    </div>
  </nav>
  <RouterView />
</template>
