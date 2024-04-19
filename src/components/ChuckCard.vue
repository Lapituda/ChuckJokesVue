<template>
  <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
    <div class="card h-100">
      <img :src="iconUrl" class="card-img-top" alt="Chuck Norris Icon">
      <div class="card-body">
        <p class="card-text">{{ value }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    iconUrl: String,
    value: String
  }
};
</script>

<style scoped>
/* Agrega estilos personalizados aquí si es necesario */
</style>
