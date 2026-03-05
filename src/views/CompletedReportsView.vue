<template>
  <ion-page>
    <AppHeader title="Uitgevoerde inspecties" />

    <ion-content class="recare-bg" fullscreen>
      <div class="completed-wrapper">
        <div class="placeholder-card">
          <p>Lijst uitgevoerde inspecties komt hier.</p>
        </div>
      </div>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonContent } from '@ionic/vue'
import AppHeader from '@/components/AppHeader.vue'
</script>

<style scoped>
.completed-wrapper {
  padding: 24px 16px;
}

.placeholder-card {
  background: #ffffff;
  border-radius: 16px;
  padding: 20px;
  box-shadow:
    0 10px 26px rgba(20, 27, 31, 0.08),
    0 2px 8px rgba(20, 27, 31, 0.06);
}
</style>
