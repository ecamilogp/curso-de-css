<template>
  <div class="contenedor">
    <button class="boton">Normal</button>
    <button class="boton focus">Con Focus</button>
    <button class="boton offset">Con Offset</button>
  </div>
</template>

<style scoped>
.contenedor {
  display: flex;
  gap: 20px;
}

.boton {
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  background-color: lightblue;
  cursor: pointer;
}

/* Contorno básico */
.boton {
  outline: 2px solid red;
}

/* Cambiar el contorno al hacer focus */
.boton.focus:focus {
  outline: 3px dashed blue;
}

/* Separar el contorno del botón */
.boton.offset {
  outline: 3px solid green;
  outline-offset: 5px;
}
</style>
