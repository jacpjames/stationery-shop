# stationery-shop
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stationery Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #444;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav li {
            display: inline;
            margin: 0 20px;
        }
        .container {
            max-width: 960px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
        }
        .product {
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ccc;
            background-color: #fff;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Stationery Shop</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Products</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <div class="container">
        <div class="product">
            <img src="pen.jpg" alt="Pen">
            <h2>Premium Ballpoint Pen</h2>
            <p>High-quality ballpoint pen for smooth writing.</p>
            <p>Price: $2.99</p>
        </div>
        <div class="product">
            <img src="notebook.jpg" alt="Notebook">
            <h2>Hardcover Notebook</h2>
            <p>Stylish hardcover notebook with lined pages.</p>
            <p>Price: $4.99</p>
        </div>
        <div class="product">
            <img src="pencil.jpg" alt="Pencil">
            <h2>Wooden Pencils</h2>
            <p>Set of 12 high-quality wooden pencils.</p>
            <p>Price: $3.49</p>
        </div>
    </div>
    <footer>
        &copy; 2023 Stationery Shop. All rights reserved.
    </footer>
</body>
</html>
