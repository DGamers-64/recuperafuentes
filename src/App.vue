<template>
  <div class="contenedor-principal">
    <Header />
    <main class="contenido">
      <router-view />
    </main>
    <Footer />
  </div>
</template>

<script setup>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
</script>

<style>
.contenedor-principal {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    width: 80%;
    margin: auto;
}

.contenido {
    flex: 1;
}
</style>