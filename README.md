<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-commerce Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }

        /* Header */
        .header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .header h1 {
            margin: 0;
        }

        /* Search Bar */
        .search-bar {
            margin: 20px auto;
            max-width: 600px;
            display: flex;
        }

        .search-bar input[type="text"] {
            flex: 1;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 8px 0 0 8px;
            outline: none;
        }

        .search-bar button {
            padding: 10px 20px;
            border: none;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
            border-radius: 0 8px 8px 0;
        }

        .search-bar button:hover {
            background-color: #45a049;
        }

        /* Categories */
        .categories {
            display: flex;
            justify-content: center;
            margin: 20px 0;
            flex-wrap: wrap;
        }

        .category {
            background-color: #fff;
            padding: 15px 25px;
            margin: 10px;
            border-radius: 8px;
            cursor: pointer;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .category:hover {
            background-color: #4CAF50;
            color: white;
        }

        /* Products Grid */
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }

        .product {
            background-color: white;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .product img {
            width: 100%;
            border-radius: 10px;
        }

        .product h3 {
            margin: 10px 0 5px 0;
            color: #333;
        }

        .product p {
            margin: 5px 0;
            color: #777;
        }

        .product .price {
            font-weight: bold;
            color: #4CAF50;
        }

        .product button {
            margin-top: 10px;
            padding: 10px 20px;
            border: none;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }

        .product button:hover {
            background-color: #45a049;
        }

        /* Footer */
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }

        /* Responsive */
        @media screen and (max-width: 600px) {
            .categories {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="header">
        <h1>My E-commerce Store</h1>
    </div>

    <!-- Search Bar -->
    <div class="search-bar">
        <input type="text" placeholder="Search products...">
        <button>Search</button>
    </div>

    <!-- Categories -->
    <div class="categories">
        <div class="category">Electronics</div>
        <div class="category">Fashion</div>
        <div class="category">Home</div>
        <div class="category">Books</div>
        <div class="category">Toys</div>
    </div>

    <!-- Products -->
    <div class="products">
        <div class="product">
            <img src="https://via.placeholder.com/200x150" alt="Product Image">
            <h3>Wireless Headphones</h3>
            <p>High-quality sound with noise cancellation</p>
            <div class="price">₹2,500</div>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200x150" alt="Product Image">
            <h3>Smart Watch</h3>
            <p>Track your fitness and notifications</p>
            <div class="price">₹3,000</div>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200x150" alt="Product Image">
            <h3>Leather Bag</h3>
            <p>Stylish and durable bag for everyday use</p>
            <div class="price">₹1,800</div>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200x150" alt="Product Image">
            <h3>Coffee Maker</h3>
            <p>Brew fresh coffee at home</p>
            <div class="price">₹2,200</div>
            <button>Add to Cart</button>
        </div>
    </div>

    <!-- Footer -->
    <div class="footer">
        &copy; 2025 My E-commerce Store. All rights reserved.
    </div>

</body>
</html>
