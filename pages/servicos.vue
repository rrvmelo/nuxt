<template>
  <div>
        <h1 class="text-lg font-bold">Servicos</h1>
        <NuxtLink to="/servicos/desenvolvimento-de-sites">Desevolvimento de Sites</NuxtLink>
        <NuxtLink to="/servicos/marketing-digital">Marketing Digital</NuxtLink>
        <br><br>
        <NuxtChild />
      </div>
</template>

<script>
export default {
  name: 'servicos'
}
</script>
