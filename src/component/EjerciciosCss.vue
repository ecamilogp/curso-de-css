<template>
  <div class="contenedor">
    <div class="uno">uno</div>
    <div class="dos">dos</div>
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
  margin-bottom: 30px;
}
.uno {
  background: yellow;
  width: 150px;
  height: 150px;
  text-align: center;
  border: 5px solid orange;
}
.dos {
  box-sizing: border-box;
  background: blue;
  width: 150px;
  height: 150px;
  text-align: center;
  border: 5px outset orange;
}

input {
  width: 80%;
  margin: 5px;
  padding: 6px 9px;
  border: none;
  border-bottom: 1px solid black;
  background: gainsboro;
}
form {
  width: 300px;
}
</style>
