<template>
  <header>
    <h1>
      <img src="../assets/sidebar.jpg" alt="">
    </h1>
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'BarraLateral'
})

</script>

<style scoped>
header {
  background: #020202;
  width: 100%;
  height: 100vh;
}

@media only screen and (max-width: 768px) {
  header {
    padding: 2.5rem;
    height: auto;
  }
}
</style>