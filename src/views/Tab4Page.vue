<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 4</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 4</ion-title>
        </ion-toolbar>
      </ion-header>

<ion-content fullscreen>
        <ion-card>
          <img src="https://scontent-sin6-1.xx.fbcdn.net/v/t1.6435-9/110320079_678019732751735_1561759245512041012_n.jpg?_nc_cat=111&ccb=1-5&_nc_sid=174925&_nc_ohc=lHXCHPIlD0UAX_eyk7K&_nc_ht=scontent-sin6-1.xx&oh=00_AT-hVNPYrdu2GC9uVlZoWn1CjTOeOK9IiipM5IluUkW0hg&oe=624BC685" />
          <ion-card-header>
            
            <ion-card-title>ณัฐดนัย ทินกร </ion-card-title>
          </ion-card-header>
          <ion-card-content>
            รหัสนักศึกษา : 62442206004-3
<ion-card-subtitle>เบอร์โทร : 0938411918</ion-card-subtitle>
           

          </ion-card-content>
        </ion-card>
      </ion-content>
      
      <ExploreContainer name="" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';


export default defineComponent({
  name: 'Tab4Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});


</script>
