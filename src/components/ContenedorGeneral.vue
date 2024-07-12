<template>
    <div class="app-content">
      <TituloPrincipalVue />
      <div class="card">
        <BuscadorGeneralVue />
      </div>
    </div>
  </template>
  
  <script lang="ts" setup>
 import ContenedorGeneral  from "./ContenedorGeneral.vue";
 import TituloPrincipalVue from "./TituloPrincipal.vue";
  </script>
  
  <style scoped>
  .app-content {
    margin-top: 120px; /* Ajusta este valor según la altura de tu título */
    padding: 20px;
  }
  
  .card {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 4px;
    padding: 20px;
    margin-top: 20px; /* Espacio entre el título y el buscador */
  }
  </style>
  
  
  