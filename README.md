<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Practica HTML5</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>

    <div id="inicio">
        <header id="cabecera">
            <h1>Practica de Estructura HTML5</h1>
            <p>Este es un texto de prueba para la cabecera de la pagina web. Aqui se muestra el primer bloque de la estructura basica solicitada en la actividad.</p>
            <a href="#" onclick="verCatalogo()">Ver catalogo de equipo de computo</a>
        </header>

        <section id="seccion1">
            <h2>Seccion de articulos</h2>
            <p>Texto aleatorio dentro de la seccion principal para diferenciar el espacio de la seccion y el de los articulos.</p>

            <article id="art1">
                <h3>Articulo 1</h3>
                <p>Texto aleatorio para el primer articulo de la pagina. Tiene asignado un color de fondo distinto desde el archivo de estilos.</p>
            </article>

            <article id="art2">
                <h3>Articulo 2</h3>
                <p>Texto aleatorio para el segundo articulo. En este bloque se cambio el color de fondo por una imagen utilizando CSS.</p>
            </article>
        </section>

        <section id="enlaces">
            <h2>Sitios de interes</h2>
            <ul>
                <li><a href="https://www.google.com" target="_blank">Google</a></li>
                <li><a href="https://es.wikipedia.org" target="_blank">Wikipedia</a></li>
                <li><a href="https://www.youtube.com" target="_blank">YouTube</a></li>
                <li><a href="https://github.com" target="_blank">GitHub</a></li>
                <li><a href="https://www.w3schools.com" target="_blank">W3Schools</a></li>
            </ul>
        </section>

        <footer id="pie">
            <p>Texto de ejemplo en el pie de pagina para completar la estructura basica de HTML5.</p>
        </footer>
    </div>

    <div id="catalogo" style="display: none;">
        <header id="cabecera-cat">
            <img src="https://cdn-icons-png.flaticon.com/512/3067/3067260.png" alt="Logo" width="50">
            <h1>CompuSinaloa</h1>
            <h2>Alondra Jazmin Meza Gonzalez</h2>
            <a href="#" onclick="verInicio()">Regresar a la pagina anterior</a>
        </header>

        <section id="seccion-catalogo">
            <h2>Equipos disponibles</h2>
            <div id="contenedor-articulos"></div>
        </section>

        <footer id="pie-cat">
            <p><span id="anio"></span> - Desarrollo Web Lado del Cliente</p>
        </footer>
    </div>

    <script src="script.js"></script>
</body>
</html>