# Rio-concordia
Información en tiempo real del rio concordia 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🌊 Río Concordia</title>

    <link rel="stylesheet" href="style.css">

    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>

<body>

<header>
    <h1>🌊 Río Concordia</h1>
    <p>Información del Río Uruguay en Tiempo Real</p>
</header>

<main>

<section class="card principal">

<h2>Altura actual</h2>

<div id="altura">
--.-- m
</div>

<div id="tendencia">
Esperando datos...
</div>

<div id="estado">
Estado desconocido
</div>

</section>

<section class="card">

<h2>📈 Evolución</h2>

<canvas id="grafico"></canvas>

</section>

<section class="card">

<h2>💧 Información</h2>

<p><strong>Caudal:</strong> <span id="caudal">--</span></p>

<p><strong>Última actualización:</strong>
<span id="hora">--</span></p>

</section>

</main>

<footer>

Datos obtenidos del Instituto Nacional del Agua (INA)

</footer>

<script src="app.js"></script>

</body>
</html>
