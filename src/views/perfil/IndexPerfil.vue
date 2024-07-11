<template>
    <ion-page>
      <ion-header>
        <ion-toolbar>
          <ion-title>Index</ion-title>
        </ion-toolbar>
      </ion-header>
  
      <ion-content class="ion-padding">
  
        <p>Index</p>
        <ion-router-outlet></ion-router-outlet>

      </ion-content>
    </ion-page>
  </template>
  
  <script setup>
  import { IonContent, IonHeader, IonPage, IonToolbar, IonRouterOutlet} from '@ionic/vue';

  </script>
  
  <style scoped>
  
  </style>