<template>
  <ion-page>
    <h1>Grid en Ionic</h1>
    <ion-grid>
      <ion-row>
        <ion-col size="6">
          <div class="image-container">
            <img src="/rayo.png" alt="Rayo">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A necessitatibus quibusdam maxime eius sapiente atque nam voluptatum ut non culpa praesentium officia corporis, molestias voluptas reprehenderit laboriosam corrupti, illo maiores!</p>
          </div>
        </ion-col>
        <ion-col size="6">
          <div class="image-container">
            <img src="/mate.png" alt="Mate">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora recusandae sit nulla voluptates ab, laborum excepturi consequuntur eum esse! Earum, provident? Amet ratione accusantium non ipsa impedit, a odit ipsum?</p>
          </div>
        </ion-col>
      </ion-row>
    </ion-grid>
  </ion-page>
</template>

<script>

import { IonPage, IonGrid, IonRow, IonCol } from '@ionic/vue';

export default {
  name: 'HomePage',
  components: { IonPage, IonGrid, IonRow, IonCol }
}

</script>

<style>

.image-container{
  max-width: 100%;
  max-height: 100%;
  display: block;
  margin: auto;
  border: 1px solid black;
}

ion-grid{
  border: 1px solid red;
  
}

ion-row {
  border: 1px solid blue;
  padding: 50px;
}
ion-col {
  border: 1px solid green;
  padding: 50px;
  }
</style>
