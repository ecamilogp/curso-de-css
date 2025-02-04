<template>
  <div class="contenedor">
    <div class="caja uno"></div>
    <div class="caja dos"></div>
    <div class="caja tres"></div>
    <div class="caja cuatro"></div>
    <div class="caja cinco"></div>
    <div class="caja seis"></div>
    <div class="caja siete"></div>
    <div class="caja ocho"></div>
    <div class="caja nueve"></div>
    <div class="caja diez"></div>
    <div class="caja once"></div>
    <div class="caja doce"></div>
    <div class="caja trece"></div>
    <div class="caja catorce"></div>
    <div class="caja quince"></div>
    <div class="caja diezyseis"></div>
  </div>
</template>

<style scoped>
.contenedor {
  background: rgb(209, 207, 207);
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
  padding: 20px;
  justify-content: center;
}

.caja {
  width: 200px;
  height: 200px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 24px;
  font-weight: bold;
  color: rgb(1, 0, 0);
  border-radius: 10px;
  border: 2px solid black;
}

.uno {
  background-color: red;
}

.dos {
  background-image: url('https://i.pinimg.com/236x/0f/47/13/0f4713d7fdea7c9ecc0d8f505084dc0d.jpg');
  background-size: cover;
  border: 2px solid black;
}

.tres {
  background: linear-gradient(to right, blue, rgb(90, 6, 139));
}

.cuatro {
  background: radial-gradient(circle, yellow, orange);
}

.cinco {
  background: conic-gradient(rgb(255, 217, 0), rgb(0, 68, 255), rgb(255, 5, 38), rgb(0, 0, 0));
}

.seis {
  background: repeating-linear-gradient(
    45deg,
    rgb(251, 255, 0),
    rgb(43, 0, 255) 10px,
    rgb(17, 16, 16) 20px
  );
}

.siete {
  background: repeating-radial-gradient(circle, rgb(0, 0, 0), rgb(255, 255, 249) 10%, blue 20%);
}

.ocho {
  background: url('https://i.pinimg.com/474x/48/16/21/481621285ef68f05414320e10422d6fe.jpg');
  background-position: center;
  background-size: contain;
}

.nueve {
  background: url('https://i.pinimg.com/236x/e5/50/e7/e550e77b8fe88f2a40f9acab30846e53.jpg');
  background-repeat: no-repeat;
  background-size: contain;
}

.diez {
  background: url('https://i.pinimg.com/236x/ec/74/8b/ec748bc55391bacf0a74e34d4241b953.jpg');
  background-attachment: fixed;
}

.once {
  background: url('https://i.pinimg.com/236x/ed/31/9e/ed319edf9ecf8648c737e43ebf494965.jpg');
  background-blend-mode: multiply;
  background-size: cover;
}

.doce {
  background: url('https://i.pinimg.com/236x/ed/d6/f2/edd6f26935fdbc59eec40f318b32b7ed.jpg'),
    linear-gradient(to bottom, rgba(0, 0, 0, 0.5), rgba(255, 255, 255, 0.5));
  background-size: contain;
}

.trece {
  background: radial-gradient(circle at top left, rgb(248, 1, 42), purple);
}

.catorce {
  background: conic-gradient(from 45deg, red, yellow, green, blue);
}

.quince {
  background: linear-gradient(to bottom, rgba(0, 0, 255, 0.5), rgba(255, 0, 0, 0.5)),
    url('https://i.pinimg.com/474x/5e/51/09/5e51095c6571a77bc83db7da9da448d3.jpg');
  background-blend-mode: exclusion;
  background-size: contain;
}
.diezyseis {
  background-color: chartreuse;
}
</style>
