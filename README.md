!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Movelo - Transporte de Personas y Mercancías</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #4a4a4a;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
    }
    section {
      padding: 2rem;
    }
    .btn {
      background-color: #007BFF;
      color: white;
      padding: 0.5rem 1rem;
      text-decoration: none;
      border-radius: 5px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #4a4a4a;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <div class="logo">Movelo</div>
      <ul>
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#servicios">Servicios</a></li>
        <li><a href="#registro">Registro</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <section id="inicio">
    <h1>Bienvenido a Movelo</h1>
    <p>Tu solución para transporte de personas y mercancías en todo Panamá.</p>
    <a href="#registro" class="btn">Regístrate Ahora</a>
  </section>

  <section id="servicios">
    <h2>Nuestros Servicios</h2>
    <ul>
      <li>Transporte de Personas</li>
      <li>Envíos de Mercancías</li>
      <li>Reservas Anticipadas</li>
      <li>Seguimiento GPS en Tiempo Real</li>
    </ul>
  </section>

  <section id="registro">
    <h2>Registro</h2>
    <form action="/register" method="POST">
      <label for="nombre">Nombre Completo:</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="correo">Correo Electrónico:</label>
      <input type="email" id="correo" name="correo" required>

      <label for="telefono">Teléfono:</label>
      <input type="tel" id="telefono" name="telefono" required>

      <label for="tipo">Tipo de Usuario:</label>
      <select id="tipo" name="tipo">
        <option value="cliente">Cliente</option>
        <option value="conductor">Conductor</option>
      </select>

      <button type="submit">Registrarse</button>
    </form>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Teléfono: +507 1234-5678</p>
    <p>Correo: info@movelo.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Movelo. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
