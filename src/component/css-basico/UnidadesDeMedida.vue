<template>
  <div class="container px">
    <h1>Has recibido un mensaje <span>(hace un momento)</span></h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Error accusamus numquam consequuntur
      maiores eos officia ipsam commodi dolore aliquid.
    </p>
  </div>

  <div class="container em">
    <h1>Has recibido un mensaje <span>(hace un momento)</span></h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Error accusamus numquam consequuntur
      maiores eos officia ipsam commodi dolore aliquid.
    </p>
  </div>

  <div class="container rem">
    <h1>Has recibido un mensaje <span>(hace un momento)</span></h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Error accusamus numquam consequuntur
      maiores eos officia ipsam commodi dolore aliquid.
    </p>
  </div>

  <div class="container vw">
    <h1>Has recibido un mensaje <span>(hace un momento)</span></h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Error accusamus numquam consequuntur
      maiores eos officia ipsam commodi dolore aliquid.
    </p>
  </div>

  <div class="container vh">
    <h1>Has recibido un mensaje <span>(hace un momento)</span></h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Error accusamus numquam consequuntur
      maiores eos officia ipsam commodi dolore aliquid.
    </p>
  </div>
</template>

<style scoped>
.container {
  padding: 20px;
  font-family: sans-serif;
  border-left: 5px solid black;
  margin-bottom: 20px;
}

.px {
  width: 600px;
  background: #ededed;
}

.em {
  width: 40em;
  background: #d1e7dd;
}

.rem {
  width: 40rem;
  background: #cfe2ff;
}

.vw {
  width: 50vw;
  background: #f8d7da;
}

.vh {
  height: 30vh;
  background: #fff3cd;
}

h1 {
  margin: 0;
  font-size: 2em;
}

span {
  font-size: 0.8em;
  color: #999;
  font-weight: 100;
}
</style>
