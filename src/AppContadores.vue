<template>
  <div class="contadores">
  <app-contador v-for="c in 5" :key="c" />
  </div>
</template>

<script>
import AppContador from './AppContador.vue'
  export default {
  components: { 'app-contador': AppContador }

 }

</script>

<style scoped>

 div{
      border: 1px solid red;
 }

</style>
