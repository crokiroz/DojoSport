<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descargar Contacto</title>
</head>
<body>
    <h1>Descargar Contacto</h1>
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
