<script setup>
//metodos
import Card from './Card.vue';
</script>

<template>
  <!--Estructura html-->
  <div class="container">

    <h1 class="text-center">MASCOTAS</h1>
    <!--iNICIO DEL PRIMER ROW-->
    <div class="row">
      <div class="col-md-6">
        <div class="card">
          <div class="card-header">
            <h6>GATOS</h6>
          </div>
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="card">
          <div class="card-header">
            <h6>PERROS</h6>
          </div>
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
    </div>
    <!-- CIERRE DEL PRIMER ROW -->
    <!--INICIO DEL SEGUNDO ROW-->
    <Card />
    <!--CIERRE DEL SEGUNDO ROW-->
    
  </div>
</template>

<style scoped>

</style>
