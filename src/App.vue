<template>
  <router-view />
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App'
})
</script>


<style>
body {
  background: url('./assets/GreenBankLandingPage.jpg');
  background-size: cover;
  /* This will cover the entire element */
  background-repeat: no-repeat;
  /* This will fix the background image */
  height: 824px;
  /* Ensure it covers the full screen */
  min-width: 100%;

}
</style>
