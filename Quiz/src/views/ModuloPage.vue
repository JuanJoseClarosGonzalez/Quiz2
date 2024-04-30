<template>
    <ion-page>
      <ion-header :translucent="true">
        <ion-toolbar>
          <ion-title>Modulo</ion-title>
        </ion-toolbar>
      </ion-header>  
      <ion-content>       
        <div id="login-container">  
          <div id="login-form">
          <DatosComponent/>     
          <InputComponent id="ruta" name="ruta" label="Ruta: " />  
          </div>
  
          <div> 
             <!--Traer el componente de los botones de la crud  -->
            <CrudButtonComponent />
          </div>          
        </div>
      </ion-content>
    </ion-page>
  </template>
  
  <script setup lang="ts">
  import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
  import ButtonComponent from '@/components/ButtonComponent.vue';
  import InputComponent from '@/components/InputComponent.vue';
  import CrudButtonComponent from '@/components/CrudButtonComponent.vue';
import DatosComponent from '@/components/DatosComponent.vue';
  </script>
  
  <style scoped src="../theme/container.css"></style>

