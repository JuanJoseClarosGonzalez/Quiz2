<template>
    <ion-page>
      <ion-header :translucent="true">
        <ion-toolbar>
          <ion-title>Rol</ion-title>
        </ion-toolbar>
      </ion-header>  
      <ion-content>       
        <div id="login-container">  
          <div id="login-form">
            <DatosComponent/>
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

