<template>
  <div class="container">
    <!-- Flex Direction: Row -->
    <div class="flex-row">
      <div class="box">Elemento 1</div>
      <div class="box">Elemento 2</div>
      <div class="box">Elemento 3</div>
    </div>

    <!-- Flex Direction: Column -->
    <div class="flex-column">
      <div class="box">Uno</div>
      <div class="box">Dos</div>
      <div class="box">Tres</div>
    </div>

    <!-- Flex Wrap -->
    <div class="flex-wrap">
      <div class="box">caja 1</div>
      <div class="box">caja 2</div>
      <div class="box">caja 3</div>
      <div class="box">caja 4</div>
      <div class="box">caja 5</div>
      <div class="box">caja 6</div>
    </div>

    <!-- Flex Flow -->
    <div class="flex-flow">
      <div class="box">7</div>
      <div class="box">6</div>
      <div class="box">8</div>
      <div class="box">9</div>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  gap: 20px;
  padding: 20px;
  background-color: #f3f3f3;
}

/* Flex Direction: Row */
.flex-row {
  display: flex;
  flex-direction: row;
  gap: 10px;
  background: #3498db;
  padding: 15px;
  border-radius: 10px;
}

/* Flex Direction: Column */
.flex-column {
  display: flex;
  flex-direction: column;
  gap: 10px;
  background: #2ecc71;
  padding: 15px;
  border-radius: 10px;
}

/* Flex Wrap */
.flex-wrap {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  background: #f39c12;
  padding: 15px;
  border-radius: 10px;
}

/* Flex Flow */
.flex-flow {
  display: flex;
  flex-flow: row wrap;
  gap: 10px;
  background: #8e44ad;
  padding: 15px;
  border-radius: 10px;
}

/* Estilos de los elementos */
.box {
  background: white;
  color: black;
  padding: 12px 16px;
  border-radius: 8px;
  text-align: center;
  font-weight: bold;
  min-width: 80px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease-in-out;
}

.box:hover {
  transform: scale(1.05);
}
</style>
