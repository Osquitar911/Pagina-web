<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EcoSunTech</title>
  <link rel="stylesheet" href="estilos.css">
  <meta author="Oscar Alejandro Vergara Izquierdo">
  <style type="text/css">
    body {
      margin: 0;
      font-family: "Verdana";
    }

    h1 {
      font-weight: 500;
      font-size: 50px;
    }

    p {
      font-size: 25px;
    }

    .contenedor {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
      padding-top: 30px;
    }

    .contenido {
      max-width: 500px;
      margin: auto;
      text-align: center;
      padding: 25px;
    }

    .header {
      background: linear-gradient(135deg, #545BBA, #5490FF);
      color: #FFFFFF;
      text-align: center;
      margin-left: 7px;
    }
    .header img{
      width: 100px;
      height: 100px;
      border-radius: 50%;
      display: inline-block;
      object-fit: cover;
      vertical-align: middle;
      margin-right: 15px;
      animation: girar 6s linear infinite;
    }

    .menu a {
      color: #FFFFFF;
      text-decoration: none;
      font-size: 13px;
      margin-left: 7px;
      background: linear-gradient(135deg, #70D5FF, #05C7FF);
      border: solid;
      padding: 3px;
      display: inline-block; 
      transition: all 1.0s ease; 
    }

    .menu a:hover {
      opacity: 0.6;
      border: solid;
      padding: 3px;
      transform: translateY(-5px);
    }

    .subtitulo {
      font-size: 36px;
      color: #7953B7;
      text-align: center;
      margin-top: 40px;
    }

    figure {
      display: inline-block;
      margin: 10px;
    }

    figure img {
      width: 100%;
      max-width: 350px;
      height: auto;
      border-radius: 15px;
      border: solid 3px #1B4F72;
    }

    figcaption {
      text-align: center;
      font-size: 14px;
      margin-top: 8px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    table, th, td {
      border: 1px solid #ccc;
    }

    th, td {
      padding: 15px;
      text-align: center;
    }

    th {
      background-color: #7953B7;
      color: white;
    }

    tr:nth-child(even) {
      background-color: #f2f2f2;
    }

    form {
      text-align: center;
    }

    input, textarea {
      padding: 20px;
      width: 85%;
      max-width: 400px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    input[type="submit"] {
      background-color: #B76E6E;
      color: white;
      border: none;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    input[type="submit"]:hover {
      background-color: #5E84FF;
      transform: translateY(-5px);

    }

    .footer {
      background-color: #3680B4;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    hr {
      border: 0;
      height: 2px;
      background: #7953B7; 
      margin: 40px 0;
    }

    .animacion-svg {
      animation: bounce 2s infinite;
    }

    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }
    section {
      background-color: #4B95C9;
    }
    @keyframes girar {
      0% {
        transform: rotate(0deg);
    }
      100% {
        transform: rotate(360deg);
      }
    }
    .card {
        transition: all 0.4s ease;
    }

    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        background-color: #ffffff1c;
    }
    inframe{
        width: 100%;
        max-width: 350px;
        height: auto;
        border-radius: 15px;
        border: solid 3px #1B4F72;
    }    

  </style>
</head>
<body>
  <header class="header">
    <div class="contenedor">
      <h1>EcoSunTech S.A.</h1>
      <img src="https://www.shutterstock.com/image-vector/letter-d-luxury-logo-sign-260nw-1635753427.jpg">
      <p>Soluciones de Energía Solar</p>
      <nav class="menu">
        <a href="#inicio">Inicio</a>
        <a href="#productos">Productos</a>
        <a href="#servicios">Servicios</a>
        <a href="#nosotros">Acerca de</a>
        <a href="#contacto">Contacto</a>
      </nav>
    </div>
  </header>

  <main>
    <section id="inicio" role="region" aria-labelledby="inicio">
      <div class="contenido">
        <h2 class="subtitulo">Bienvenidos a EcoSunTech</h2>
        
        <figure>
          <picture>
            <source srcset="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRprjb0Jtz431o8ViFudr0wgHTNMeu9TrwRhw&s" media="(max-width: 600px)">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRprjb0Jtz431o8ViFudr0wgHTNMeu9TrwRhw&s" class="card" alt="Paneles solares a plena luz del día">
          </picture>
          <figcaption>Paneles solares trabajando bajo el sol.</figcaption>
        </figure>
        
        <p>En EcoSunTech trabajamos por un futuro más limpio, brindando acceso a tecnologías solares modernas y accesibles para todos.</p>
      </div>
    </section>

    <hr>

    <section id="productos" role="region" aria-labelledby="productos">
      <div class="contenido">
        <h2 class="subtitulo">Nuestros Productos</h2>
        
        <figure>
          <img src="https://sotysolar.es/imgcache/1200x1200png/kaxa7mejtvjxzmroctbf.jpg" alt="Inversores solares modernos" usemap="#productos-map">
          <figcaption>Inversores solares modernos</figcaption>
          <map name="productos-map">
            <area shape="rect" coords="0,0,200,200" href="#panel-solar" alt="Panel Solar" title="Panel Solar">
            <area shape="rect" coords="210,0,400,200" href="#inversor-solar" alt="Inversor Solar" title="Inversor Solar">
          </map>
        </figure>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/gpyxTDt18o0?si=5dSa8H9Jix90nkMQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

        <h3>Especificaciones de nuestros productos</h3>
        <table>
          <thead>
            <tr>
              <th>Producto</th>
              <th>Especificaciones</th>
              <th>Precio</th>
              <th>Disponibilidad</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Panel Solar EcoPro 500W</td>
              <td>Alta eficiencia y durabilidad para climas exigentes.</td>
              <td>$500</td>
              <td>Disponible</td>
            </tr>
            <tr>
              <td>Inversor Solar X3</td>
              <td>Convierte energía solar en electricidad lista para el hogar.</td>
              <td>$350</td>
              <td>Disponible</td>
            </tr>
            <tr>
              <td>Batería Solar PowerBox</td>
              <td>Almacenamiento confiable para uso nocturno o días nublados.</td>
              <td>$250</td>
              <td>Agotado</td>
            </tr>
            <tr>
              <td>Controlador de Carga Inteligente</td>
              <td>Protege tu sistema solar y mejora su rendimiento.</td>
              <td>$120</td>
              <td>Disponible</td>
            </tr>
          </tbody>
        </table>
        <h3>Solicita una cotización</h3>
<form action="mailto:contacto@ecosuntech.com" method="post" enctype="text/plain">
  <p>
    <label for="nombre-cotizacion">Nombre:</label><br>
    <input type="text" id="nombre-cotizacion" name="nombre" placeholder="Tu nombre completo" required>
  </p>
  <p>
    <label for="email-cotizacion">Correo electrónico:</label><br>
    <input type="email" id="email-cotizacion" name="email" placeholder="ejemplo@correo.com" required>
  </p>
  <p>
    <label for="producto">Producto de interés:</label><br>
    <select id="producto" name="producto">
      <option value="EcoPro 500W">Panel Solar EcoPro 500W</option>
      <option value="Inversor X3">Inversor Solar X3</option>
      <option value="PowerBox">Batería Solar PowerBox</option>
      <option value="Controlador">Controlador de Carga Inteligente</option>
    </select>
  </p>
  <p>
    <label for="mensaje-cotizacion">Mensaje adicional:</label><br>
    <textarea id="mensaje-cotizacion" name="mensaje" rows="4" placeholder="Incluye detalles como cantidad, uso, etc."></textarea>
  </p>
  <input type="submit" value="Solicitar cotización">
</form>


        <p>Consulta nuestras ofertas para obtener más información sobre precios y disponibilidad.</p>
      </div>
    </section>

    <hr>

    <section id="servicios" role="region" aria-labelledby="servicios">
      <div class="contenido">
        <div class="contenido card">
        <h2 class="subtitulo">Nuestros Servicios</h2>
        
        <figure class="animacion-svg">
          <svg width="100" height="100">
            <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="blue" />
          </svg>
          <figcaption>Instalación profesional de paneles solares</figcaption>
        </figure>

        <p>Instalación profesional, mantenimiento periódico y asesoría personalizada para cada cliente.</p>

        <h3>Testimonios de nuestros clientes</h3>
        <p>“Gracias a EcoSunTech, mi casa ahora funciona 100% con energía solar. ¡Excelente servicio!” – Ana M.</p>
        <p>“Profesionales, responsables y con buenos precios. ¡Totalmente recomendados!” – Luis R.</p>
      </div>
    </section>

    <hr>

    <section id="nosotros" role="region" aria-labelledby="nosotros">
      <div class="contenido">
        <h2 class="subtitulo">Acerca de Nosotros</h2>
        <figure>
          <img src="https://cdn.prod.website-files.com/5f0e313047b8f9130dd8eb8a/5ffe1ccd120792be17ff2f58_responsabilidad-galt-energy.jpeg" alt="Equipo de trabajo de EcoSunTech">
          <figcaption>El equipo de EcoSunTech trabajando juntos.</figcaption>
        </figure>

        <h3>Misión</h3>
        <p>Proveer soluciones de energía solar eficientes y sostenibles que mejoren la vida de nuestros clientes.</p>

        <h3>Visión</h3>
        <p>Ser líderes en el sector solar en el Perú, promoviendo un futuro más verde.</p>

        <h3>Valores</h3>
        <ul>
          <li>Compromiso ambiental</li>
          <li>Calidad</li>
          <li>Innovación</li>
          <li>Transparencia</li>
        </ul>

        <h3>¿Quiénes somos?</h3>
        <p>EcoSunTech es una empresa peruana con experiencia en sistemas solares residenciales y comerciales.</p>

        <h3>Nuestras capacidades</h3>
        <p>Contamos con un equipo técnico especializado, soporte post-venta y una red de distribución nacional.</p>
      </div>
    </section>

    <hr>

    <section id="contacto" role="region" aria-labelledby="contacto">
      <div class="contenido">
        <h2 class="subtitulo">Contáctanos</h2>
        <form action="#" method="post">
          <p>
            <label for="nombre">Nombre completo</label><br>
            <input type="text" id="nombre" name="nombre" placeholder="Nombre completo" required>
          </p>
          <p>
            <label for="email">Correo electrónico</label><br>
            <input type="email" id="email" name="email" placeholder="Correo electrónico" required>
          </p>
          <p>
            <label for="mensaje">Mensaje</label><br>
            <textarea id="mensaje" name="mensaje" rows="5" placeholder="Escribe tu mensaje..." required></textarea>
          </p>
          <input type="submit" value="Enviar mensaje">
        </form>
      </div>
    </section>

  </main>

  <footer class="footer">
    <p>© 2025 EcoSunTech - Todos los derechos reservados</p>
  </footer>
</body>
</html>
