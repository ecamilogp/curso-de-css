<template>
  <div>
    <h1>PseudoElementos</h1>

    <p>
      texto # 1 <br />
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae, eius fugit! Modi omnis
      placeat dolores debitis provident architecto, ratione sequi vero, cumque, sapiente alias odit
      veniam sunt recusandae! Est, impedit?
    </p>
    <p class="p2">texto # 2</p>

    <input placeholder="ingrese texto" type="text" />

    <ul>
      <li>elemento 1</li>
      <li>elemento 2</li>
      <li>elemento 3</li>
      <li>elemento 4</li>
    </ul>
  </div>
</template>

<style scoped>
p::before {
  content: 'A 🤟 before ';
  color: red;
}

p::after {
  content: ' ✊ after';
  color: green;
}

p::first-letter {
  font-size: 2rem;
  color: red;
  font-weight: bold;
}

p::first-line {
  font-weight: bold;
  text-decoration: underline blue 2px;
}

p::selection {
  background-color: aqua;
}

input::placeholder {
  color: red;
  font-family: italic;
}

li::marker {
  color: blue;
  font-size: 1.2rem;
  content: '|👉 ';
}

h1::first-letter {
  color: red;
}
</style>
