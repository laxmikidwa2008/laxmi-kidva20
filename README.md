<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Selling Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #222;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: yellow;
        }
        .hero {
            text-align: center;
            padding: 50px;
            background-color: #ddd;
        }
        .cars {
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }
        .car {
            background: white;
            padding: 15px;
            width: 30%;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .car img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Laxmi Kidva Car Showroom</h1>
    <h2>Owner: Laxmi Kidva</h2>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Cars</a>
    <a href="#">Contact</a>
</nav>

<div class="hero">
    <h2>Welcome to Our Car Store</h2>
    <p>Find the best cars at affordable prices!</p>
</div>

<section class="cars">
    <div class="car">
        <img src="https://via.placeholder.com/300x200" alt="Car 1">
        <h3>Car Model 1</h3>
        <p>Price: ₹5,00,000</p>
    </div>

    <div class="car">
        <img src="https://via.placeholder.com/300x200" alt="Car 2">
        <h3>Car Model 2</h3>
        <p>Price: ₹7,50,000</p>
    </div>

    <div class="car">
        <img src="https://via.placeholder.com/300x200" alt="Car 3">
        <h3>Car Model 3</h3>
        <p>Price: ₹10,00,000</p>
    </div>
</section>

<footer>
    <p>© 2026 Laxmi Kidva Car Showroom | All Rights Reserved</p>
</footer>

</body>
</html>
