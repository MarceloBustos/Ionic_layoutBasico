<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>Inicio</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content class="ion-padding">
            <p><b>La pelicula de Cars</b> Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam alias,
                asperiores sapiente corrupti quis harum temporibus fuga sunt! Aspernatur sunt non cupiditate neque fugit
                repudiandae aperiam reiciendis a dolorum voluptas.</p>
        </ion-content>

        <ion-footer>
            <ion-toolbar>
                <ion-title class="ion-text-center">
                    @copy Mabo Soft
                </ion-title>
            </ion-toolbar>
        </ion-footer>
    </ion-page>
</template>

<script>
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonFooter } from '@ionic/vue';

export default {
    name: 'Inicio',
    components: {
        IonPage,
        IonHeader,
        IonToolbar,
        IonTitle,
        IonContent,
        IonFooter
    }
}
</script>

<style>
p {
    font-size: 18px;
    text-align: justify;
    color: lightseagreen;
}
</style>