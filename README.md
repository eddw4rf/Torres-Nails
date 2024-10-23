<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Torres Nails</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #f1c6d5;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        .hero {
            background: url('your-hero-image.jpg') no-repeat center center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);
        }
        .services, .about, .gallery, .testimonials, .contact {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #f1c6d5;
        }
    </style>
</head>
<body>

<header>
    <h1>Torres Nails</h1>
    <nav>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero">
    <h2>Welcome to Torres Nails</h2>
</div>

<section id="services" class="services">
    <h2>Our Services</h2>
    <ul>
        <li><strong>Classic Manicure:</strong> Nail shaping, cuticle care, and polish.</li>
        <li><strong>Gel Pedicure:</strong> Long-lasting shine and durability.</li>
        <li><strong>Nail Art:</strong> Custom designs to express your style.</li>
        <li><strong>Spa Treatments:</strong> Pampering for your hands and feet.</li>
    </ul>
</section>

<section id="gallery" class="gallery">
    <h2>Our Work</h2>
    <img src="nail-art-1.jpg" alt="Nail Art 1" style="width: 100%; height: auto;">
    <img src="nail-art-2.jpg" alt="Nail Art 2" style="width: 100%; height: auto;">
    <img src="nail-art-3.jpg" alt="Nail Art 3" style="width: 100%; height: auto;">
</section>

<section id="about" class="about">
    <h2>About Us</h2>
    <p>At Your Torres Nails, we believe that beauty is an art. Our talented team is passionate about nails and committed to helping you express your unique style.</p>
</section>

<section id="testimonials" class="testimonials">
    <h2>What Our Clients Say</h2>
    <blockquote>"Absolutely in love with my nails! The team is so talented and friendly." – Sarah J.</blockquote>
</section>

<section id="contact" class="contact">
    <h2>Get in Touch</h2>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" required></textarea><br>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>Follow us on social media!</p>
    <p>&copy; 2024 Torres Nails. All Rights Reserved.</p>
</footer>

</body>
</html>
