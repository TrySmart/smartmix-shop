<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smartmix Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
            color: #333;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        header {
            background: #333;
            color: white;
            padding: 20px;
            text-align: center;
            animation: fadeInDown 1s ease-in-out;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            animation: fadeInUp 1s ease-in-out;
        }
        .product {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            width: 300px;
            margin: 20px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .product:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
        }
        .product img {
            max-width: 100%;
            border-bottom: 1px solid #ddd;
            padding-bottom: 15px;
            margin-bottom: 15px;
            transition: transform 0.3s;
        }
        .product:hover img {
            transform: scale(1.05);
        }
        .product h3 {
            margin: 0;
            font-size: 1.5em;
        }
        .product p {
            font-size: 1em;
            color: #666;
        }
        .product .price {
            font-size: 1.2em;
            color: #333;
            margin: 10px 0;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 1em;
            color: white;
            background: #333;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s, transform 0.3s;
        }
        .button:hover {
            background: #555;
            transform: scale(1.05);
        }
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Smartmix Shop</h1>
    </header>
    <div class="container">
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Produktbild">
                <h3>Speed Up Mix Album</h3>
                <p>Genieße unsere besten schnellen Mixes in einem Album.</p>
                <div class="price">€9.99</div>
                <a class="button" href="#">Kaufen</a>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Produktbild">
                <h3>Slow Down Mix Album</h3>
                <p>Entspanne mit unseren beruhigenden Mixes in diesem Album.</p>
                <div class="price">€9.99</div>
                <a class="button" href="#">Kaufen</a>
            </div>
        </div>
    </div>
</body>
</html>
