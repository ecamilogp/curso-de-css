<template>
  <header class="header">
    <nav class="main-navbar">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Login</a></li>
        <li><a href="#">ITEM 5</a></li>
      </ul>
    </nav>
  </header>
  <div class="main-wrapper">
    <aside class="secondary-navbar">
      <h2>ELIGE EL CONCEPTO</h2>
      <nav>
        <ul>
          <li><a href="#">Concepto 1</a></li>
          <li><a href="#">Concepto 2</a></li>
          <li><a href="#">Concepto 3</a></li>
          <li><a href="#">Concepto 4</a></li>
          <li><a href="#">Concepto 5</a></li>
        </ul>
      </nav>
    </aside>
    <main>
      <h1>Título Principal</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores voluptates dicta quas
        placeat beatae et expedita quia accusamus id magni. Velit molestiae rem ipsam praesentium
        voluptatum reprehenderit libero officiis adipisci.
      </p>
    </main>
    <aside class="right-sidebar">
      <h2>Título Random</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aliquid officiis quasi adipisci
        fuga commodi soluta, corrupti ratione repudiandae laudantium minima libero amet nesciunt
        atque at et natus vel facere voluptate!
      </p>
    </aside>
  </div>
  <footer>Edward - @Copyright 2025</footer>
</template>

<style scoped>
/* HEADER */
header {
  background-color: #48e;
  padding: 10px 0;
  text-align: center;
}

.main-navbar ul {
  display: flex;
  justify-content: center;
  padding: 0;
  margin: 0;
}

.main-navbar li {
  list-style: none;
  margin: 0 10px;
}

.main-navbar a {
  color: white;
  padding: 10px 15px;
  display: inline-block;
  font-weight: bold;
}

nav a {
  text-decoration: none;
}

/* MAIN SECTION */
.main-wrapper {
  display: flex;
  flex-direction: row;
  min-height: 80vh;
  margin: 20px auto;
  max-width: 1200px;
  gap: 20px;
}

.secondary-navbar {
  width: 250px;
  background-color: #f8f9fa;
  padding: 20px;
  border-radius: 5px;
}

.secondary-navbar ul {
  padding: 0;
}

.secondary-navbar li {
  list-style: none;
  margin: 10px 0;
}

.secondary-navbar a {
  color: #48e;
  display: inline-block;
  padding: 8px 10px;
}

main {
  flex-grow: 1;
  background-color: #fff;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.right-sidebar {
  width: 250px;
  background-color: #f8f9fa;
  padding: 20px;
  border-radius: 5px;
}

/* FOOTER  */

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
</style>
