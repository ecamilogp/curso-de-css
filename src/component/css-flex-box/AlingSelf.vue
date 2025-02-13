<template>
  <div class="contenedor">
    <div class="item">Item 1</div>
    <div class="item self-center">Item 2 (Centrado)</div>
    <div class="item self-flex-end">Item 3 (Final)</div>
  </div>
</template>

<style scoped>
.contenedor {
  display: flex;
  flex-direction: row; /* Eje principal en horizontal */
  align-items: flex-start; /* Todos los elementos se alinean arriba por defecto */
  height: 200px;
  background-color: lightgray;
}

.item {
  width: 100px;
  padding: 10px;
  background-color: steelblue;
  color: white;
  text-align: center;
  margin: 5px;
}

.self-center {
  align-self: center; /* Se alinea en el centro verticalmente */
}

.self-flex-end {
  align-self: flex-end; /* Se alinea en la parte inferior */
}
</style>
