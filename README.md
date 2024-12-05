<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SweetBee Raw Honey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff8f0;
            color: #333;
        }
        header {
            background-color: #ffcc00;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #654321;
        }
        nav {
            background-color: #fff;
            overflow: hidden;
            border-bottom: 1px solid #ddd;
        }
        nav a {
            float: left;
            display: block;
            color: #654321;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 1.1em;
        }
        nav a:hover {
            background-color: #ffcc00;
            color: #fff;
        }
        .banner {
            position: relative;
            text-align: center;
            color: white;
        }
        .banner img {
            width: 100%;
            height: 400px;
            object-fit: cover;
            opacity: 0.8;
        }
        .banner-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        .banner-text h2 {
            font-size: 3em;
            margin: 0;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 300px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            width: 100%;
            border-bottom: 1px solid #ddd;
            border-top-left-radius: 8px;
            border-top-right-radius: 8px;
        }
        .product-details {
            padding: 15px;
            text-align: center;
        }
        .product-details h3 {
            margin: 10px 0;
            color: #654321;
        }
        .product-details p {
            color: #666;
        }
        .product-details .price {
            font-size: 1.2em;
            color: #ff6600;
            margin: 10px 0;
        }
        .product-details button {
            background-color: #ffcc00;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            color: #654321;
            transition: background-color 0.3s;
        }
        .product-details button:hover {
            background-color: #e6b800;
        }
        .about, .contact {
            margin: 40px 0;
        }
        .about h2, .contact h2 {
            text-align: center;
            color: #654321;
            margin-bottom: 20px;
        }
        .about p, .contact p {
            max-width: 800px;
            margin: auto;
            line-height: 1.6;
            color: #555;
        }
        .contact form {
            max-width: 600px;
            margin: auto;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .contact form input, .contact form textarea {
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1em;
        }
        .contact form button {
            background-color: #ffcc00;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            color: #654321;
            transition: background-color 0.3s;
        }
        .contact form button:hover {
            background-color: #e6b800;
        }
        footer {
            background-color: #ffcc00;
            text-align: center;
            padding: 15px 0;
            color: #654321;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        @media (max-width: 768px) {
            .products {
                flex-direction: column;
                align-items: center;
            }
            .banner-text h2 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>SweetBee Raw Honey</h1>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <!-- Banner -->
    <div class="banner" id="home">
        <img src="https://images.unsplash.com/photo-1514933651103-005eec06c04b?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Raw Honey">
        <div class="banner-text">
            <h2>Pure, Raw, Natural Honey</h2>
        </div>
    </div>

    <!-- Products Section -->
    <div class="container" id="products">
        <h2 style="text-align:center; color:#654321;">Our Products</h2>
        <div class="products">
            <!-- Product 1 -->
            <div class="product">
                <img src="https://images.unsplash.com/photo-1583272493743-dc7a0c0221c1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Wildflower Honey">
                <div class="product-details">
                    <h3>Wildflower Honey</h3>
                    <p>Rich and aromatic, sourced from wildflower blossoms.</p>
                    <div class="price">$15.99/liter</div>
                    <button>Add to Cart</button>
                </div>
            </div>
            <!-- Product 2 -->
            <div class="product">
                <img src="https://images.unsplash.com/photo-1581349481113-fcb2ad3e9f38?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Clover Honey">
                <div class="product-details">
                    <h3>Clover Honey</h3>
                    <p>Smooth and mild, perfect for everyday use.</p>
                    <div class="price">$12.99/liter</div>
                    <button>Add to Cart</button>
                </div>
            </div>
            <!-- Product 3 -->
            <div class="product">
                <img src="https://images.unsplash.com/photo-1603046893384-642668b6d8da?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Manuka Honey">
                <div class="product-details">
                    <h3>Manuka Honey</h3>
                    <p>Premium honey with unique antibacterial properties.</p>
                    <div class="price">$29.99/liter</div>
                    <button>Add to Cart</button>
                </div>
            </div>
            <!-- Add more products as needed -->
        </div>
    </div>

    <!-- About Us Section -->
    <div class="container about" id="about">
        <h2>About Us</h2>
        <p>
            At SweetBee Raw Honey, we are passionate about providing the purest and most natural honey to our customers. Our bees are nurtured in pristine environments, ensuring that every jar of honey we produce is bursting with natural flavor and health benefits. From wildflower to Manuka, our diverse range of honey varieties caters to all your culinary and wellness needs.
        </p>
    </div>

    <!-- Contact Us Section -->
    <div class="container contact" id="contact">
        <h2>Contact Us</h2>
        <p>
            Have questions or need assistance? We'd love to hear from you!
        </p>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>

    <!-- Footer -->
    <footer>
        &copy; 2024 SweetBee Raw Honey. All rights reserved.
    </footer>

</body>
</html>
