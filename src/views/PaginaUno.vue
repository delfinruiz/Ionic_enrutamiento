<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Pagina UNO</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content class="ion-padding">

      <p>Contenido de la pagina (1)</p>
      <br>
      <br>
      <ion-button router-link="/pagina2/hola ivan">Ir a Pagina DOS</ion-button>
    </ion-content>
  </ion-page>
</template>

<script setup>
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonButton } from '@ionic/vue';
</script>

<style scoped>

</style>
