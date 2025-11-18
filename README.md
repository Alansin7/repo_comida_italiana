<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Comida Italiana — Bella Italia</title>
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>

  <header class="topbar">
    <h1>Bella Italia</h1>
    <p class="subtitle">Sabores auténticos de la cocina italiana</p>
    <nav class="nav">
      <a href="#inicio">Inicio</a>
      <a href="#menu">Menú</a>
      <a href="#nosotros">Nosotros</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <main>
    <!-- Sección Inicio -->
    <section id="inicio" class="section">
      <h2>Bienvenido a Bella Italia</h2>
      <p>
        Disfruta pastas, pizzas y postres italianos preparados con ingredientes frescos 
        y recetas tradicionales.
      </p>
    </section>

    <section id="menu" class="section">
      <h2>Menú destacado</h2>

      <h3>Pastas</h3>
      <ul>
        <li>Spaghetti a la Boloñesa</li>
        <li>Fettuccine Alfredo</li>
        <li>Lasagna de carne</li>
      </ul>

      <h3>Pizzas</h3>
      <ul>
        <li>Margherita</li>
        <li>Cuatro quesos</li>
        <li>Hawaiana italiana</li>
      </ul>

      <h3>Postres</h3>
      <ul>
        <li>Tiramisú</li>
        <li>Panna Cotta</li>
        <li>Gelato artesanal</li>
      </ul>
    </section>

    <!-- Sección Nosotros -->
    <section id="nosotros" class="section">
      <h2>Sobre nosotros</h2>
      <p>
        Somos un pequeño restaurante familiar que busca compartir el amor por la 
        comida italiana en cada plato. Nuestro objetivo es que te sientas como en casa.
      </p>
    </section>

    <!-- Sección Contacto -->
    <section id="contacto" class="section">
      <h2>Contacto</h2>
      <p>Dirección: Calle Italia #123, Col. Centro, Cuernavaca, Morelos</p>
      <p>Teléfono: 777 000 0000</p>
      <p>Horario: Lunes a domingo, 1:00 pm - 10:00 pm</p>

      <form class="contact-form">
        <label>
          Nombre:
          <input type="text" name="nombre" placeholder="Tu nombre">
        </label>

        <label>
          Correo:
          <input type="email" name="correo" placeholder="tucorreo@ejemplo.com">
        </label>

        <label>
          Mensaje:
          <textarea name="mensaje" rows="4" placeholder="Escribe tu mensaje..."></textarea>
        </label>

        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>

  <footer class="footer">
    <p>&copy; 2025 Bella Italia. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
