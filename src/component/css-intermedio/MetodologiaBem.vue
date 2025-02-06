<template>
  <nav class="menu menu--horizontal">
    <ul class="menu__lista">
      <li class="menu__item menu__item--activo">Inicio</li>
      <li class="menu__item">Servicios</li>
      <li class="menu__item">Contacto</li>
    </ul>
  </nav>
  <nav class="menu menu--viejo">
    <ul class="menu__lista">
      <li class="menu__item menu__item--activo">Inicio</li>
      <li class="menu__item">Servicios</li>
      <li class="menu__item">Contacto</li>
    </ul>
  </nav>
</template>

<style scoped>
/* Bloque */
.menu {
  background-color: lightgray;
  padding: 10px;
  text-decoration: underline;
  margin: 20px;
  border: 2px solid black;
}

/* Modificador del bloque */
.menu--horizontal {
  display: flex;
}

/* Elemento */
.menu__lista {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
}

/* Elemento */
.menu__item {
  margin-right: 15px;
  padding: 5px;
}

/* Modificador de elemento */
.menu__item--activo {
  font-weight: bold;
  color: red;
}

.menu--viejo {
  background-color: aqua;
  opacity: 0.5;
}
</style>
