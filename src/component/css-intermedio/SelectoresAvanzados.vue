<template>
  <h1>Ingredientes</h1>
  <p>
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam cupiditate iusto voluptatibus
    cum repellat aperiam repudiandae magnam, aut voluptas placeat consequatur beatae, quisquam
    accusamus minus quod reprehenderit. Id, totam saepe.
  </p>

  <ul>
    <li class="ingrediente-faltante">Harina</li>
    <li>Leche</li>
    <li>Sal</li>
    <li id="ingrediente-secreto">Levadura</li>
    <li>Azúcar</li>
    <li>Mantequilla</li>
    <li>Huevos</li>
    <li>Agua</li>
    <li>Esencia de vainilla</li>
    <li>Chocolate</li>
    <li>Canela</li>
    <li>Frutas</li>
    <li>Yogur</li>
    <li>Almendras</li>
    <li>Crema de leche</li>
  </ul>

  <h2>Otro Título</h2>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic magnam nam molestiae fugit ad, quo
    voluptate, nulla iusto autem a optio asperiores laboriosam consectetur dolor error dignissimos
    repellat dolores alias!
  </p>
  <img src="../../assets/yotas.jpg" alt="Imagen de ejemplo" />

  <input type="text" />
</template>

<style>
li {
  color: gray;
  padding: 5px;
  list-style-type: square;
  font-size: 18px;
}

/* Selector de clase */
.ingrediente-faltante {
  color: red;
  font-weight: bold;
}

/* Selector de ID */
#ingrediente-secreto {
  color: blue;
  font-style: italic;
}

/* Selector de hijo directo */
ul > li {
  font-size: 18px;
}

/* Selector de hermanos generales */
.ingrediente-faltante ~ li {
  color: black;
}

/* Selector de hermano adyacente */
.ingrediente-faltante + li {
  text-decoration: underline;
}

/* Selector de primer hijo */
ul li:first-child {
  border-bottom: 2px solid black;
}

/* Selector de último hijo */
ul li:last-child {
  background-color: yellow;
}

/* Selector de hijo impar */
ul li:nth-child(odd) {
  background-color: rgba(33, 32, 32, 0.58);
}

/* Selector de hijo par */
ul li:nth-child(even) {
  background-color: rgba(204, 204, 211, 0.909);
}

/* Selector de elemento vacío */
p:empty {
  border: 2px dashed red;
}

/* Selector de estado :hover */
li:hover {
  background-color: rgb(50, 208, 6);
  cursor: pointer;
}

/* Selector de estado :active */
li:active {
  transform: scale(1.1);
}

/* Selector de estado :focus */
input:focus {
  outline: 2px solid rgb(7, 255, 12);
}

/* Selector de atributo */
img[alt] {
  border: 3px solid rgb(255, 19, 19);
  background-attachment: fixed;
  width: 200px;
  height: 200px;
  margin: 20px;
}

/* Selector de negación */
li:not(.ingrediente-faltante) {
  font-style: italic;
}
img:hover {
  width: 300px;
  height: 300px;
  border: 2px outset red;
  border-radius: 50%;
}
</style>
