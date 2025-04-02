<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Impresiones</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 400px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
        }
        select, input {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            padding: 10px 20px;
            border: none;
            background-color: #28a745;
            color: white;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #218838;
        }
        #resultado {
            font-size: 20px;
            font-weight: bold;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Calculadora de Impresiones</h2>

        <label>Selecciona un producto:</label>
        <select id="producto" onchange="actualizarPrecio()">
            <option value="" disabled selected>-- Selecciona un producto --</option>
            <option value="15000">Tela de PVC - $15,000</option>
            <option value="15000">Adhesivo sin laminado - $15,000</option>
            <option value="20000">Adhesivo laminado - $20,000</option>
            <option value="25000">Onevision - $25,000</option>
            <option value="25000">Backlight - $25,000</option>
            <option value="20000">Adhesivo troquelado - $20,000</option>
            <option value="60000">Trovicel con adhesivo laminado - $60,000</option>
        </select>

        <label>Ancho (cm):</label>
        <input type="number" id="ancho" placeholder="Ej: 120">

        <label>Alto (cm):</label>
        <input type="number" id="alto" placeholder="Ej: 80">

        <label>Precio por metro cuadrado ($):</label>
        <input type="number" id="precio" placeholder="Ej: 15000" readonly>

        <button onclick="calcular()">Calcular Precio</button>

        <p id="resultado"></p>
    </div>

    <script>
        function actualizarPrecio() {
            let precioSeleccionado = document.getElementById("producto").value;
            document.getElementById("precio").value = precioSeleccionado;
        }

        function calcular() {
            let anchoCm = parseFloat(document.getElementById("ancho").value);
            let altoCm = parseFloat(document.getElementById("alto").value);
            let precio = parseFloat(document.getElementById("precio").value);

            if (isNaN(anchoCm) || isNaN(altoCm) || isNaN(precio)) {
                document.getElementById("resultado").innerHTML = "⚠️ Ingresa valores válidos.";
                return;
            }

            // Convertimos cm a metros (100 cm = 1 metro)
            let anchoM = anchoCm / 100;
            let altoM = altoCm / 100;
            let area = anchoM * altoM;
            let total = area * precio;

            document.getElementById("resultado").innerHTML = `El precio total es: <strong>$${total.toLocaleString()}</strong>`;
        }
    </script>

</body>
</html>
