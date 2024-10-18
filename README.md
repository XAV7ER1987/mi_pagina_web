<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transforma tu Salud - Nutrición y Bienestar</title>
    <link rel="stylesheet" href="styles.css"> <!-- Añadir estilos -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .hero {
            background-image: url('tu-imagen-destacada.jpg'); /* Imagen de fondo atractiva */
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }
        .cta-buttons {
            margin-top: 20px;
        }
        .cta-buttons a {
            background-color: #FF5733;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin: 10px;
            font-size: 1.2rem;
        }
        .cta-buttons a:hover {
            background-color: #C70039;
        }
        main {
            padding: 20px;
        }
        .productos-destacados {
            display: flex;
            justify-content: space-around;
        }
        .producto {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 30%;
            text-align: center;
        }
        .producto img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenido a tu Camino hacia la Salud y el Bienestar</h1>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="about.html">Sobre mí</a></li>
                <li><a href="blog.html">Blog</a></li>
                <li><a href="planes.html">Planes de nutrición</a></li>
                <li><a href="contact.html">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <div class="hero">
        <h1>Transforma tu Salud Hoy</h1>
        <p>Descubre cómo la nutrición celular puede cambiar tu vida.</p>
        <div class="cta-buttons">
            <a href="planes.html">Explora Nuestros Planes</a>
            <a href="contact.html">Consulta Gratis</a>
        </div>
    </div>

    <main>
        <h2>Productos Destacados</h2>
        <div class="productos-destacados">
            <div class="producto">
                <img src="producto1.jpg" alt="Producto 1">
                <h3>Omega-3 Herbalifeline® Max</h3>
                <p>Cuida tu salud cardiovascular con los beneficios de los ácidos grasos esenciales.</p>
            </div>
            <div class="producto">
                <img src="producto2.jpg" alt="Producto 2">
                <h3>Fórmula 1 - Batido Nutricional</h3>
                <p>Alimento completo para el día a día. Mejora tu energía y bienestar.</p>
            </div>
            <div class="producto">
                <img src="producto3.jpg" alt="Producto 3">
                <h3>CR7 Drive</h3>
                <p>Hidratación avanzada y energía para un rendimiento óptimo en cada deporte.</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2024 Blog de Nutrición y Bienestar - Todos los derechos reservados</p>
        <p>Síguenos en <a href="https://tiktok.com/@Maurowolf" target="_blank">TikTok</a> y <a href="https://tiktok.com/@Xav7er" target="_blank">TikTok</a></p>
    </footer>

</body>
</html>
