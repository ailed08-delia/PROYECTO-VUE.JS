<template>
    <div class="card-header">
      <div class="title-container">
        <h2>Status Diario de Flota Nacional</h2>
      </div>
      <div class="logo-container">
        <img alt="Marvisur logo" class="logo" src="@/assets/flota.jpg" width="180" height="81" />
      </div>
    </div>
  </template>
  
  <script lang="ts" setup>
  // Aquí puedes agregar lógica adicional si es necesario
  </script>
  
  <style scoped>
  .card-header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
    background-color: #ffffff; /* Fondo blanco */
    color: #7f0000; /* Color de texto rojo para el título */
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 2em;
    padding: 10px 20px; /* Ajusta el padding para espacio interno */
    border-bottom: 2px solid #7f0000; /* Borde rojo en la parte inferior */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Sombra suave */
    box-sizing: border-box; /* Ajusta el modelo de caja para incluir el padding en el ancho total */
  }
  
  .title-container {
    flex: 1; /* Ocupa el espacio restante */
  }
  
  .logo-container {
    margin-left: 20px; /* Agrega espacio entre el título y la imagen */
  }
  
  .logo {
    width: 165px; /* Ancho de la imagen */
    height: 56px; /* Alto de la imagen */
  }
  
  h2 {
    font-weight: bold; /* Texto en negrita */
    margin: 0; /* Elimina el margen predeterminado del título */
    color: #7f0000; /* Color rojo */
  }
  </style>
  
