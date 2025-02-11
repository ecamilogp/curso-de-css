<template>
  <h1>propiedades de texto</h1>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Placeat fugit voluptatibus,
    repudiandae omnis vitae quaerat. Vitae ducimus hic architecto eligendi, quaerat quam ipsam quis
    aliquam repellendus. Enim error repellat distinctio.
  </p>

  <p class="text">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda est quia repudiandae quae
    voluptatum. Dolore rerum quos sint omnis illo unde dignissimos dolorem, error placeat minus
    suscipit in dolor odio?
  </p>
</template>

<style scoped>
p {
  color: crimson;
  font-family: sans-serif;
  font-size: 20px;
  font-weight: bolder;
  font-style: italic;
  font-variant: normal;

  /* podemos usar todo en una sola linea con font
   pero es importante conservar el orden para poder hacer el efecto cascada

  font: italic small-caps bold 20px sans-serif; */
}

.text {
  color: blue;
  text-align: center;
  text-decoration: underline;
  text-transform: capitalize;
  letter-spacing: 2px;
  word-spacing: 2px;
  line-height: 1.5;
  white-space: normal;
  text-shadow: 1px 2px 2px black;
}
</style>
