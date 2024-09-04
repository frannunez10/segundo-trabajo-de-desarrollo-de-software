<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Práctico CSS - Desarrollo de Software</title>
    <style>
        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        p {
            font-size: 16px;
            text-align: justify;
        }

        /* 4.1 Cabecera con párrafo y blockquote */
        .header {
            padding: 20px;
            text-align: center;
        }
        blockquote {
            font-size: 20px;
            font-style: italic;
            text-align: center;
            margin: 20px auto;
            color: #666;
            border-left: 5px solid #ddd;
            padding-left: 15px;
        }

        /* 4.3 Propiedades de Caja */
        .box-container {
            display: flex;
            justify-content: space-around;
            margin: 20px;
        }
        .box {
            width: 200px;
            height: 200px;
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }
        .box.highlight {
            border: 3px solid #ff5722;
            background-color: #ffccbc;
        }

        /* 4.4 Posicionamiento Relativo y Absoluto */
        .relative {
            position: relative;
            width: 300px;
            height: 200px;
            margin: 20px auto;
            background-color: #ffeb3b;
            padding: 20px;
        }
        .absolute {
            position: absolute;
            top: 50px;
            left: 50px;
            width: 100px;
            height: 100px;
            background-color: #4caf50;
            color: white;
            text-align: center;
            line-height: 100px;
        }

        /* 4.5 Media Queries */
        @media (max-width: 768px) {
            body {
                background-color: #333;
                color: white;
            }
            h1 {
                font-size: 24px;
            }
        }

        /* 4.6 Principios de Grid */
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 10px;
            padding: 20px;
        }
        .grid-item {
            background-color: #ff9800;
            padding: 20px;
            text-align: center;
            color: white;
        }

        /* 4.7 Animaciones */
        .animacion {
            width: 100px;
            height: 100px;
            background-color: #009688;
            margin: 20px auto;
            transition: background-color 0.5s ease;
        }
        .animacion:hover {
            background-color: #e91e63;
        }
        @keyframes mover {
            0% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(300px);
            }
        }
        .mover {
            width: 100px;
            height: 100px;
            background-color: #3f51b5;
            margin: 20px auto;
            animation: mover 2s infinite alternate;
        }
    </style>
</head>
<body>

    <h1>Práctico CSS - Desarrollo de Software</h1>

    <!-- 4.1 Cabecera -->
    <div class="header">
        <p>Este es un párrafo introductorio sobre el trabajo práctico. El objetivo es aplicar diferentes propiedades de CSS para estilizar elementos HTML y demostrar su correcto uso.</p>
        <blockquote>"El diseño web no es solo sobre cómo se ve, sino también sobre cómo funciona."</blockquote>
    </div>

    <!-- 4.3 Propiedades de Caja -->
    <div class="box-container">
        <div class="box">Caja 1</div>
        <div class="box highlight">Caja 2 (destacada)</div>
    </div>

    <!-- 4.4 Posicionamiento Relativo y Absoluto -->
    <div class="relative">
        Contenedor relativo
        <div class="absolute">Caja absoluta</div>
    </div>

    <!-- 4.6 Principios de Grid -->
    <div class="grid-container">
        <div class="grid-item">Item 1</div>
        <div class="grid-item">Item 2</div>
        <div class="grid-item">Item 3</div>
        <div class="grid-item">Item 4</div>
    </div>

    <!-- 4.7 Animaciones -->
    <div class="animacion"></div>
    <div class="mover"></div>

</body>
</html>
