<template>
  <div>
    <h1>Detalhes do Produto {{ idParams }}</h1>

    <p>Nome: Produto 1</p>
    <p>Preço: R$ 100,00</p>
    <p>Descrição: Descrição do produto 1</p>

    <NuxtLink to="/produtos">Voltar</NuxtLink>
  </div>
</template>

<script setup>
const route = useRoute()
const idParams = route.params.id
</script>

<style lang="scss" scoped></style>
