<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blue Fleet Computer</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        header {
            background: #0a2540;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background: #133b5c;
            display: flex;
            justify-content: center;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background: #1e5f74;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1518770660439-4636190af475') no-repeat center/cover;
            color: white;
            padding: 80px 20px;
            text-align: center;
        }
        .container {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .card {
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 8px;
            background: #f9f9f9;
        }
        footer {
            background: #0a2540;
            color: white;
            text-align: center;
            padding: 20px;
        }
        button {
            background: #1e5f74;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background: #133b5c;
        }
    </style>
</head>
<body>

<header>
    <h1>Blue Fleet Computers</h1>
    <p>Fast Fixes. Honest Service. Technology You Can Rely On.</p>
</header>

<nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero">
    <h2>Reliable Computer Repair Services</h2>
    <p>We fix laptops, desktops, viruses, and more — quick and affordable.</p>
    <button onclick="document.getElementById('contact').scrollIntoView()">Get Help Now</button>
</section>

<section id="services" class="container">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Virus Removal</h3>
            <p>Eliminate malware and keep your system secure.</p>
        </div>
        <div class="card">
            <h3>Hardware Repair</h3>
            <p>Screen replacements, hard drives, RAM upgrades, and more.</p>
        </div>
        <div class="card">
            <h3>Data Recovery</h3>
            <p>Recover lost or deleted files safely.</p>
        </div>
        <div class="card">
            <h3>System Optimization</h3>
            <p>Speed up your computer for better performance.</p>
        </div>
    </div>
</section>

<section id="about" class="container">
    <h2>About Us</h2>
    <p>
        At Blue Fleet Computers, we specialize in fast, reliable, and affordable computer repair services.
        Our experienced technicians are committed to getting your devices back up and running
        with minimal downtime.
    </p>
</section>

<section id="contact" class="container">
    <h2>Contact Us</h2>
    <p>Email: support@bluefleetcomputers.com</p>
    <p>Phone: (801) 845-3184</p>
    <p>Location: Magna UT, USA</p>
</section>

<footer>
    <p>© 2026 Blue Fleet Computers LLC | All Rights Reserved</p>
</footer>

</body>
</html>
