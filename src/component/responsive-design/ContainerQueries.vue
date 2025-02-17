<template>
  <div class="container">
    <p>
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Provident ab, inventore porro sit
      quae, qui sed sequi nesciunt voluptate veniam ipsum maiores dolor sunt? Nostrum quae deleniti
      expedita perspiciatis possimus!
    </p>
  </div>
</template>

<style scoped>
.container {
  container-type: inline-size;
  container-name: main;
}

p {
  font-size: 8px;
}

@container main (max-width: 600px) {
  p {
    font-size: 20px;
    color: red;
    background-color: lightgray;
  }
}
</style>
