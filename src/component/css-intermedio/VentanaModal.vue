<template>
  <dialog open class="ventana">
    <div class="modal__content">
      <h2 class="modal__title">VENTANA MODAL</h2>
      <P class="text"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste illo rem repellat soluta a
        quo nostrum harum laboriosam, reprehenderit natus earum voluptatem mollitia veritatis dolore
        ipsum ad fugit. Ullam, fuga.</P
      >
      <form method="dialog">
        <button class="modal__close-button">X</button>
      </form>
    </div>
  </dialog>

  <!-- ejemplo de como hacerlo de otra manera sin js  -->
  <button onclick="miDialog.showModal()">Abrir Modal</button>

  <dialog id="miDialog">
    <p>Este es un modal nativo sin necesidad de librerías.</p>
    <button onclick="miDialog.close()">Cerrar</button>
  </dialog>

  Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente quaerat doloribus nihil
  consequatur, repudiandae fugiat et fuga libero perferendis quos non sunt fugit natus aspernatur,
  dignissimos officia beatae ad corrupti. Lorem ipsum dolor sit amet consectetur adipisicing elit.
  Sapiente quaerat doloribus nihil consequatur, repudiandae fugiat et fuga libero perferendis quos
  non sunt fugit natus aspernatur, dignissimos officia beatae ad corrupti. Lorem ipsum dolor sit
  amet consectetur adipisicing elit. Sapiente quaerat doloribus nihil consequatur, repudiandae
  fugiat et fuga libero perferendis quos non sunt fugit natus aspernatur, dignissimos officia beatae
  ad corrupti. Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente quaerat doloribus
  nihil consequatur, repudiandae fugiat et fuga libero perferendis quos non sunt fugit natus
  aspernatur, dignissimos officia beatae ad corrupti. Lorem ipsum dolor sit amet consectetur
  adipisicing elit. Sapiente quaerat doloribus nihil consequatur, repudiandae fugiat et fuga libero
  perferendis quos non sunt fugit natus aspernatur, dignissimos officia beatae ad corrupti. Lorem
  ipsum dolor sit amet consectetur adipisicing elit. Sapiente quaerat doloribus nihil consequatur,
  repudiandae fugiat et fuga libero perferendis quos non sunt fugit natus aspernatur, dignissimos
  officia beatae ad corrupti. Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente
  quaerat doloribus nihil consequatur, repudiandae fugiat et fuga libero perferendis quos non sunt
</template>

<style scoped>
.ventana {
  position: absolute;
  background: rgba(0, 0, 0, 0.384);
  height: 100vh;
  box-sizing: border-box;
}

.modal__content {
  background-color: white;
  padding: 10px 20px;
  width: 80%;
  margin: auto;
  margin-top: 50px;
  position: relative;
}

.modal__title {
  margin-top: 10px;
}
.modal__close-button {
  background: black;
  color: white;
  position: absolute;
  top: 0;
  right: 0;
  padding: 4px 12px;
}
</style>
