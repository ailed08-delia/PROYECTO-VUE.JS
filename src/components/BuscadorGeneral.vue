<template>
    <div class="form-group row">
      <label for="placa" class="col-sm-2 col-form-label">Placa:</label>
      <div class="col-sm-8">
        <input type="text" class="form-control" id="placa" value="AEK-829">
      </div>
      <div class="col-sm-2">
        <button @click="buscarPlaca">Buscar</button>
      </div>
    </div>
  </template>
  
  <script lang="ts" setup>
  function buscarPlaca() {
    // Lógica para buscar placa
  }
  </script>
  
  <style scoped>
  .form-group {
    display: flex;
    align-items: center;
    margin: 10px 0;
  }
  
  .form-group .col-sm-2 {
    flex: 1;
  }
  
  .form-group .col-sm-8 {
    flex: 4;
  }
  
  .form-group .col-sm-2 button {
    flex: 1;
    margin-left: 10px;
    padding: 10px 20px;
    border: none;
    background-color: #0F2C67;
    color: #fff;
    border-radius: 4px;
    cursor: pointer;
    font-size: 14px;
    height: 40px;
  }
  
  .form-group input {
    width: 100%;
    padding: 10px;
    border-radius: 4px;
    border: 1px solid #ccc;
    box-sizing: border-box;
  }
  </style>
  
  