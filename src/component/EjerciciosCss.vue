<template>
  <!-- Ejemplo de selector de ID -->
  <h1 id="titulo">Ingredientes</h1>

  <!-- Ejemplo de selector de etiqueta -->
  <p id="parrafo-general">Lista de ingredientes esenciales para la receta.</p>

  <!-- Ejemplo de selector de clase -->
  <div class="contenedor-lista">
    <ul>
      <li class="ingrediente-faltante">Harina</li>
      <li class="ingrediente-presente">Aceite</li>
      <li class="ingrediente-presente">Leche</li>
      <li class="ingrediente-faltante">Sal</li>
    </ul>
  </div>

  <!-- Ejemplo de selector de hijo directo -->
  <div id="seccion-lista">
    <ul>
      <li>Azúcar</li>
      <li>Mantequilla</li>
    </ul>
  </div>

  <!-- Ejemplo de selector de descendiente -->
  <section id="zona-receta">
    <div>
      <p>Tiempo de preparación: 30 minutos</p>
    </div>
  </section>

  <!-- Ejemplo de selector de hermano adyacente -->
  <h2 id="subtitulo">Instrucciones</h2>
  <p id="primer-paso">Paso 1: Mezclar los ingredientes secos.</p>

  <!-- Ejemplo de selector de hermanos generales -->
  <h3 id="consejos">Consejos adicionales</h3>
  <p id="consejo-uno">Utiliza ingredientes frescos para mejores resultados.</p>
  <p id="consejo-dos">Prueba diferentes proporciones para ajustar el sabor.</p>
</template>

<style scoped>
/* Ejemplo de selector de ID */
#titulo {
  text-transform: uppercase;
  color: blue;
}

#parrafo-general {
  font-size: 16px;
  color: gray;
}

#seccion-lista > ul > li {
  font-weight: bold;
  color: darkblue;
}

#zona-receta p {
  color: darkgreen;
  font-style: italic;
}

#subtitulo + p {
  font-size: 18px;
  font-weight: bold;
}

#consejos ~ p {
  color: brown;
}

/* Ejemplo de selector de clase */
.ingrediente-faltante {
  color: red;
  font-weight: bold;
}

.ingrediente-presente {
  color: green;
  font-style: italic;
}

.contenedor-lista ul {
  border: 1px solid black;
  padding: 10px;
  background-color: #f8f8f8;
}

/* Ejemplo de selector universal */
* {
  font-family: Arial, sans-serif;
}

/* Ejemplo de selector de etiqueta */
p {
  margin-bottom: 10px;
}
</style>
