 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raze & John's - Where Style Meets Comfort</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
        }
        .hero {
            background-image: url('your-hero-image.jpg');
            background-size: cover;
            height: 400px;
            text-align: center;
            color: white;
            padding-top: 150px;
        }
        .hero h2 {
            font-size: 48px;
            margin: 0;
        }
        .section {
            padding: 40px 20px;
            text-align: center;
        }
        .section h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .section p {
            font-size: 18px;
            line-height: 1.6;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            padding: 20px;
        }
        .product {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            margin-top: 10px;
            font-size: 24px;
        }
        .product p {
            font-size: 16px;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        footer a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Raze & John's</h1>
        <p>Where Style Meets Comfort</p>
    </header>

    <div class="hero">
        <h2>Explore Our Collection</h2>
    </div>

    <div class="section">
        <h2>Why Choose Raze & John's?</h2>
        <p>Our designs blend the latest fashion trends with premium comfort. Each piece is crafted to make you look stylish and feel confident.</p>
    </div>

    <div class="section">
        <h2>Our Collection</h2>
        <p>From casual wear to formal attire, discover pieces that will elevate your wardrobe.</p>
    </div>

    <div class="products">
        <div class="product">
            <img src="casual-wear.jpg" alt="Casual Wear">
            <h3>Casual Wear</h3>
            <p>Comfortable and stylish outfits for everyday wear.</p>
        </div>
        <div class="product">
            <img src="formal-wear.jpg" alt="Formal Wear">
            <h3>Formal Wear</h3>
            <p>Elegant and sophisticated designs for any formal event.</p>
        </div>
        <div class="product">
            <img src="athleisure.jpg" alt="Athleisure">
            <h3>Athleisure</h3>
            <p>Perfect for both workouts and lounging.</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Raze & John's | <a href="#">Privacy Policy</a> | <a href="#">Contact Us</a></p>
    </footer>

</body>
</html>
