<template>
  <div class="image-container">
    <h3>Object-Fit: Cover</h3>
    <img src="../../assets/yotas.jpg" class="cover" alt="Nature Image" />

    <h3>Object-Fit: Contain</h3>
    <img src="../../assets/yotas.jpg" class="contain" alt="Ocean Image" />

    <h3>Object-Fit: None + Object-Position: Left Top</h3>
    <img src="../../assets/yotas.jpg" class="none-position" alt="Mountain Image" />
  </div>
</template>

<style scoped>
.image-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
}

img {
  width: 200px;
  height: 150px;
  border: 2px solid black;
}

/* Ejemplos de object-fit */
.cover {
  object-fit: cover;
}

.contain {
  object-fit: contain;
  background-color: lightgray;
}

.none-position {
  object-fit: none;
  object-position: left top;
}
</style>
