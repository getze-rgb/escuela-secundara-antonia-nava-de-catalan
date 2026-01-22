#hola bienvenidos a la pagina de la antonia #

/ (raíz)
│── index.html
│<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Escuela Secundaria Antonia Nava de Catalán</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css/estilos.css">
</head>

<body>

<header class="encabezado">
  <h1>Escuela Secundaria Antonia Nava de Catalán</h1>
  <p>Aula de Medios · Inscripciones Abiertas</p>
</header>

<nav class="menu">
  <a href="#inicio">Inicio</a>
  <a href="#aula">Aula de Medios</a>
  <a href="#galeria">Galería</a>
  <a href="#avisos">Avisos</a>
  <a href="#inscripcion">Inscripción</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="inicio" class="seccion">
  <h2>Bienvenidos</h2>
  <p>
    Sitio institucional de la Escuela Secundaria Antonia Nava de Catalán,
    orientado a la difusión de actividades académicas y al proceso de
    inscripción del Aula de Medios.
  </p>
</section>

<section id="aula" class="seccion">
  <h2>Aula de Medios</h2>
  <p>
    El Aula de Medios promueve el desarrollo de habilidades digitales,
    el uso responsable de la tecnología y el fortalecimiento académico
    de los estudiantes.
  </p>
</section>

<section id="galeria" class="seccion">
  <h2>Galería</h2>
  <div class="galeria">
    <img src="img/foto1.jpg" alt="Aula de medios">
    <img src="img/foto2.jpg" alt="Trabajo en computadoras">
    <img src="img/foto3.jpg" alt="Actividades escolares">
  </div>
</section>

<section id="avisos" class="seccion">
  <h2>Avisos</h2>
  <ul class="avisos">
    <li>📌 Inscripciones abiertas al nuevo ciclo escolar.</li>
    <li>📌 Cupo limitado.</li>
    <li>📌 Inicio de clases: Próximamente.</li>
  </ul>
</section>

<section id="inscripcion" class="seccion">
  <h2>Inscripción</h2>
  <p>
    Para realizar el proceso de inscripción, da clic en el siguiente enlace:
  </p>
  <a class="boton" href="#" target="_blank">Formulario de Inscripción</a>
</section>

<section id="contacto" class="seccion">
  <h2>Contacto</h2>
  <p>📍 Escuela Secundaria Antonia Nava de Catalán</p>
  <p>📞 Teléfono: __________________</p>
  <p>✉️ Correo: __________________</p>
</section>

<footer class="pie">
  <p>© 2026 Escuela Secundaria Antonia Nava de Catalán</p>
</footer>

<script src="js/scripts.js"></script>
</body>
</html>

├── css/
│   └── estilos.css
│* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background-color: #f2f2f2;
  color: #333;
}

.encabezado {
  background-color: #1f3c88;
  color: white;
  padding: 30px 15px;
  text-align: center;
}

.menu {
  background-color: white;
  text-align: center;
  padding: 10px;
}

.menu a {
  margin: 0 10px;
  text-decoration: none;
  color: #1f3c88;
  font-weight: bold;
}

.menu a:hover {
  text-decoration: underline;
}

.seccion {
  background-color: white;
  margin: 20px;
  padding: 20px;
  border-radius: 8px;
}

.galeria {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
}

.galeria img {
  width: 100%;
  border-radius: 6px;
}

.avisos {
  list-style: none;
  padding: 0;
}

.avisos li {
  padding: 8px 0;
}

.boton {
  display: inline-block;
  background-color: #1f3c88;
  color: white;
  padding: 12px 20px;
  text-decoration: none;
  border-radius: 6px;
  margin-top: 10px;
}

.boton:hover {
  background-color: #162e63;
}

.pie {
  text-align: center;
  padding: 15px;
  color: #666;
}

├── js/
│   └── scripts.js
│console.log("Sitio del Aula de Medios cargado correctamente");

└── img/
    └── (aquí van tus fotos)
