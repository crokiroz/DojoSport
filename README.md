<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOJO SPORT - Descargar Contacto</title>
    <style>
        body {
            background-color: #000000; /* Fondo negro */
            font-family: Arial, sans-serif;
            text-align: center;
            color: white;
            padding: 20px;
        }
        header {
            background-color: #c59a4a; /* Color dorado */
            padding: 20px;
            color: white;
        }
        header img {
            max-width: 100px;
            height: auto;
        }
        button {
            background-color: #c59a4a;
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
            background-color: #b5893e;
        }
        .contact-info {
            margin: 20px 0;
            text-align: left;
            display: inline-block;
        }
        .contact-info p {
            margin: 10px 0;
        }
        .contact-info img {
            vertical-align: middle;
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo dojo sport.png" alt="Logo Dojo Sport"> <!-- Ruta al logo -->
        <h1>DOJO SPORT</h1>
    </header>
    <div class="contact-info">
        <p><img src="iconos/nombre.png" alt="Nombre" width="20"> Juan Carlos Montes Juarez</p>
        <p><img src="iconos/organizacion.png" alt="Organización" width="20"> Dojo Sport</p>
        <p><img src="iconos/titulo.png" alt="Título" width="20"> Sensei c.n. 8º dan</p>
        <p><img src="iconos/telefono.png" alt="Teléfono" width="20"> 55-9198-6630</p>
        <p><img src="iconos/telefono.png" alt="Teléfono" width="20"> 55-4623-2920</p>
        <p><img src="iconos/email.png" alt="Email" width="20"> j.carlosmontesjz@gmail.com</p>
    </div>
    <button id="downloadBtn">
        <img src="iconos/descargar.png" alt="Descargar" width="20"> Descargar Contacto
    </button>

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
