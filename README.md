<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iron Works</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #0d1a3c;
            color: #fff;
            padding: 15px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 5%;
        }
        nav .logo {
            font-size: 24px;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin-left: 20px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            padding: 5px 10px;
            transition: background-color 0.3s ease;
        }
        nav ul li a:hover {
            background-color: #2a3e6a;
            border-radius: 4px;
        }
        .hero {
            position: relative;
            height: 400px;
            overflow: hidden;
            color: #fff;
            text-align: center;
        }
        .hero img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            filter: brightness(60%);
        }
        .hero-content {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 1;
        }
        .hero-content h1 {
            font-size: 4em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero-content p {
            font-size: 1.2em;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto 20px auto;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
        }
        .btn {
            background-color: #f7931e;
            color: #fff;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.1em;
            transition: background-color 0.3s ease;
        }
        .btn:hover {
            background-color: #e07b00;
        }
        .section {
            padding: 60px 5%;
            text-align: center;
        }
        .section h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #0d1a3c;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .gallery-item {
            background-color: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .gallery-item:hover {
            transform: translateY(-5px);
        }
        .gallery-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            display: block;
        }
        .gallery-item .title {
            padding: 15px;
            font-weight: bold;
            color: #0d1a3c;
        }
        .footer-banner {
            background-color: #0d1a3c;
            color: #fff;
            padding: 80px 5%;
            text-align: center;
            margin-top: 50px;
        }
        .footer-banner h3 {
            font-size: 3em;
            margin-bottom: 20px;
        }
        .footer-banner p {
            font-size: 1.2em;
            margin-bottom: 30px;
            max-width: 900px;
            margin-left: auto;
            margin-right: auto;
        }
        footer {
            background-color: #0d1a3c;
            color: #fff;
            padding: 40px 5%;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            font-size: 0.9em;
        }
        footer div {
            flex: 1;
            min-width: 250px;
            margin-bottom: 20px;
        }
        footer h4 {
            font-size: 1.2em;
            margin-bottom: 15px;
            color: #f7931e;
        }
        footer ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        footer ul li {
            margin-bottom: 8px;
        }
        footer ul li a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        footer ul li a:hover {
            color: #f7931e;
        }
        .social-icons a {
            color: #fff;
            font-size: 1.5em;
            margin-right: 15px;
            transition: color 0.3s ease;
        }
        .social-icons a:hover {
            color: #f7931e;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">PRASANNA IRON WORKS</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#works">Our Works</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="contact-info">
                <a href="tel:+94703618426" class="btn">Contact Us</a>
            </div>
        </nav>
    </header>

    <div class="hero">
        <img src="1.jpg" alt="1">
        <div class="hero-content">
            <h1>IRON WORKS</h1>
            <p>We specialize in metal fabrication, creating beautiful and durable ironwork for residential and commercial clients. Our services include gates, iron doors, iron windows, Construction of roofs of houses, including decorative elements. With a commitment to quality craftsmanship, we bring your vision to life.

            </p>
            <a href="tel:+94703618426" class="btn">Call Now</a>
        </div>
    </div>

    <section id="works" class="section">
        <h2>Our Works</h2>
        <p>Iron gates, iron stairs, iron roofs and windows, etc...
          .</p>
        <div class="gallery">
            <div class="gallery-item">
                <img src="2.jpg" alt="Custom Gate">
                <div class="title">Custom Gate</div>
            </div>
            <div class="gallery-item">
                <img src="3.jpg" alt="Wrought Iron Staircase">
                <div class="title">Wrought Iron Staircase</div>
            </div>
            <div class="gallery-item">
                <img src="4.jpg" alt="Steel Structure">
                <div class="title">Steel Structure</div>
            </div>
            <div class="gallery-item">
                <img src="5.jpg" alt="Decorative Fencing">
                <div class="title">Decorative Fencing</div>
            </div>
            <div class="gallery-item">
                <img src="6.jpg" alt="Balcony Railing">
                <div class="title">Balcony Railing</div>
            </div>
            <div class="gallery-item">
                <img src="7.jpg" alt="Modern Gate">
                <div class="title">Modern Gate</div>
            </div>
        </div>
    </section>

    <div class="footer-banner">
        <h3>Need custom ironwork?</h3>
        <p>Contact us today for a free consultation and let's bring your vision to life with our expert craftsmanship.</p>
        <a href="#contact" class="btn">Get a Quote</a>
    </div>

    <footer>
        <div>
            <h4>IronWorks</h4>
            <p>Dedicated to crafting high-quality iron solutions for over 20 years.</p>
            <div class="social-icons">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
        <div>
            <h4>Operating Hours</h4>
            <ul>
                <li>Mon - Fri: 8am - 5pm</li>
                <li>Saturday: 8am - 5pm</li>
                <li>Sunday: 8am - 5pm</li>
            </ul>
        </div>
        <div>
            <h4>Contact</h4>
            <ul>
                <li>Woodland watta,Gonupinuwala.</li>
                <li>prasanna@gmail.com</li>
                <li>0703618426</li>
            </ul>
        </div>
        <div>
            <h4>Privacy Policy</h4>
            <ul>
                <li><a href="#">Terms & Conditions</a></li>
                <li><a href="#">Sitemap</a></li>
            </ul>
        </div>
    </footer>

    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
