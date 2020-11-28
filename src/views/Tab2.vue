<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Apps</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Apps</ion-title>
        </ion-toolbar>
      </ion-header>
            <ion-item button @click="testClick()" href="intent://com.google.android.googlequicksearchbox/#Intent;scheme=android-app;end">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/google.jpg">
              </ion-avatar>
              <ion-label >
                Google Now
              </ion-label>
            </ion-item>
            <ion-item button @click="testClick()" href="intent://com.android.settings/#Intent;scheme=android-app;end">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/setting.png">
              </ion-avatar>
              <ion-label >
                Open Setting
              </ion-label>
            </ion-item>
            <ion-item button @click="testClick()" href="https://caaqilyare.github.io/globalsetup/file/Apex_Launcher.apk">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/apex.jpg">
              </ion-avatar>
              <ion-label >
                Apex Launcher
              </ion-label>
            </ion-item>
            <ion-item button @click="testClick()" href="https://caaqilyare.github.io/globalsetup/file/Android_5_GAM.apk">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/google5.jpg">
              </ion-avatar>
              <ion-label >
                Google Account Manager 5
              </ion-label>
            </ion-item>
            <ion-item button @click="testClick()" href="https://caaqilyare.github.io/globalsetup//file/Android_6_GAM.apk">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/google6.png">
              </ion-avatar>
              <ion-label >
                Google Account Manager 6
              </ion-label>
            </ion-item>

            <ion-item button @click="testClick()" href="https://caaqilyare.github.io/globalsetup//file/Google_Setting.apk">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/t.png">
              </ion-avatar>
              <ion-label >
                Technocare
              </ion-label>
            </ion-item>
            <ion-item button @click="testClick()" href="https://caaqilyare.github.io/globalsetup//file/QuickShortcutMaker.apk">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/q.png">
              </ion-avatar>
              <ion-label >
                Quick Short Maker
              </ion-label>
            </ion-item>
            <ion-item button @click="testClick()" href="https://caaqilyare.github.io/globalsetup//file/FRP_Bypass.apk">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/log.png">
              </ion-avatar>
              <ion-label >
                By Bass Frp Login
              </ion-label>
            </ion-item>
            <ion-item button @click="testClick()" href="https://caaqilyare.github.io/globalsetup//file/Menu Button No root_v5.3_apkpure.com.apk">
              <ion-avatar slot="start">
              <img src="https://caaqilyare.github.io/globalsetup/img/menu.png">
              </ion-avatar>
              <ion-label >
                Menu Button
              </ion-label>
            </ion-item>
    

    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';

export default  {
  name: 'Tab2',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
}
</script>