<template>
  <header class="header">
    <div class="header__overlay"></div>
    <div class="header__item-container">
      <img src="../../assets/yotas.jpg" class="header__img" />
      <h1>ADA VERSION 2024</h1>
      <P
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, provident quis.
        Itaque, dolore magnam nisi enim odio eos sit nam, quaerat perspiciatis minus dolorum esse
        veritatis voluptas veniam vitae autLorem ipsum dolor sit amet consectetur adipisicing elit.
        Reiciendis, provident quis. Itaque, dolore magnam nisi enim odio eos sit nam, quaerat
        perspiciatis minus dolorum esse veritatis voluptas veniam vitae autLorem ipsum dolor sit
        amet consectetur adipisicing elit. Reiciendis, provident quis. Itaque, dolore magnam nisi
        enim odio eos sit nam, quaerat perspiciatis minus dolorum esse veritatis voluptas veniam
        vitae aut.</P
      >
    </div>
  </header>
  <nav>
    <div>
      <ul class="nav__ul">
        <li class="nav__item"><a href="#" class="nav__link">house</a></li>
        <li class="nav__item"><a href="#" class="nav__link">about</a></li>
        <li class="nav__item"><a href="#" class="nav__link">contac</a></li>
        <li class="nav__item"><a href="#" class="nav__link link--login">login</a></li>
      </ul>
    </div>
    <div>
      <img src="../../assets/Ada13.png" alt="" />
    </div>
  </nav>
  <main>
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi recusandae eveniet tempore.
    Voluptate cumque iure inventore dolorem, illum, dignissimos nulla a qui, nostrum provident
    dolores sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet consectetur adipisicing
    elit. Sequi recusandae eveniet tempore. Voluptate cumque iure inventore dolorem, illum,
    dignissimos nulla a qui, nostrum provident dolores sapiente iste. Ad, minus dolore.Lorem ipsum
    dolor, sit amet consectetur adipisicing elit. Sequi recusandae eveniet tempore. Voluptate cumque
    iure inventore dolorem, illum, dignissimos nulla a qui, nostrum provident dolores sapiente iste.
    Ad, minus dolore.Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi recusandae
    eveniet tempore. Voluptate cumque iure inventore dolorem, illum, dignissimos nulla a qui,
    nostrum provident dolores sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet
    consectetur adipisicing elit. Sequi recusandae eveniet tempore. Voluptate cumque iure inventore
    dolorem, illum, dignissimos nulla a qui, nostrum provident dolores sapiente iste. Ad, minus
    dolore.Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi recusandae eveniet
    tempore. Voluptate cumque iure inventore dolorem, illum, dignissimos nulla a qui, nostrum
    provident dolores sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet consectetur
    adipisicing elit. Sequi recusandae eveniet tempore. Voluptate cumque iure inventore dolorem,
    illum, dignissimos nulla a qui, nostrum provident dolores sapiente iste. Ad, minus dolore.Lorem
    ipsum dolor, sit amet consectetur adipisicing elit. Sequi recusandae eveniet tempore. Voluptate
    cumque iure inventore dolorem, illum, dignissimos nulla a qui, nostrum provident dolores
    sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi
    recusandae eveniet tempore. Voluptate cumque iure inventore dolorem, illum, dignissimos nulla a
    qui, nostrum provident dolores sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet
    consectetur adipisicing elit. Sequi recusandae eveniet tempore. Voluptate cumque iure inventore
    dolorem, illum, dignissimos nulla a qui, nostrum provident dolores sapiente iste. Ad, minus
    dolore.Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi recusandae eveniet
    tempore. Voluptate cumque iure inventore dolorem, illum, dignissimos nulla a qui, nostrum
    provident dolores sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet consectetur
    adipisicing elit. Sequi recusandae eveniet tempore. Voluptate cumque iure inventore dolorem,
    illum, dignissimos nulla a qui, nostrum provident dolores sapiente iste. Ad, minus dolore.Lorem
    ipsum dolor, sit amet consectetur adipisicing elit. Sequi recusandae eveniet tempore. Voluptate
    cumque iure inventore dolorem, illum, dignissimos nulla a qui, nostrum provident dolores
    sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi
    recusandae eveniet tempore. Voluptate cumque iure inventore dolorem, illum, dignissimos nulla a
    qui, nostrum provident dolores sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet
    consectetur adipisicing elit. Sequi recusandae eveniet tempore. Voluptate cumque iure inventore
    dolorem, illum, dignissimos nulla a qui, nostrum provident dolores sapiente iste. Ad, minus
    dolore.Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi recusandae eveniet
    tempore. Voluptate cumque iure inventore dolorem, illum, dignissimos nulla a qui, nostrum
    provident dolores sapiente iste. Ad, minus dolore.Lorem ipsum dolor, sit amet consectetur
    adipisicing elit. Sequi recusandae eveniet tempore. Voluptate cumque iure inventore dolorem,
    illum, dignissimos nulla a qui, nostrum provident dolores sapiente iste. Ad, minus dolore.
  </main>
</template>

<style scoped>
/* esto me funciona para manejar el estilo del body desde un conmponente */

body,
h1,
p,
ul,
li {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  color: white;
}

body {
  font-family: Arial, sans-serif;
  background-color: #fa8000;
  color: white;
  text-align: center;
}

/* HEADER */
.header {
  height: 100vh;
  background: url('../../assets/4k2.jpeg') no-repeat center center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  text-align: center;
  text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
}

.header__overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0.4;
  background: #fa8000;
}

.header__item-container {
  position: relative;
  z-index: 1;
  max-width: 800px;
}

.header__img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  border: 5px solid white;
  margin-bottom: 20px;
  transition: transform 0.3s ease;
}

.header__img:hover {
  transform: scale(1.1);
}

h1 {
  font-size: 3rem;
  font-weight: bold;
  margin-bottom: 10px;
}

p {
  font-size: 1.1rem;
  line-height: 1.6;
  padding: 0 20px;
  text-align: justify;
}

/* NAVIGATION */
nav {
  background: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 40px;
  box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
}

.nav__ul {
  display: flex;
  gap: 20px;
}

.nav__item {
  list-style: none;
}

.nav__link {
  color: #fa8000;
  font-weight: bold;
  text-decoration: none;
  padding: 8px 12px;
  transition:
    color 0.3s ease,
    background 0.3s ease;
  border-radius: 5px;
}

.nav__link:hover {
  background: #fa8000;
  color: white;
}

nav img {
  width: 60px;
}

/* MAIN CONTENT */
main {
  padding: 40px 20px;
  font-size: 1rem;
  line-height: 1.8;
  max-width: 900px;
  margin: 0 auto;
}
</style>
