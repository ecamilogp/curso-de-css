<template>
  <div class="box">caja 1</div>
  <div class="box box--blue">caja 2</div>
  <div class="box box--red">caja 3</div>
  <p>Edward Garcia</p>
  <img src="../../assets/yotas.jpg" alt="" />
</template>

<style scoped>
.box {
  background-color: lightgray;
  width: 200px;
  height: 200px;
  font-size: x-large;
  color: white;
  border: 2px solid black;
  position: relative;
}

.box--blue {
  background: blue;
  top: -140px;
  left: 40px;
}

p {
  background-color: red;
  color: white;
  width: 100px;
  position: relative;
  top: -12px;
  left: 72px;
  z-index: 1;
}

img {
  height: 200px;
  width: 200px;
  border: 2px solid black;
  position: relative;
  top: -230px;
  left: 70px;
}

.box--red {
  color: red;
  text-decoration: underline;
}
</style>
