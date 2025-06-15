<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>¿Qué es NemorIA?</title>
    <style>
        /* Estilos generales */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #e3f2fd, #ffffff);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .card {
            background-color: #ffffff;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            padding: 40px;
            max-width: 700px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        h1 {
            color: #2c3e50;
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2em;
            line-height: 1.6;
            color: #444;
            margin-bottom: 15px;
        }

        strong {
            color: #0077cc;
        }

        .nota-desarrollo {
            margin-top: 30px;
            font-size: 0.95em;
            color: #888;
            font-style: italic;
        }

        @media (max-width: 600px) {
            .card {
                padding: 25px;
            }

            h1 {
                font-size: 2em;
            }

            p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>¿Qué es NemorIA?</h1>
        <p><strong>NemorIA</strong> es una aplicación basada en inteligencia artificial enfocada en ayudarte a organizarte y tomar mejores decisiones. Está diseñada para apoyar a personas en la gestión de su tiempo, tareas y objetivos personales o profesionales.</p>
        <p>Su objetivo es utilizar la inteligencia artificial de forma práctica y responsable para facilitar la toma de decisiones y mejorar la productividad y el equilibrio personal.</p>
        <p class="nota-desarrollo">Nota: Esta aplicación aún se encuentra en desarrollo.</p>
    </div>
</body>
</html>
