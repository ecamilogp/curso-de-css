<template>
  <!-- Encabezado (Bloque) -->
  <header class="header">
    <h1>bloques y multimedia</h1>
  </header>

  <!-- Sección con imagen de fondo -->
  <section class="content">
    <h2>Imagen de Fondo</h2>
    <p>Este bloque tiene una imagen de fondo utilizando CSS.</p>
  </section>

  <!-- Sección con video de fondo -->
  <div class="video-container">
    <video autoplay loop controls muted>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4" />
    </video>
    <div class="video-text">Texto sobre el video</div>
  </div>
</template>

<style scoped>
/* Estilos generales */
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

/* Encabezado (bloque) */
.header {
  background-color: #4a90e2;
  color: white;
  text-align: center;
  padding: 20px;
}

/* Sección con imagen de fondo */
.content {
  background-image: url('https://source.unsplash.com/1600x900/?nature');
  background-size: cover;
  background-position: center;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

/* Contenedor del video */
.video-container {
  position: relative;
  aspect-ratio: 16/9;
  overflow: hidden;
}

/* Video de fondo */
.video-container video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* Texto sobre el video */
.video-text {
  position: relative;
  z-index: 2;
  text-align: center;
  color: white;
  font-size: 24px;
  padding: 50px;
  background: rgba(0, 0, 0, 0.5);
}
</style>
