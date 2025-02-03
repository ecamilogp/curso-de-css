<template>
  <div class="contenedor">
    <div class="uno">uno</div>
    <div class="dos">dos</div>
    <div class="tres">tres</div>
    <div class="cuatro">cuatro</div>
    <div class="cinco">cinco</div>
    <div class="seis">seis</div>
    <div class="siete">siete</div>
    <div class="ocho">ocho</div>
    <div class="nueve">nueve</div>
    <div class="diez">diez</div>
    <div class="once">once</div>
    <div class="doce">doce</div>
  </div>
  <form>
    <input type="email" placeholder="email" />
    <input type="password" placeholder="contraseña" />
    <input type="submit" value="iniciar sesion" />
  </form>
</template>

<style scoped>
.contenedor {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
  margin: auto;
}
.uno {
  background: yellow;
  width: 180px;
  height: 180px;
  text-align: center;
  border-width: 9px;
  border-style: solid;
  border-color: orange;
}
.dos {
  background: blue;
  width: 180px;
  height: 180px;
  text-align: center;
  border-width: 9px;
  border-style: dotted;
  border-color: orange;
}
.tres {
  background: red;
  width: 180px;
  height: 180px;
  text-align: center;
  border-width: 9px;
  border-style: dashed;
  border-color: orange;
}
.cuatro {
  background: gray;
  width: 180px;
  height: 180px;
  text-align: center;
  border-width: 9px;
  border-style: double;
  border-color: orange;
}
.cinco {
  background: aqua;
  width: 180px;
  height: 180px;
  text-align: center;
  border-width: 9px;
  border-style: groove;
  border-color: orange;
}
.seis {
  background: rgb(198, 1, 198);
  width: 180px;
  height: 180px;
  text-align: center;
  border-width: 9px;
  border-style: ridge;
  border-color: orange;
}
.siete {
  background: rgb(252, 199, 252);
  width: 180px;
  height: 180px;
  text-align: center;
  border-width: 9px;
  border-style: inset;
  border-color: orange;
}
.ocho {
  background: rgb(190, 240, 190);
  width: 180px;
  height: 180px;
  text-align: center;
  border-width: 9px;
  border-style: outset;
  border-color: orange;
}

.nueve {
  background: rgb(242, 255, 4);
  width: 180px;
  height: 180px;
  border-top: 9px solid orange;
  border-radius: 30%;
  text-align: center;
}
.diez {
  background: rgb(3, 171, 255);
  width: 180px;
  height: 180px;
  border-right: 9px dotted orange;
  border-radius: 100%;
  text-align: center;
}
.once {
  background: rgb(255, 4, 4);
  width: 180px;
  height: 180px;
  border-left: 9px dashed orange;
  border-radius: 10%;
  text-align: center;
}
.doce {
  background: rgb(188, 194, 196);
  width: 180px;
  height: 180px;
  border-bottom: 9px double orange;
  border-radius: 100%;
  text-align: center;
}
input {
  width: 80%;
  margin-top: 10px;
}
form {
  width: 300px;
}
</style>
