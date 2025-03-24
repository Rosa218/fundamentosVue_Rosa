<script setup>
// importaci[on del primer card
//metodos
import Card from './Card.vue';
//importacion del cardPrincipal
import CardPrincipal from './CardPrincipal.vue';
</script>

<template>
  <!--Estructura html-->
  <div class="container">

    <h1 class="text-center">MASCOTAS</h1>
    <!--iNICIO DEL PRIMER ROW-->
    <CardPrincipal />
    <!-- CIERRE DEL PRIMER ROW -->
    <!--INICIO DEL SEGUNDO ROW-->
    <Card />
    <!--CIERRE DEL SEGUNDO ROW-->
    
  </div>
</template>

<style scoped>

</style>
