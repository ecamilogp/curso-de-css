<template>
  <div class="contenedor">
    <h1>Título Principal</h1>

    <!-- Herencia natural -->
    <section class="seccion">
      <p>Este párrafo hereda color y fuente del contenedor.</p>
      <span>Texto dentro de un <strong>span</strong> con herencia de color.</span>
    </section>

    <!-- Forzar herencia con inherit -->
    <div class="forzar-herencia">
      <p>Este div no heredaría fondo, pero lo forzamos con <strong>inherit</strong>.</p>
    </div>

    <!-- Reiniciar valores con initial -->
    <div class="resetear">
      <p>Este párrafo dentro de este div tiene color reiniciado con <strong>initial</strong>.</p>
    </div>

    <!-- Mezcla con unset -->
    <div class="unset">
      <p>Este párrafo usa <strong>unset</strong>, combinando herencia y valores por defecto.</p>
    </div>

    <!-- Aplicando all: initial para eliminar estilos -->
    <div class="eliminar-estilos">
      <p>Todos los estilos han sido eliminados con <strong>all: initial</strong>.</p>
    </div>

    <!-- Demostración con etiquetas extra -->
    <aside>
      <p>Esto es un aside con estilos propios, pero también usando herencia.</p>
    </aside>

    <footer>
      <p>Pie de página con estilo reiniciado.</p>
    </footer>
  </div>
</template>

<style scoped>
/* Herencia natural aplicada a los elementos dentro del contenedor */
.contenedor {
  color: rgb(1, 35, 98);
  font-family: 'Arial', sans-serif;
  font-size: 18px;
}

/* Forzar herencia en propiedades que no la tienen por defecto */
.forzar-herencia {
  background-color: inherit;
  color: inherit;
  padding: 10px;
  border: 2px solid black;
}

/* Restablecer valores a los predeterminados del navegador */
.resetear p {
  color: initial;
  font-size: initial;
  font-family: initial;
}

/* Aplicar unset para combinar herencia y valores por defecto */
.unset p {
  color: unset;
  font-weight: unset;
}

/* Eliminar todos los estilos aplicados */
.eliminar-estilos p {
  all: initial;
}

/* Estilos adicionales aplicados a otros elementos */
aside {
  background-color: lightgray;
  color: inherit;
  padding: 10px;
}

footer p {
  all: initial;
  color: black;
  font-family: sans-serif;
}
</style>
