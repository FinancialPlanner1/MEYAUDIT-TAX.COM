<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MEYAUDITDEMO - Your Trusted Accounting Partner</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 90%;
            margin: 65px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0px 0px 10px #aaa;
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
            color: #003366; /* Dark blue */
            transition: color 0.3s ease;
        }
        .highlight {
            background-color: #e0e0e0; /* Light grey */
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #003366; /* Dark blue */
        }
        .highlight h2 {
            color: #002a4a; /* Slightly darker blue */
        }

        .contact-info {
            background: #003366; /* Dark blue */
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
            background-color: #003366; /* Dark blue */
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #002a4a; /* Slightly darker blue */
        }
        footer {
            text-align: center;
            background-color: #f4f4f9;
            padding: 10px;
            margin-top: 40px;
            font-size: 0.9em;
        }
        .disclaimer {
            color: #777;
        }
        .meeting-form {
            background: #e0e0e0; /* Light grey */
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
            background: #003366; /* Dark blue */
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }
        button:hover {
            background: #002a4a; /* Slightly darker blue */
        }
        /* Slow Motion Scroll */
        html {
            scroll-behavior: smooth;
        }

        .sitemap-section {
            margin-top: 50px;
        }

        /* Site Map Styling */
        .sitemap-section {
            margin-top: 50px;
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .sitemap-section h2 {
            color: #003366; /* Dark blue */
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
            color: #003366; /* Dark blue */
            transition: color 0.3s ease;
        }

        .sitemap-list a:hover {
            color: #002a4a; /* Slightly darker blue */
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
            <p><strong>Contact Us</strong></p>
            <p>Email: <a href="mailto:info@meyauditdemo.com">info@meyauditdemo.com</a></p>
            <p>Phone: <a href="tel:+27111234567">+27 11 123 4567</a></p>
        </div>

        <!-- About Us Section -->
        <div class="section highlight" id="about-us">
            <h2>About Us</h2>
            <p>MEYAUDITDEMO is your reliable partner for comprehensive auditing and advisory services. With our expert team of professionals, we provide tailored financial solutions to individuals and businesses, ensuring financial transparency, compliance, and operational efficiency.</p>
        </div>

        <!-- Services Offered Section -->
        <div class="section highlight" id="services-offered">
            <h2>Services Offered</h2>
            <ul>
                <li>Financial Audits</li>
                <li>Internal Audits</li>
                <li>Compliance Audits</li>
                <li>Risk Assessment and Management</li>
                <li>Advisory Services</li>
            </ul>
        </div>

        <!-- Book a Meeting Form -->
        <div class="section meeting-form">
            <h2>Book a Meeting</h2>
            <form action="mailto:info@meyauditdemo.com" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="Name" required>

                <label for="surname">Surname:</label>
                <input type="text" id="surname" name="Surname" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="Email" required>

                <label for="contact">Contact Number:</label>
                <input type="tel" id="contact" name="Contact" required>

                <label for="message">Additional Details (Optional):</label>
                <textarea id="message" name="Message" rows="4"></textarea>

                <button type="submit">Send Meeting Request</button>
            </form>
        </div>

        <!-- Connect with Us Section -->
        <div class="section" id="connect-with-us">
            <h2>Connect with Us on WhatsApp</h2>
            <p><a href="https://wa.me/27111234567" target="_blank" class="button">Chat with Us on WhatsApp</a></p>
        </div>

        <!-- Site Map Section -->
        <div class="sitemap-section">
            <h2>Site Map</h2>
            <div class="sitemap-list">
                <ul>
                    <li><a href="#about-us" class="smooth-scroll">About Us</a></li>
                    <li><a href="#services-offered" class="smooth-scroll">Services Offered</a></li>
                    <li><a href="#connect-with-us" class="smooth-scroll">Connect with Us</a></li>
                </ul>
            </div>
        </div>

    </div>

    <footer>
        <p>&copy; 2025 MEYAUDITDEMO. All rights reserved.</p>
        <p class="disclaimer">Disclaimer: This website is for informational purposes only and is not intended as professional auditing or financial advice. Always consult a certified auditor or financial planner for personalized advice.</p>
    </footer>

    <script>
        // Smooth Scroll for Site Map links
        document.querySelectorAll('.smooth-scroll').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth',
                    block: 'start'
                });
            });
        });
    </script>
</body>
</html>
