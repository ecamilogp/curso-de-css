<template>
  <div class="contenedor">
    <!-- Caja que se mueve -->

    <br />

    <!-- Botón con cambio de color y tamaño -->
    <button class="btn">Pasa el mouse</button>

    <!-- Caja con cambio de tamaño y borde -->
    <div class="caja"></div>

    <!-- Imagen con efecto de escala -->
    <img class="imagen" src="../../assets/yotas.jpg" alt="Imagen animada" />

    <!-- Texto con cambio de color y espaciado -->
    <p class="texto">Pasa el mouse sobre mí</p>
  </div>

  <div class="box"></div>
</template>

<style scoped>
.contenedor {
  text-align: center;
  padding: 20px;
}

/* Caja roja que se mueve */
.box {
  width: 120px;
  height: 120px;
  background-color: red;

  transition: left 1s ease-in-out;
  position: relative;
  left: 0;
}

.box:hover {
  left: 400px;
}

/* Transición en botón */
.btn {
  padding: 10px 20px;
  background-color: blue;
  color: white;
  border: none;
  cursor: pointer;
  transition:
    background-color 0.3s,
    transform 0.3s;
}

.btn:hover {
  background-color: red;
  transform: scale(1.1);
}

/* Transición en caja */
.caja {
  width: 100px;
  height: 100px;
  background-color: green;
  margin: 20px auto;
  transition:
    transform 0.4s,
    border-radius 0.4s;
}

.caja:hover {
  transform: scale(1.2);
  border-radius: 20px;
}

/* Transición en imagen */
.imagen {
  display: block;
  margin: 20px auto;
  width: 300px;
  transition: transform 0.4s ease-in-out;
}

.imagen:hover {
  transform: scale(1.2) rotate(10deg);
}

/* Transición en texto */
.texto {
  font-size: 18px;
  color: black;
  display: inline-block; /* Mejora la animación */
  transition:
    color 0.3s,
    letter-spacing 0.3s;
}

.texto:hover {
  color: purple;
  letter-spacing: 2px;
}
</style>
