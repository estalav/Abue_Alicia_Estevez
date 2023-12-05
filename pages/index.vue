<template>
  <div class="container">
    <div class="section links">
      <Nav />
    </div>
    <div class="section tribute">
      <!-- CONTENT START -->
      <h1 class="title">En Memoria y celebracion de la Abuela Alicia Estevez</h1>
      <img height="292" src="~/assets/frontimage.jpg" alt="In loving memory" />
      <div class="subtitle"><div class="name">{{ $config.name }}</div>{{ $config.dates }}</div>
      <!-- CONTENT END -->
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">

</style>
