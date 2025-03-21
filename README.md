<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MEYAUDITDEMO - Your Trusted Accounting Partner</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5; /* Light grey background */
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 90%;
            margin: 65px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
            opacity: 0;
            animation: fadeIn 1.5s forwards;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        h1, h2 {
            color: #4682b4; /* Soft blue color */
            transition: color 0.3s ease;
        }
        .highlight {
            background-color: #e9ecef; /* Light grey background */
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #4682b4; /* Soft blue border */
        }
        .highlight h2 {
            color: #5f6368; /* Dark grey */
        }

        .contact-info {
            background: #4682b4; /* Soft blue */
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
        }
        .contact-info a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            margin-bottom: 20px;
            text-align: left;
            transition: transform 1s ease-out;
        }

        .section:hover {
            transform: scale(1.02);
        }

        .section ul {
            list-style-type: none;
            padding: 0;
        }
        .section li {
            margin-bottom: 10px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4682b4; /* Soft blue */
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #4169e1; /* Slightly darker blue */
        }
        footer {
            text-align: center;
            background-color: #f5f5f5;
            padding: 10px;
            margin-top: 40px;
            font-size: 0.9em;
        }
        .disclaimer {
            color: #777;
        }
        .meeting-form {
            background: #e9ecef; /* Light grey */
            padding: 15px;
            border-radius: 5px;
            margin-top: 20px;
        }
        label {
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background: #4682b4; /* Soft blue */
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }
        button:hover {
            background: #4169e1; /* Slightly darker blue */
        }
        /* Smooth Scroll */
        html {
            scroll-behavior: smooth;
        }

        .sitemap-section {
            margin-top: 50px;
            background-color: #e9ecef; /* Light grey */
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .sitemap-section h2 {
            color: #4682b4; /* Soft blue */
            margin-bottom: 10px;
            text-align: center;
        }

        .sitemap-list {
            text-align: center;
        }

        .sitemap-list ul {
            list-style-type: none;
            padding: 0;
        }

        .sitemap-list li {
            margin-bottom: 8px;
        }

        .sitemap-list a {
            text-decoration: none;
            font-size: 16px;
            color: #4682b4; /* Soft blue */
            transition: color 0.3s ease;
        }

        .sitemap-list a:hover {
            color: #4169e1; /* Slightly darker blue */
        }

    </style>
</head>
<body>
    <div class="container">
        <h1>MEYAUDITDEMO</h1>
        <h2>Your Trusted Accounting Partner</h2>
        <hr>

        <!-- Contact Info Section -->
        <div class="contact-info">
            <p><strong>Contact Me</strong></p>
            <p>Email: <a href="mailto:info@meyauditdemo.com">info@meyauditdemo.com</a></p>
            <p>Phone: <a href="tel:+1234567890">+1 234 567 890</a></p>
        </div>

        <!-- About Us Section -->
        <div class="section highlight" id="about-us">
            <h2>About Us</h2>
            <p>At MEYAUDITDEMO, we specialize in providing professional accounting services, helping businesses and individuals optimize their financial management with personalized solutions. Our expert team is dedicated to delivering reliable advice and exceptional service.</p>
        </div>

        <!-- Services Offered Section -->
        <div class="section highlight" id="services-offered">
            <h2>Services Offered</h2>
            <ul>
                <li>Financial Statement Preparation</li>
                <li>Tax Planning and Advisory</li>
                <li>Payroll Services</li>
                <li>Management Reporting</li>
                <li>Business Consulting</li>
                <li>Tax Returns and Compliance</li>
            </ul>
        </div>

        <!-- Book a Meeting Form -->
        <div class="section meeting-form">
            <h2>Book a Meeting</h2>
            <form action="mailto:info@meyauditdemo.com" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="Name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="Email" required>

                <label for="contact">Phone Number:</label>
                <input type="tel" id="contact" name="Phone" required>

                <label for="message">Message (Optional):</label>
                <textarea id="message" name="Message" rows="4"></textarea>

                <button type="submit">Submit Meeting Request</button>
            </form>
        </div>

        <!-- Connect with Me Section -->
        <div class="section" id="connect-with-me">
            <h2>Connect with Me</h2>
            <p><a href="https://wa.me/1234567890" target="_blank" class="button">Connect on WhatsApp</a></p>
        </div>

        <!-- Site Map Section -->
        <div class="sitemap-section">
            <h2>Site Map</h2>
            <div class="sitemap-list">
                <ul>
                    <li><a href="#about-us" class="smooth-scroll">About Us</a></li>
                    <li><a href="#services-offered" class="smooth-scroll">Services Offered</a></li>
                    <li><a href="#connect-with-me" class="smooth-scroll">Connect with Me</a></li>
                    <li><a href="#book-a-meeting" class="smooth-scroll">Book a Meeting</a></li>
                </ul>
            </div>
        </div>

    </div>
<section id="sitemap">
    <h2>Site Map</h2>
    <div class="category-list">
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#services">Our Services</a></li>
            <li><a href="#consultation">Book a Consultation</a></li>
            <li><a href="#contact">Contact Us</a></li>
            <li><a href="#subscribe">Subscribe</a></li>
        </ul>
    </div>
</section>

    <footer>
        <p>&copy; 2025 MEYAUDITDEMO. All rights reserved.</p>
        <p class="disclaimer">Disclaimer: This website is for informational purposes only and is not intended as professional financial advice. Always consult a qualified financial planner for personalized advice.</p>
    </footer>

</body>
</html>
