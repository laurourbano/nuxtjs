import { NuxtLink } from '../.nuxt/components';
<template>
  <div>
    <header>
      <h1>Meu Site</h1>
      <navbar>
        <NuxtLink to="/">Página Inicial</NuxtLink>
        <NuxtLink to="/produtos">Produtos</NuxtLink>
      </navbar>
    </header>
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>
