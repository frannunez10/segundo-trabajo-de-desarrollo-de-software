<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Práctico CSS - Desarrollo de Software</title>
    <style>
        /* Estilos para la cabecera */
        header {
            padding: 20px;
            background-color: #f4f4f4;
            text-align: center;
        }

        header p {
            font-size: 20px;
            text-align: center;
            text-transform: uppercase;
            text-decoration: underline;
            margin-bottom: 10px;
        }

        header blockquote {
            font-size: 18px;
            text-align: right;
            font-style: italic;
            border-left: 5px solid #ccc;
            padding-left: 10px;
        }

        /* Estilos para las cajas */
        .box-container {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
        }

        .box {
            padding: 20px;
            margin: 10px;
            border: 2px solid #000;
            box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.1);
            background-color: #e0e0e0;
            width: 150px;
            text-align: center;
        }

        .box.highlight {
            border: 4px solid #f00;
            background-color: #ffd700;
        }

        /* Estilos para la posición relativa y absoluta */
        .relativo {
            position: relative;
            margin: 20px;
            padding: 20px;
            background-color: #add8e6;
        }

        .absoluto {
            position: absolute;
            top: 10px;
            left: 10px;
            background-color: #ff6347;
            padding: 10px;
        }

        /* Estilos para grid */
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin: 20px 0;
            padding: 20px;
            background-color: #f0f8ff;
        }

        .grid-item {
            background-color: #87cefa;
            padding: 20px;
            text-align: center;
            border: 2px solid #000;
        }

        /* Estilos para la animación */
        .animacion {
            width: 100px;
            height: 100px;
            background-color: #4682b4;
            transition: background-color 0.5s ease;
        }

        .animacion:hover {
            background-color: #5f9ea0;
        }

        @keyframes mover {
            0% { transform: translateX(0); }
            100% { transform: translateX(100%); }
        }

        .mover {
            width: 100px;
            height: 100px;
            background-color: #8a2be2;
            animation: mover 2s infinite alternate;
        }

        /* Media Queries */
        @media (max-width: 768px) {
            body {
                background-color: #f0e68c;
            }

            h1 {
                font-size: 24px;
            }

            .box-container, .grid-container {
                flex-direction: column;
                gap: 10px;
                padding: 10px;
            }
        }
    </style>
</head>
<body>

    <header>
        <p>Bienvenido al Práctico de Desarrollo de Software</p>
        <blockquote>"El desarrollo web es un arte, la funcionalidad es su esencia."</blockquote>
    </header>

    <section class="box-container">
        <div class="box">Caja 1</div>
        <div class="box highlight">Caja 2</div>
    </section>

    <section class="relativo">
        Este es un contenedor con posición relativa.
        <div class="absoluto">Caja con posición absoluta</div>
    </section>

    <section class="grid-container">
        <div class="grid-item">Elemento 1</div>
        <div class="grid-item">Elemento 2</div>
        <div class="grid-item">Elemento 3</div>
        <div class="grid-item">Elemento 4</div>
    </section>

    <section>
        <div class="animacion"></div>
        <div class="mover"></div>
    </section>

</body>
</html>
