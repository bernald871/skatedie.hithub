<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>El Mundo del Skate</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Bienvenidos al Mundo del Skate</h1>
    <nav>
      <ul>
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#historia">Historia</a></li>
        <li><a href="#tipos">Tipos de Skate</a></li>
        <li><a href="#trucos">Trucos</a></li>
        <li><a href="#tienda">Tienda</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <section id="inicio">
    <h2>¿Qué es el Skate?</h2>
    <p>El skateboarding es un deporte que consiste en deslizarse sobre una patineta o skate. Es una disciplina que ha sido popular por décadas y se ha convertido en un estilo de vida para muchas personas.</p>
  </section>

  <section id="historia">
    <h2>Historia del Skate</h2>
    <p>El skateboarding nació en la década de 1950 en California, cuando los surfistas decidieron simular el surf en tierra firme. Con el tiempo, se fue desarrollando como una disciplina propia, con sus propias maniobras y cultura.</p>
  </section>

  <section id="tipos">
    <h2>Tipos de Skate</h2>
    <ul>
      <li><strong>Skateboard clásico:</strong> Ideal para hacer trucos en el asfalto y en rampas.</li>
      <li><strong>Longboard:</strong> Más largo y estable, ideal para descender colinas y hacer paseos largos.</li>
      <li><strong>Cruiser:</strong> Similar al longboard, pero más pequeño y maniobrable.</li>
    </ul>
  </section>

  <section id="trucos">
    <h2>Trucos de Skate</h2>
    <p>Algunos de los trucos más populares son:</p>
    <ul>
      <li><strong>Ollie:</strong> El truco básico de saltar con el skate.</li>
      <li><strong>Kickflip:</strong> Giro del skateboard mientras el patinador está en el aire.</li>
      <li><strong>Heelflip:</strong> Similar al Kickflip, pero el giro es controlado con el talón del pie.</li>
    </ul>
  </section>

  <section id="tienda">
    <h2>Productos de Skate</h2>
    <p>Visita nuestra tienda para comprar tablas, ruedas, rodamientos y todo lo que necesitas para patinar.</p>
    <button><a href="tienda.html">Ver Tienda</a></button>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Si tienes preguntas o deseas saber más, no dudes en contactarnos.</p>
    <form action="/submit-form" method="POST">
      <label for="name">Nombre:</label>
      <input type="text" id="name" name="name">
      
      <label for="email">Correo electrónico:</label>
      <input type="email" id="email" name="email">
      
      <label for="message">Mensaje:</label>
      <textarea id="message" name="message"></textarea>
      
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 El Mundo del Skate. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
