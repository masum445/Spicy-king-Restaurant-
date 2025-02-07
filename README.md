<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spicy King Restaurant</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
</head>
<body>

    <div class="container">
        <header>
            <div class="logo">
                <a href="#"><i class="fa-solid fa-utensils"></i> Spicy King</a>
            </div>
            <nav>
                <ul id="menu-list">
                    <li><a href="#">Home</a></li>
                    <li><a href="#about-us">About</a></li>
                    <li><a href="#menu-section">Menu</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="login.html" class="login-btn">Log In</a></li>
                    <li><a href="signup.html" class="signup-btn">Sign Up</a></li>
                </ul>
                <div class="menu-toggle" onclick="toggleMenu()">
                    <i class="fa-solid fa-bars"></i>
                </div>
            </nav>
        </header>

        <section id="banner">
            <div class="banner-content">
                <h1>Spicy King Restaurant</h1>
                <p>20% Discount for Take Away</p>
                <button class="btn">Order Now</button>
            </div>
        </section>

        <section id="about-us">
            <h2>About Us</h2>
            <p>Welcome to Spicy King, where flavor rules! We specialize in mouthwatering, spice-infused dishes...</p>
        </section>

        <section id="menu-section">
            <h2>Our Menu</h2>
            <div class="menu-items">
                <div class="card">
                    <img src="img1.jpg" alt="Curma">
                    <h3>Curma</h3>
                    <p>Item No: 101</p>
                    <p>Rating: 4/5</p>
                    <p>Price: 250 TK</p>
                </div>
                <div class="card">
                    <img src="img2.jpg" alt="Burger">
                    <h3>Burger</h3>
                    <p>Item No: 102</p>
                    <p>Rating: 5/5</p>
                    <p>Price: 180 TK</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <div class="contact-info">
                <p>📍 Location: Sylhet, Bangladesh</p>
                <p>📞 Phone: +8801983357473</p>
                <p>⏰ Opening Hours: Tue-Sun: 5PM to 11PM</p>
            </div>
        </section>

        <footer>
            <p>&copy; 2025 Spicy King. All Rights Reserved.</p>
        </footer>
    </div>

    <script>
        function toggleMenu() {
            const menuList = document.getElementById("menu-list");
            menuList.classList.toggle("active");
        }
    </script>

</body>
</html>
