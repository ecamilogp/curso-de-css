<template>
  <div class="container">
    <h1>Ejemplos de Media Queries</h1>
    <p class="responsive-text">Este texto cambia de tamaño en diferentes pantallas.</p>
  </div>
</template>

<style scoped>
/* ✅ Estilos generales */
.container {
  padding: 20px;
  text-align: center;
}

/* ✅ Cambia el color de fondo para pantallas menores a 600px */
@media (max-width: 600px) {
  .container {
    background-color: lightblue;
  }
}

/* ✅ Cambia el tamaño del texto para pantallas mayores a 1024px */
@media (min-width: 1024px) {
  .responsive-text {
    font-size: 24px;
    color: darkblue;
  }
}

/* ✅ Media queries combinadas (Rango de pantalla) */
@media (min-width: 600px) and (max-width: 1024px) {
  .container {
    background-color: lightcoral;
  }
}

/* ✅ Detectar orientación de pantalla (modo retrato) */
@media (orientation: portrait) {
  .container {
    border: 5px solid black;
  }
}

/* ✅ Detectar dispositivos con pantalla Retina */
@media (-webkit-min-device-pixel-ratio: 2), (min-resolution: 192dpi) {
  .responsive-text {
    font-weight: bold;
  }
}
</style>
