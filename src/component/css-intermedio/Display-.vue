<template>
  <h1>Elementos en bloque con uso de display block</h1>
  <div>Contenedor 1 uso de display block</div>
  <div>Contenedor 2 uso de display block</div>
  ---------------------------------------------
  <h1>Uso de display inline</h1>
  <strong>
    Aquí los pone en una sola línea y ocupa solo el espacio necesario, no deja modificar la altura
    ni el ancho.
  </strong>
  <br /><br />
  <div class="inline">Uso de display inline 1</div>
  <div class="inline">Uso de display inline 2</div>
  <br /><br />
  ---------------------------------------------
  <h1>Uso de inline-block</h1>
  <p>
    <strong
      >Esta es muy similar a inline, pero sí deja cambiar el alto y el ancho de su
      contenedor.</strong
    >
  </p>
  <div class="inline-block">Prueba con inline-block 1</div>
  <div class="inline-block">Prueba con inline-block 2</div>
  <br /><br />
  ---------------------------------------------
  <h1>Uso de display flex</h1>
  <p>
    <b>
      Este método convierte un elemento en un contenedor flexible y permite una distribución más
      dinámica.
    </b>
  </p>

  <h2>Flex con justify-content: baseline</h2>
  <div class="flex flex--baseline">
    <div>Uso de flex 1</div>
    <div>Uso de flex 2</div>
    <div>Uso de flex 3</div>
    <div>Uso de flex 4</div>
  </div>

  <h2>Flex con justify-content: center</h2>
  <div class="flex flex--center">
    <div>Uso de flex 1</div>
    <div>Uso de flex 2</div>
    <div>Uso de flex 3</div>
    <div>Uso de flex 4</div>
  </div>

  <h2>Flex con justify-content: end</h2>
  <div class="flex flex--end">
    <div>Uso de flex 1</div>
    <div>Uso de flex 2</div>
    <div>Uso de flex 3</div>
    <div>Uso de flex 4</div>
  </div>

  <h2>Flex con justify-content: space-around</h2>
  <div class="flex flex--around">
    <div>Uso de flex 1</div>
    <div>Uso de flex 2</div>
    <div>Uso de flex 3</div>
    <div>Uso de flex 4</div>
  </div>

  <h2>Flex con justify-content: space-between</h2>
  <div class="flex flex--between">
    <div>Uso de flex 1</div>
    <div>Uso de flex 2</div>
    <div>Uso de flex 3</div>
    <div>Uso de flex 4</div>
  </div>

  <h2>Flex con justify-content: space-evenly</h2>
  <div class="flex flex--evenly">
    <div>Uso de flex 1</div>
    <div>Uso de flex 2</div>
    <div>Uso de flex 3</div>
    <div>Uso de flex 4</div>
  </div>

  <h2>uso de display grid</h2>
  <div class="grid">
    <img src="../../assets/yotas.jpg" alt="" /><img src="../../assets/yotas.jpg" alt="" /><img
      src="../../assets/yotas.jpg"
      alt=""
    /><img src="../../assets/yotas.jpg" alt="" />
  </div>

  <h2>uso de display none</h2>
  <p class="oculto">Este texto está oculto</p>
</template>

<style scoped>
div {
  display: block;
  background-color: aqua;
  margin: 10px;
  border: 2px solid black;
}

.inline {
  display: inline;
  background-color: red;
  color: white;
}

.inline-block {
  display: inline-block;
  background-color: blue;
  color: white;
  width: 100px;
  height: 100px;
}

.flex {
  display: flex;
  background-color: lightgray;
  margin: 10px 0;
}

.flex--baseline {
  justify-content: baseline;
}

.flex--center {
  justify-content: center;
}

.flex--end {
  justify-content: end;
}

.flex--around {
  justify-content: space-around;
}

.flex--between {
  justify-content: space-between;
}

.flex--evenly {
  justify-content: space-evenly;
}

img {
  width: 200px;
  height: 200px;
  border: 2px solid red;
}

.grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
}

.oculto {
  display: none;
  font-size: 30px;
  font-weight: bold;
}
</style>
