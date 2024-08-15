<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automotores Navarra</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #444;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        .logo {
            max-width: 150px;
            margin: 20px auto;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .car {
            background-color: white;
            margin: 20px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
        }

        .car img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Automotores Navarra</h1>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Vehículos</a>
        <a href="#">Contacto</a>
        <a href="#">Sobre Nosotros</a>
    </nav>

    <div class="container">
        <div class="car">
            <img src="https://via.placeholder.com/400" alt="Auto 1">
            <h2>Auto 1</h2>
            <p>Descripción del auto.</p>
            <p>Precio: $10,000</p>
        </div>

        <div class="car">
            <img src="https://via.placeholder.com/400" alt="Auto 2">
            <h2>Auto 2</h2>
            <p>Descripción del auto.</p>
            <p>Precio: $15,000</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Automotores Navarra. Todos los derechos reservados.</p>
    </footer>

</body>
</html>

