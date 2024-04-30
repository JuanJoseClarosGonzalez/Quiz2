<template>
            <InputComponent id="id" name="id" type="hidden"/>
            <InputComponent type="number" id="Codigo" name="Codigo" label="Codigo: " />
            <InputComponent id="nombre" name="nombre" label="Nombre: " />
            <InputComponent id="descripcion" name="descripcion" label="Descripcion: " />
            <InputComponent id="estado" name="estado" label="Estado: " />
  </template>
  
  <script setup lang="ts">
  import InputComponent from './InputComponent.vue';
  </script>
  
  <style scoped src="../theme/container.css"></style>