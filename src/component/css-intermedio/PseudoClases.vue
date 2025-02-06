<template>
  <!-- pseudoclases  de interaccion -->
  <div class="pseudoClaseInteraccion">
    <h1>pseudoClases de interaccion</h1>
    <button>dar click</button>
    <input type="text" />
    <a href="https://www.youtube.com/watch?v=l9ny-3BBw-s&list=TLPQMDYwMjIwMjXwoCk6XhodKQ&index=18"
      >aqui puede acceder al link
    </a>
  </div>
  <!-- --------------------------------------------------- -->

  <!-- pseudoClases de posicion -->
  <div class="pseudoClasePosicion">
    <h1>pseudoClases de Posicion</h1>
    <p>hola</p>
    <span>lalala</span><br />
    <span>eeeeee</span><br />
    <span>AAAAAA</span><br />
    <span>BBBBBB</span>
    <p>mundo</p>
  </div>

  <!-- --------------------------------------------------- -->

  <!-- pseudoClases de estado -->
  <div class="pseudoClaseEstado">
    <h1>pseudoclase de estado</h1>
    <input class="uno" type="checkbox" />
    <input class="password" type="password" placeholder="inabilitado" disabled />
    <input class="tres" type="text" />
  </div>

  <!-- --------------------------------------------------- -->
  <div class="pseudoClaseEstructura">
    <h1>pseudoclase de estructura</h1>

    <div class="content"><p>hola</p></div>

    <h3>ultimo</h3>
    <h3>ultimo</h3>
  </div>
</template>

<style scoped>
.pseudoClaseInteraccion {
  display: inline-block;
  background-color: rgb(202, 209, 209);
  padding: 20px;
  text-align: center;

  border: 3px solid black;
}

/* pseudoclases  de interaccion */
input {
  margin: 20px;
}

/* pseudoclases  de interaccion */
button:hover {
  background-color: blue;
  color: white;
}

/* pseudoclases  de interaccion */
button:active {
  background-color: rgb(0, 255, 238);
  color: black;
}

/* pseudoclases  de interaccion */
input:focus {
  border: 5px outset red;
}

/* pseudoclases  de interaccion */
a:active {
  color: cyan;
  font-size: 30px;
}
/* ----------------------------------------------*/

/* pseudoclases  de posicion */
.pseudoClasePosicion {
  display: inline-block;
  background-color: rgb(202, 209, 209);
  text-align: center;
  font-size: 16px;
  margin: 10px;
  padding: 20px;
  border: 3px solid blue;
}
/* pseudoclases  de posicion */
.pseudoClasePosicion :first-child {
  color: red;
}

/* pseudoclases  de posicion */
.pseudoClasePosicion :last-child {
  color: blue;
}

/* pseudoclases  de posicion */
.pseudoClasePosicion :nth-child(2) {
  color: blueviolet;
}

/* pseudoclases  de posicion */
.pseudoClasePosicion :nth-child(odd) {
  text-decoration: underline;
}

/* pseudoclases  de posicion */
.pseudoClasePosicion :nth-child(even) {
  background-color: azure;
}
/* --------------------------------------------------- */

/* pseudoclases  de estado */
.pseudoClaseEstado {
  display: inline-block;
  background-color: rgb(202, 209, 209);
  padding: 20px;
  border: 3px solid red;
}

/* pseudoclases  de estado */
.uno:checked {
  outline: 2px solid red;
}

/* pseudoclases  de estado */
.password:disabled {
  background: rgb(21, 222, 222);
}

/* pseudoclases  de estado */
.tres:enabled {
  background-color: chartreuse;
}

/* --------------------------------------------------- */

/* pseudoclases  de estructura */
.pseudoClaseEstructura {
  display: inline-block;
  background-color: rgb(202, 209, 209);
  margin: 10px;
  padding: 20px;
  border: 3px solid rgb(69, 239, 225);
}

p:first-of-type {
  font-weight: bold;
  color: aqua;
}

h3:last-of-type {
  color: rgb(249, 152, 33);
}

.content {
  background-color: blueviolet;
}
</style>
