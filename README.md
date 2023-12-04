<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Black Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em;
            text-align: center;
        }
        section {
            padding: 2em;
        }
        #product-display {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            justify-content: space-around;
        }
        .product {
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border: 2px solid #fff;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 1em;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Black Website</h1>
        <form action="#" method="get">
            <label for="search">Search:</label>
            <input type="text" id="search" name="search">
            <input type="submit" value="Search">
        </form>
    </header>
    <section id="product-display">
        <!-- Product 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 1">
            <h3>Product 1</h3>
            <p>$19.99</p>
            <p>Description of Product 1.</p>
        </div>
        
        <!-- Repeat the above product structure for the remaining 99 products with unique details -->
        <!-- Product 2 -->
        <!-- ... -->

        <!-- Product 100 -->
        <!-- ... -->
    </section>
    <footer>
        <p>&copy; 2023 Black Website. All rights reserved.</p>
    </footer>
</body>
</html>
