import { NuxtLink } from '../../.nuxt/components';
<template>
  <div>
    <h1>Produtos</h1>
    <NuxtLink to="/produtos/${idParams}">Detalhes</NuxtLink>
  </div>
</template>

<script setup>
const route = useRoute()
const idParams = route.params.id
</script>

<style lang="scss" scoped></style>
