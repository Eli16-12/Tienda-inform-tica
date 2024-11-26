<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>Bienvenidos a nuestra Tienda de Informática</h1>
        <p><em>Equipos, accesorios y más, ¡todo lo que necesitas en informática!</em></p>
    </header>
    <nav>
        <ul>
            <li><a href="index.html" title="Página principal">Inicio</a></li>
            <li><a href="productos.html" title="Ver productos">Productos</a></li>
            <li><a href="ofertas.html" title="Ver ofertas">Ofertas</a></li>
            <li><a href="contacto.html" title="Atención al cliente">Contacto</a></li>
        </ul>
    </nav>
    <section>
        <h2>Productos Destacados</h2>
        <p>Te ofrecemos una amplia gama de productos, desde portátiles hasta componentes para tu PC. ¡Explora nuestra página!</p>
        <ul>
            <li><a href="productos.html#portatil" title="Ver portatil Xtreme">Portatil Xtreme</a></li>
            <li><a href="productos.html#monitor" title="Ver monitor UltraView">Monitor UltraView</a></li>
            <li><a href="productos.html#teclado" title="Ver teclado">Teclado</a></li>
            <li><a href="productos.html#ratón" title="Ver ratón">Ratón</a></li>
        </ul>
        <img src="https://github.com/Eli16-12/Tienda-inform-tica/blob/main/imagen89d921aac7337a84da709e90e219e207.jpg" alt="Vista de nuestra tienda" title="Tienda de informática">
    </section>
    <footer>
        <p>&copy; 2024 Tienda de Informática. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>Productos de la tienda</h1>
    </header>
    <section>
        <h2>Nuestros Productos</h2>
        <article id="portatil">
            <h3>Portatil Xtreme 15</h3>
            <img src="https://github.com/Eli16-12/Tienda-inform-tica/blob/main/modelo-acer-1.jpg" alt="Portatil Xtreme 15" title="Portatil Xtreme 15">
            <p><strong>Precio:</strong>699.90€</p>
            <p><em>Potente, ligero y con la última tecnología, ideal para profesionales y gamers.</em></p>
        </article>
        <article id="monitor">
            <h3>Monitor UltraView 27"</h3>
            <img src="https://github.com/Eli16-12/Tienda-inform-tica/blob/main/450_1000.jpg" alt="Monitor UltraView 27" title="Monitor UltraView 27">
            <p><strong>Precio:</strong>300€</p>
            <p><em>Con una resolución 4K y una pantalla amplia para una experiencia visual sin igual.</em></p>
        </article>
         <article id="teclado">
            <h3>Teclado</h3>
            <img src="https://github.com/Eli16-12/Tienda-inform-tica/blob/main/611g0QNYpQL._AC_UF894%2C1000_QL80_.jpg" alt="Teclado" title="Teclado">
            <p><strong>Precio:</strong>75€</p>
            <p><em>Ligero y con la última tecnología en teclados.</em></p>
        </article>
         <article id="ratón">
            <h3>Ratón</h3>
            <img src="https://github.com/Eli16-12/Tienda-inform-tica/blob/main/51piJTmCqlL.jpg" alt="Ratón" title="Ratón">
            <p><strong>Precio:</strong>50€</p>
            <p><em>Ratón óptico inalámbrico, ligero y cómodo.</em></p>
        </article>
    </section>
    <footer>
        <p>&copy; 2024 Tienda de Informática. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>Ofertas</h1>
    </header>
    <section>
        <h2>Ofertas por tiempo limitado</h2>
        <p><b>¡No te pierdas nuestras promociones de black friday!</b></p>
        <ul>
            <li><a href="productos.html#portatil" title="Portatil Xtreme en oferta">Portatil Xtreme 15 - 699.90€ (¡Ahorra 100€!)</a></li>
            <li><a href="productos.html#monitor" title="Monitor UltraView 27 en oferta">Monitor UltraView 27" - 300€(¡Ahorra 50€!)</a></li>
        </ul>
    </section>
    <footer>
        <p>&copy; 2024 Tienda de Informática. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>Contáctanos</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html" title="Página principal">Inicio</a></li>
            <li><a href="productos.html" title="Ver productos">Productos</a></li>
            <li><a href="ofertas.html" title="Ver ofertas">Ofertas</a></li>
            <li><a href="contacto.html" title="Atención al cliente">Contacto</a></li>
        </ul>
    </nav>
    <section>
        <h2>Formulario de Contacto</h2>
        <form action="enviar_contacto.php" method="POST">
            <label for="nombre">Nombre:</label><br>
            <input type="text" id="nombre" name="nombre" required><br><br>
            <label for="email">Correo Electrónico:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="mensaje">Mensaje:</label><br>
            <input type="submit" value="Enviar">
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Tienda de Informática. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

