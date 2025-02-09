# web-development
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cozy Coffee Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Cozy Coffee Shop</h1>
        <nav>
            <ul>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="menu">
        <h2>Our Menu</h2>
        <ul>
            <li>Espresso - ₹100</li>
            <li>Latte - ₹150</li>
            <li>Cappuccino - ₹120</li>
        </ul>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>Cozy Coffee Shop is your home away from home. Come in and enjoy our warm ambiance and freshly brewed coffee.</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Cozy Coffee Shop</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
