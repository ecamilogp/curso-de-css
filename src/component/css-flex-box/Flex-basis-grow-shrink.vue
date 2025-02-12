<template>
  <div class="contenedor">
    <div class="item item1">1</div>
    <div class="item item2">2</div>
    <div class="item item3">3</div>
  </div>
</template>

<style scoped>
.contenedor {
  display: flex;
  width: 100%;
  height: 100px;
  border: 2px solid black;
  background-color: lightgray;
}

.item {
  color: white;
  text-align: center;
  font-size: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 10px;
}

.item1 {
  flex-basis: 100px; /* Tamaño inicial */
  flex-grow: 5; /* Crece 5 parte */
  flex-shrink: 1; /* Se encoge normalmente */
  background-color: blue;
}

.item2 {
  flex-basis: 100px;
  flex-grow: 4; /* Crece 4 partes (más grande) */
  flex-shrink: 3; /* Se encoge más rápido */
  background-color: red;
}

.item3 {
  flex-basis: 100px;
  flex-grow: 3; /* Crece 3 parte */
  flex-shrink: 2;
  background-color: green;
}
</style>
