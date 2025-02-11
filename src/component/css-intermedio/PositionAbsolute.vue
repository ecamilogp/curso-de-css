<template>
  <div class="container">
    <img src="../../assets/yotas.jpg" alt="Imagen" />
    <div class="overlay">Ejemplo con position absolute</div>
  </div>
</template>

<style>
.container {
  position: relative;
  width: 300px;
  background-color: red;
  border: 2px solid rgb(137, 137, 137);
}

.container img {
  width: 90%;
  display: block;
}

.overlay {
  position: absolute;
  top: 89%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: rgba(0, 0, 0, 0.6);
  color: white;
  padding: 10px;
  font-size: 18px;
  z-index: 10;
}
</style>
