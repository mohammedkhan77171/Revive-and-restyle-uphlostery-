# Revive-and-restyle-uphlostery-
Revive and restyle uphlostery 
I understand you want to create a free website for your upholstery business and are now asking for code. Since you initially mentioned creating a website and I suggested using Canva’s no-code website builder, I’ll assume you’re looking for a simple HTML/CSS code solution to create a basic, free website that can be hosted on a free platform like GitHub Pages. Below, I’ll provide a sample code for a single-page website tailored for an upholstery business, including a homepage with sections for About, Services, Portfolio, and Contact. You can customize this further and host it for free.
Step-by-Step Code for a Basic Upholstery Website
This code creates a responsive, one-page website with a clean design, styled with CSS and structured in HTML. It’s beginner-friendly and can be edited with a text editor like Notepad or VS Code.
html<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Upholstery Business</title>
    <style>
        /* Basic CSS for styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem;
        }
        header h1 {
            margin–

System: 0;
            font-size: 2.5rem;
        }
        nav {
            background: #444;
            padding: 1rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.1rem;
        }
        nav a:hover {
            color: #ddd;
        }
        section {
            padding: 2rem;
            max-width: 1000px;
            margin: auto;
        }
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }
        .portfolio-grid img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .contact-form {
            max-width: 600px;
            margin: auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.5rem;
            margin: 0.5rem 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            background: #333;
            color: white;
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background: #555;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Upholstery Business</h1>
        <p>Transforming Furniture with Craftsmanship</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="home">
        <h2>Welcome to Your Upholstery Business</h2>
        <p>We specialize in custom upholstery, bringing new life to your furniture with high-quality fabrics and expert craftsmanship.</p>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>With over 10 years of experience, we are passionate about creating beautiful, durable upholstery for homes and businesses. Our team works closely with clients to deliver personalized designs.</p>
    </section>
    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Custom Furniture Upholstery</li>
            <li>Furniture Repair and Restoration</li>
            <li>Slipcovers and Cushions</li>
            <li>Commercial Upholstery Projects</li>
        </ul>
    </section>
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-grid">
            <!-- Replace with your own images -->
            <img src="https://via.placeholder.com/300x200?text=Chair+Upholstery" alt="Chair Upholstery">
            <img src="https://via.placeholder.com/300x200?text=Sofa+Restoration" alt="Sofa Restoration">
            <img src="https://via.placeholder.com/300x200?text=Custom+Cushions" alt="Custom Cushions">
            <img src="https://via.placeholder.com/300x200?text=Vintage+Reupholstery" alt="Vintage Reupholstery">
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Your Upholstery Business. All rights reserved.</p>
    </footer>
</body>
</html>
