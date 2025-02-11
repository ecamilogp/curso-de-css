<template>
  <!-- pero aqui la que mas relevancia tiene es style ya que al ser un selector en linea
   su valor es de 1000 puntos y se sobrepone sobre las demas  -->
  <p class="miClase" id="miID" style="color: orange">hola mundo</p>

  <!-- aqui aplicamos el uso de important lo que omite el puntaje de especificidad
  por lo tanto si aplicamos importan ese va hacer el valor tomado por css  -->
  <span class="miClase-2">hola mundo</span>
</template>

<style>
/* esta vale 1 punto */
p {
  font-size: 50px;
  color: blue;
}

/* esta vale 10 + 1 = 11 puntos  */
.miClase {
  color: red;
}

/* esta vale 100 puntos  */
#miID {
  color: yellow;
}

/* uso de !important para que se sobreponga sobre los demas sin importar la especificidad */
span {
  color: blue !important;
}

/* aqui el selector de clase tiene mas relevancia que el selector de etiqueta
pero como se usa iportant en el selector de etiqueta esta queda ignorada  */
.miClase-2 {
  color: red;
}
</style>
