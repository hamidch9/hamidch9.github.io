<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ali Supermercado</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .product {
            display: inline-block;
            width: 30%;
            margin: 1%;
            background-color: white;
            padding: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product h3 {
            margin-top: 10px;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ali Supermercado</h1>
        <p>Tu tienda de confianza</p>
    </header>
    
    <div class="container">
        <h2>Productos Destacados</h2>
        
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Producto 1">
            <h3>Producto 1</h3>
            <p>Descripción del producto 1</p>
        </div>
        
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Producto 2">
            <h3>Producto 2</h3>
            <p>Descripción del producto 2</p>
        </div>
        
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Producto 3">
            <h3>Producto 3</h3>
            <p>Descripción del producto 3</p>
        </div>
    </div>
</body>
</html>
