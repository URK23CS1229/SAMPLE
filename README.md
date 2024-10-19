<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Creative Website</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eaeaea;
            color: #333;
        }
        header {
            background: #4a90e2;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 30px;
            background: #fff;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        button {
            padding: 10px 20px;
            background-color: #4a90e2;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #357ab8;
        }
        footer {
            text-align: center;
            padding: 15px 0;
            background: #4a90e2;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Creative Website</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Us</h2>
    <p>Our mission is to create unique web experiences that engage and inspire users.</p>
    <button onclick="alert('More about us coming soon!')">Learn More</button>
</section>

<section id="services">
    <h2>Our Services</h2>
    <p>We provide web development, design, and consulting services to help your business thrive.</p>
    <button onclick="alert('Check out our services!')">Explore Services</button>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Reach out to us at: email@example.com</p>
    <button onclick="alert('We look forward to hearing from you!')">Get in Touch</button>
</section>

<footer>
    <p>&copy; 2024 My Creative Website</p>
</footer>

</body>
</html>
