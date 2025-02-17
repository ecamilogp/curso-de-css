<template>
  <div class="container">
    <h1>Ejemplo de Media Queries</h1>
    <div class="contenedor">
      <div class="caja">Caja 1</div>
      <div class="caja">Caja 2</div>
    </div>
  </div>
</template>

<style scoped>
.container {
  min-height: 100vh;
  background: lightblue;
  padding: 20px;
  text-align: center;
}

h1 {
  font-size: 24px;
  font-weight: bold;
}

.contenedor {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.caja {
  background: white;
  padding: 20px;
  border-radius: 5px;
  width: 100%;
}

@media (min-width: 768px) {
  .contenedor {
    flex-direction: row;
    justify-content: center;
  }
  .caja {
    width: 45%;
  }
}

@media (min-width: 1024px) {
  .caja {
    width: 30%;
  }
}
</style>
