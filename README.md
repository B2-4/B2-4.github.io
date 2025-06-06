Mir primer citio web

<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Menú Rosa Simple</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      display: flex;
      height: 100vh;
      background-color: #fce4ec; /* fondo rosado claro */
    }

    .contenido {
      flex: 1;
      padding: 20px;
      background-color: #f8bbd0; /* rosado intermedio */
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .contenido-box {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      width: 80%;max-width: 500px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      color: #880e4f;
    }

    .menu {
      width: 200px;
      background-color: #f06292; /* rosa fuerte */
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 10px;
      gap: 10px;
    }

    .menu button {
      background-color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      color: #880e4f;
      font-weight: bold;
      cursor: pointer;
    }
.menu button:hover {
      background-color: #f8bbd0;
    }
  </style>
</head>
<body>

  <!-- Contenido que cambia -->
  <div class="contenido" id="pantalla">
    <div class="contenido-box">
      <h2>Bienvenida 💖</h2>
      <p>Haz clic en una página del menú.</p>
    </div>
  </div>
 <!-- Menú de botones -->

  <div class="menu">
    <a href="1)NOMBRE DE LA EMPRESA.html">NOMBRE</a>
    <a href="2)QUIENES SOMOS.html">QUIENES SOMOS</a>
    <a href="3)HISTORIA.html">HISTORIA</a>
    <a href="4)GALERIA FOTOGRAFIAS.html">FOTOGRAFIAS</a>
    <a href="5)GALERIA DE VIDEOS.html">VIDEOS</a>
    <a href="6)DESCRIPCION DE PRODUCTOS.html">PRODUCTOS</a>
    <a href="7)DATOS DE CONTACTO.html">DATOS DE CONTACTO</a>
    <a href="8)DISTRIBUCIÓN.html">DISTRIBUCION</a>
  </div>
</body>
</html>
![image](https://github.com/user-attachments/assets/e83ad4aa-8920-4fc5-85dc-76f0bcf8cf30)
