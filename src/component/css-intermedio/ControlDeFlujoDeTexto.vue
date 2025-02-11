<template>
  <div class="text-container">
    <h2>Ejemplo de Control de Flujo de Texto en CSS</h2>

    <div class="text-box">
      <h3>1. Alineación de texto (text-align)</h3>
      <p class="align-left">Este texto está alineado a la izquierda.</p>
      <p class="align-center">Este texto está centrado.</p>
      <p class="align-right">Este texto está alineado a la derecha.</p>
    </div>

    <div class="text-box">
      <h3>2. Sangría (text-indent)</h3>
      <p class="indent">Este párrafo tiene una sangría de 20px en la primera línea.</p>
    </div>

    <div class="text-box">
      <h3>3. Control de espacio entre líneas (line-height)</h3>
      <p class="line-height">Este párrafo tiene un espacio de 1.5 entre las líneas de texto.</p>
    </div>

    <div class="text-box">
      <h3>4. Transformación de texto (text-transform)</h3>
      <p class="uppercase">Este texto está en mayúsculas.</p>
      <p class="capitalize">Este texto tiene la primera letra de cada palabra en mayúscula.</p>
      <p class="lowercase">ESTE TEXTO ESTÁ EN MINÚSCULAS.</p>
    </div>

    <div class="text-box">
      <h3>5. Desbordamiento de texto (text-overflow)</h3>
      <p class="ellipsis">
        Este texto es demasiado largo para el contenedor y se cortará con puntos suspensivos...
      </p>
    </div>

    <div class="text-box">
      <h3>6. Espaciado entre caracteres (letter-spacing)</h3>
      <p class="letter-spacing">Este texto tiene un espaciado de 2px entre caracteres.</p>
    </div>

    <div class="text-box">
      <h3>7. Control de flujo de texto (white-space)</h3>
      <p class="nowrap">Este texto no se ajustará, todo está en una sola línea.</p>
      <p class="pre-wrap">
        Este texto tiene saltos de línea, pero se ajustará dentro del contenedor si es necesario.
      </p>
    </div>

    <div class="text-box">
      <h3>8. Manejo de palabras largas (word-wrap)</h3>
      <p class="break-word">
        Estaesunapalabralongisimaqueprobablementeserompa para que pueda ajustarse dentro del
        contenedor sin causar desbordamientos.
      </p>
    </div>

    <div class="text-box">
      <h3>9. Dirección de flujo de texto (direction)</h3>
      <p class="rtl">
        Este texto se lee de derecha a izquierda (ideal para idiomas RTL como árabe).
      </p>
    </div>
  </div>
</template>

<style scoped>
.text-container {
  width: 80%;
  margin: 0 auto;
  padding: 20px;
  font-family: Arial, sans-serif;
}

h2 {
  text-align: center;
  margin-bottom: 30px;
}

.text-box {
  margin-bottom: 20px;
  padding: 15px;
  border: 1px solid #ddd;
  background-color: #f8f9fa;
}

h3 {
  margin-top: 0;
}

.align-left {
  text-align: left;
}

.align-center {
  text-align: center;
}

.align-right {
  text-align: right;
}

.indent {
  text-indent: 20px;
}

.line-height {
  line-height: 1.5;
}

.uppercase {
  text-transform: uppercase;
}

.capitalize {
  text-transform: capitalize;
}

.lowercase {
  text-transform: lowercase;
}

.ellipsis {
  width: 200px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.letter-spacing {
  letter-spacing: 2px;
}

.nowrap {
  white-space: nowrap;
}

.pre-wrap {
  white-space: pre-wrap;
}

.break-word {
  word-wrap: break-word;
}

.rtl {
  direction: rtl;
}
</style>
