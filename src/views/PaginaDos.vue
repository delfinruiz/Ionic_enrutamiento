<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Pagina DOS</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content class="ion-padding">

      <p>ontenido de la pagina (2)</p>
      <br>
      <br>
      <ion-button router-link="/pagina1">Ir a Pagina UNO</ion-button>
        <h1>Saludo: {{ $route.params.mensaje }}</h1>
    </ion-content>
  </ion-page>
</template>

<script setup>
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonButton } from '@ionic/vue';
</script>

<style scoped>

</style>
