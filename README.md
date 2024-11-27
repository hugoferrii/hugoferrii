<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Productos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #222;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        main {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
        }
        .product {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product h3 {
            margin: 1rem 0 0.5rem;
            font-size: 1.2rem;
        }
        .product p {
            padding: 0 1rem;
            color: #555;
        }
        .product button {
            background-color: #007bff;
            color: #fff;
            border: none;
            padding: 0.75rem 1rem;
            margin: 1rem;
            font-size: 1rem;
            border-radius: 4px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #0056b3;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #222;
            color: #fff;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tienda de Productos Recomendados</h1>
    </header>
    <main>
        <!-- Producto 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/300x200" alt="Producto 1">
            <h3>Eroxcel</h3>
            <p>Un suplemento que mejora tu vitalidad.</p>
            <button onclick="window.location.href='https://eroxcel.com/latam-vsl#aff=hugoferrii_'">Comprar</button>
        </div>
        <!-- Producto 2 -->
        <div class="product">
            <img src="https://via.placeholder.com/300x200" alt="Producto 2">
            <h3>Producto Digital</h3>
            <p>Descubre un método innovador para mejorar tu vida.</p>
            <button onclick="window.location.href='https://www.digistore24.com/redir/447828/hugoferrii_/'">Comprar</button>
        </div>
    </main>
    <footer>
        <p>© 2024 Tu Tienda Online. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
