<template lang="html">
  <div class="modal-success">
    <i class="main-icon icon ion-md-checkmark"></i>
    <p class="main-text">בקשתך נקלטה בהצלחה</p>
    <button @click="$emit('close')" class="yes theme-button-outline">אישור</button>
  </div>
</template>
