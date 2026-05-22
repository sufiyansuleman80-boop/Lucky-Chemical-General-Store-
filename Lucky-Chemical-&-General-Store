<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lucky Chemical & General Store</title>
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f0f7f4; /* Beautiful fine light green background */
            color: #333;
            line-height: 1.6;
        }

        /* Top Welcome Bar */
        .welcome-bar {
            background-color: #004085;
            color: white;
            text-align: center;
            padding: 8px;
            font-size: 0.9rem;
            font-weight: 500;
        }

        /* Header & Navigation */
        header {
            background-color: white;
            padding: 1rem 2rem;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.6rem;
            font-weight: bold;
            color: #004085;
        }

        .logo span {
            color: #28a745;
        }

        nav a {
            color: #555;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #004085;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(240, 247, 244, 0.92), rgba(240, 247, 244, 0.88)), url('https://images.unsplash.com/photo-1578916171728-46686eac8d58?q=80&w=1200&h=400') no-repeat center center/cover;
            color: #333;
            text-align: center;
            padding: 5rem 2rem 4rem 2rem;
            border-bottom: 1px solid #e2ebd9;
        }

        .hero h1 {
            font-size: 3rem;
            color: #004085;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            max-width: 750px;
            margin-left: auto;
            margin-right: auto;
            color: #555;
        }

        /* Top Search Bar Styling */
        .search-container {
            max-width: 600px;
            margin: 0 auto;
            position: relative;
        }

        .search-input {
            width: 100%;
            padding: 15px 20px;
            font-size: 1.1rem;
            border: 2px solid #28a745;
            border-radius: 30px;
            outline: none;
            box-shadow: 0 4px 15px rgba(40, 167, 69, 0.1);
            transition: all 0.3s ease;
        }

        .search-input:focus {
            box-shadow: 0 4px 20px rgba(40, 167, 69, 0.25);
            border-color: #1e7e34;
        }

        /* Main Content Container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 3rem 2rem 4rem 2rem;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3.5rem;
            color: #004085;
            font-size: 2.2rem;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 3px;
            background-color: #28a745;
            margin: 10px auto 0;
        }

        /* Department Grid */
        .dept-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2.5rem;
            margin-bottom: 5rem;
        }

        .dept-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(0,0,0,0.03);
            transition: transform 0.3s;
            border: 1px solid #e2ebd9;
        }

        .dept-card:hover {
            transform: translateY(-5px);
        }

        /* Images */
        .dept-img {
            width: 100%;
            height: 200px;
            background-size: cover;
            background-position: center;
            border-bottom: 1px solid #e2ebd9;
        }

        .img-tea {
            background-image: url('https://images.unsplash.com/photo-1597481499750-3e6b22637e12?w=500&q=80');
        }

        .img-laundry {
            background-image: url('https://images.unsplash.com/photo-1610557892470-55d9e80c0bce?w=500&q=80');
        }

        .dept-details {
            padding: 2rem;
        }

        .dept-details h3 {
            font-size: 1.5rem;
            color: #004085;
            margin-bottom: 1rem;
            border-bottom: 2px solid #f1f1f1;
            padding-bottom: 5px;
        }

        .product-list {
            list-style: none;
        }

        .product-list li {
            padding: 10px 0;
            border-bottom: 1px solid #f0f0f0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 0.95rem;
            transition: background 0.2s;
        }

        .product-list li:last-child {
            border-bottom: none;
        }

        .price-tag {
            background-color: #e2f0d9;
            color: #385723;
            font-weight: bold;
            padding: 3px 10px;
            border-radius: 5px;
            font-size: 0.9rem;
            white-space: nowrap;
        }

        /* Info Section */
        .info-section {
            background: white;
            padding: 3rem;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.03);
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 3rem;
            border: 1px solid #e2ebd9;
        }

        .info-box h3 {
            color: #004085;
            margin-bottom: 1.2rem;
            font-size: 1.4rem;
        }

        .info-box p {
            margin-bottom: 1rem;
            color: #555;
        }

        /* Footer */
        footer {
            background-color: #111;
            color: #aaa;
            text-align: center;
            padding: 2.5rem;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .nav-container {
                flex-direction: column;
                gap: 1rem;
            }
            nav a {
                margin: 0 10px;
            }
            .hero h1 {
                font-size: 2.4rem;
            }
        }
    </style>
</head>
<body>

    <!-- Top Notice Bar -->
    <div class="welcome-bar">
        👋 Welcome to Lucky Chemical & General Store! Fresh retail stock at standard market prices.
    </div>

    <!-- Header -->
    <header>
        <div class="nav-container">
            <div class="logo">Lucky <span>Store</span></div>
            <nav>
                <a href="#home">Home</a>
                <a href="#shop">Shop Items</a>
                <a href="#visit-us">Contact Us</a>
            </nav>
        </div>
    </header>

    <!-- Hero Banner -->
    <section class="hero" id="home">
        <h1>Lucky Chemical & General Store</h1>
        <p>Your premium neighborhood retail outlet for premium brand teas, top-tier washing detergents, everyday groceries, and home chemical essentials.</p>
        
        <!-- Search Bar at the Top of the Screen -->
        <div class="search-container">
            <input type="text" id="productSearch" class="search-input" placeholder="Search items (e.g., Tapal, Surf, Tang)..." onkeyup="searchProducts()">
        </div>
    </section>

    <!-- Main Content Container -->
    <div class="container" id="shop">
        <h2 class="section-title">Our Retail Price Catalog</h2>
        
        <div class="dept-grid">

            <!-- Category 1: Tea & Beverages -->
            <div class="dept-card">
                <div class="dept-img img-tea"></div>
                <div class="dept-details">
                    <h3>Tea & Beverages</h3>
                    <ul class="product-list">
                        <li class="product-item">
                            <span class="product-name">Tapal Family Mixture (900g)</span>
                            <span class="price-tag">Rs. 1,700</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Tapal Family Mixture (430g)</span>
                            <span class="price-tag">Rs. 900</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Tapal Mixture (200g)</span>
                            <span class="price-tag">Rs. 360</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Pulsar Mixture (100g)</span>
                            <span class="price-tag">Rs. 180</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Tapal Danedar (900g)</span>
                            <span class="price-tag">Rs. 1,660</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Tapal Danedar (430g)</span>
                            <span class="price-tag">Rs. 860</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Tapal Danedar (200g)</span>
                            <span class="price-tag">Rs. 360</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Tapal Danedar (100g)</span>
                            <span class="price-tag">Rs. 180</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Tang Pouch</span>
                            <span class="price-tag">Rs. 320</span>
                        </li>
                    </ul>
                </div>
            </div>

            <!-- Category 2: Laundry & Washing Powders -->
            <div class="dept-card">
                <div class="dept-img img-laundry"></div>
                <div class="dept-details">
                    <h3>Laundry & Washing Powders</h3>
                    <ul class="product-list">
                        <li class="product-item">
                            <span class="product-name">Surf Excel (1 kg)</span>
                            <span class="price-tag">Rs. 550</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Surf Excel (500g)</span>
                            <span class="price-tag">Rs. 280</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Bright Surf (1 kg)</span>
                            <span class="price-tag">Rs. 550</span>
                        </li>
                        <li class="product-item">
                            <span class="product-name">Bright Surf (500g)</span>
                            <span class="price-tag">Rs. 280</span>
                        </li>
                    </ul>
                </div>
            </div>

        </div>

        <!-- Shop Location & Timing Section -->
        <section id="visit-us" class="info-section">
            <div class="info-box">
                <h3>About Our Shop</h3>
                <p>Lucky Chemical and General Store brings you authentic everyday grocery brands alongside powerful, safe home-care cleaning chemicals right in your local area.</p>
            </div>
            <div class="info-box">
                <h3>Store Details</h3>
                <p>📍 <strong>Address:</strong> F.B. Area, Karimabad Market, near Habib Achar, Opposite Pappu Papar Wala, Karachi, Pakistan</p>
                <p>📞 <strong>Phone / WhatsApp:</strong> 03333367707</p>
                <p>⏰ <strong>Opening Hours:</strong> 10:30 AM - 9:30 PM (Monday to Saturday)</p>
            </div>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Lucky Chemical & General Store. All Rights Reserved.</p>
    </footer>

    <!-- Instant Search Logic (JavaScript) -->
    <script>
        function searchProducts() {
            let input = document.getElementById('productSearch').value.toLowerCase();
            let items = document.getElementsByClassName('product-item');
            
            for (let i = 0; i < items.length; i++) {
                let productName = items[i].getElementsByClassName('product-name')[0].innerText.toLowerCase();
                if (productName.includes(input)) {
                    items[i].style.display = "flex";
                } else {
                    items[i].style.display = "none";
                }
            }
        }
    </script>

</body>
</html>
