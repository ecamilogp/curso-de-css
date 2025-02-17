<template>
  <img
    src="../../assets/yotas.jpg"
    srcset="
      ../../assets/yotas-small.jpg   400w,
      ../../assets/yotas-medium.jpg  600w,
      ../../assets/yotas-big.jpg    1000w
    "
    sizes="(max-width: 600px) 100vw, (max-width: 1200px) 50vw, 33vw"
    alt="Imagen de Yotas"
  />
</template>

<style scoped>
img {
  max-width: 100%;
  height: auto;
}
</style>
