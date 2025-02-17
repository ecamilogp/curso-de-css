<template>
  <div class="container">
    <!-- NAVBAR -->
    <header class="header">
      <nav class="main-navbar">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">Login</a></li>
          <li><a href="#">More</a></li>
        </ul>
      </nav>
    </header>

    <!-- CONTENIDO PRINCIPAL -->
    <div class="main-wrapper">
      <!-- MENÚ IZQUIERDO -->
      <aside class="secondary-navbar">
        <nav>
          <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Servicios</a></li>
            <li><a href="#">Proyectos</a></li>
            <li><a href="#">Contacto</a></li>
          </ul>
        </nav>
      </aside>

      <!-- SECCIÓN CENTRAL -->
      <main>
        <h1>Bienvenido a Nuestra Plataforma</h1>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolorum consequuntur excepturi
          repellat adipisci labore corporis aut asperiores animi odit fuga. Voluptatum nesciunt,
          repellendus consectetur a velit suscipit. Nemo, commodi quaerat! Lorem ipsum dolor sit
          amet consectetur adipisicing elit. Nisi recusandae doloremque voluptas sunt dolorum
          exercitationem velit debitis quod, earum, aliquid magnam quia molestias esse. Iure nostrum
          enim cum ipsam? Facere. Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Voluptatibus excepturi, at ipsa dolore rem dolores explicabo repellat perferendis quas
          quisquam, doloremque impedit enim illo accusamus dolor. Sit veritatis odit fugiat? Lorem
          ipsum dolor sit amet, consectetur adipisicing elit. Nihil laborum at doloremque nisi modi
          pariatur fugiat assumenda molestiae accusamus itaque vero totam blanditiis optio neque
          est, deserunt eligendi. Modi, eum.
        </p>
      </main>

      <!-- MENÚ DERECHO -->
      <aside class="right-sidebar">
        <h2>Información Destacada</h2>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis est nostrum earum, quo
          iure qui ipsa dolore natus rerum consequuntur architecto ducimus velit eum quis doloribus
          perspiciatis impedit quam soluta! Lorem ipsum dolor sit amet consectetur, adipisicing
          elit. In, mollitia voluptatem, nihil ut ducimus iste perspiciatis quis impedit laborum
          aperiam cumque est facilis autem sunt. Soluta, impedit quod. Iure, reiciendis.
        </p>
      </aside>
    </div>

    <!-- FOOTER -->
    <footer>© 2025 - Todos los derechos reservados</footer>
  </div>
</template>

<style scoped>
/* ========== DISEÑO BASE (Mobile First) ========== */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Arial', sans-serif;
}

.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  background: linear-gradient(to bottom, #f5f7fa, #c3cfe2);
}

/* HEADER */
.header {
  background: #2c3e50;
  padding: 10px 0;
  text-align: center;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

/* NAVBAR */
.main-navbar ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
  list-style: none;
  padding: 10px;
}

.main-navbar a {
  color: white;
  font-weight: bold;
  padding: 8px 12px;
  display: inline-block;
  text-decoration: none;
  border-bottom: 2px solid transparent;
  transition: 0.3s ease-in-out;
}

.main-navbar a:hover {
  border-bottom: 2px solid #3498db;
}

/* CONTENIDO PRINCIPAL */
.main-wrapper {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  padding: 20px;
  gap: 20px;
}

/* SECCIONES */
.secondary-navbar,
.right-sidebar,
main {
  width: 100%;
  padding: 20px;
  text-align: center;
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h1 {
  font-size: 24px;
  color: #34495e;
}

h2 {
  font-size: 20px;
  color: #2c3e50;
}

p {
  font-size: 16px;
  color: #555;
  line-height: 1.6;
}

/* MENÚ LATERAL IZQUIERDO */
.secondary-navbar ul {
  list-style: none;
  padding: 0;
}

.secondary-navbar li {
  margin-bottom: 10px;
}

.secondary-navbar a {
  display: block;
  color: #2c3e50;
  font-weight: bold;
  padding: 10px;
  text-decoration: none;
  border-bottom: 2px solid transparent;
  transition: 0.3s ease-in-out;
}

.secondary-navbar a:hover {
  border-bottom: 2px solid #3498db;
}

/* MENÚ DERECHO */
.right-sidebar {
  text-align: left;
}

/* FOOTER */
footer {
  background-color: #2c3e50;
  color: white;
  text-align: center;
  padding: 15px;
  width: 100%;
  margin-top: auto;
}

/* ========== MEDIA QUERIES (Pantallas más grandes) ========== */
@media screen and (min-width: 768px) {
  .main-navbar ul {
    flex-wrap: nowrap;
  }

  .main-wrapper {
    flex-direction: row;
    max-width: 1200px;
    margin: 0 auto;
    align-items: stretch;
  }

  .secondary-navbar,
  .right-sidebar {
    width: 280px;
  }

  main {
    flex-grow: 1;
    text-align: justify;
  }
}

/* Pantallas Grandes */
@media screen and (min-width: 1200px) {
  .main-wrapper {
    max-width: 1400px;
  }

  main {
    padding: 40px;
  }

  .secondary-navbar,
  .right-sidebar {
    padding: 30px;
  }
}
</style>
