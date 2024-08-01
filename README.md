<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descargar Contacto</title>
    <style>
        body {
            background-color: #f0f0f0; /* Color de fondo */
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        header {
            background-color: #4CAF50; /* Color del encabezado */
            padding: 20px;
            color: white;
        }
        header img {
            max-width: 100px;
            height: auto;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 20px 0;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <img src="ruta/al/logo.png" alt="Logo"> <!-- Reemplaza con la ruta a tu logo -->
        <h1>Descargar Contacto</h1>
    </header>
    <p>Haz clic en el botón de abajo para descargar el contacto.</p>
    <button id="downloadBtn">Descargar Contacto</button>

    <script>
        document.getElementById('downloadBtn').addEventListener('click', function() {
            var link = document.createElement('a');
            link.href = 'JuanCarlosMontesJuarez.vcf'; // Ruta al archivo vCard
            link.download = 'JuanCarlosMontesJuarez.vcf'; // Nombre del archivo que se descargará
            link.click();
        });
    </script>
</body>
</html>
