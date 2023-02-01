<!DOCTYPE html>
<html>
  <head>
    <title>Mi Currículum</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <header>
      <h1>Gonzalo Martinez</h1> <img src="https://img.a.transfermarkt.technology/portrait/big/281405-1583435145.JPG?lm=1" alt="" width="50px">
      <p>futbolista</p>
    </header>
    <section>
      <h2>1143874509</h2>
      <p>Correo electrónico: gonza912@gmail.com</p>
      <p>Teléfono: 123-456-7890</p>
      <p>Dirección: 123 Cabildo y Gral Paz</p>
    </section>
    <section>
      <h2>Educación <button id="educacionBtn">Mostrar más</button></h2>
      <div id="educacionInfo" style="display:none;">
        <h3>UADE</h3>
        <p>Grado en Ingenieria, 09/12/18</p>
        
        <p>Licenciado en Bellas Artes, 23/9/99</p>
      </div>
    </section>
    <section>
      <h2>Experiencia Laboral <button id="experienciaBtn">Mostrar más</button></h2>
      <div id="experienciaInfo" style="display:none;">
        <h3>Caño.dot</h3>
        <p>Puesto, gerente general</p>
        <p>gerente general de la revista deportiva "caño.dot"</p>
        
      </div>
    </section>
    <section>
      <h2>Habilidades</h2>
      <ul>
        <li>Habilidades interpersonales</li>
        <li>Gambeta</li>
        <li>Lectura del juego</li>
      </ul>
    </section>
    <script src="script.js"></script>

    <h2>Contacto</h2>
<form>
  <label for="nombre">Nombre:</label>
     <input type="text" id="nombre" name="nombre" required>

  <label for="email">Email:</label>
     <input type="email" id="email" name="email" required>

  <label for="mensaje">Mensaje:</label>
     <textarea id="mensaje" name="mensaje" rows="5" required></textarea>

  <input type="submit" value="Enviar">

</form>

  </body>
</html>
