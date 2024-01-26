<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto flex items-center space-x-4 h-10 mb-10">
        <NuxtLink :to="{ name: 'a-empresa' }">Empresa</NuxtLink>
        <NuxtLink :to="{ name: 'servicos' }">Serviços</NuxtLink>
        <NuxtLink :to="{ name: 'produtos' }">Produtos</NuxtLink>
      </div>
    </div>
    <h1 class="text-lg font-bold">Serviços</h1>

    <NuxtLink to="/servicos/desenvolvimento-de-sites">Desenvolvimento De Sites</NuxtLink>
    <NuxtLink to="/servicos/marketing-digital">Marketing Digital</NuxtLink>
<br><br>
    <NuxtChild />

  </div>
</template>

<script>
  export default {
    name: '',
    data() {
      return {

      };
    },
    methods: {},

  };
</script>