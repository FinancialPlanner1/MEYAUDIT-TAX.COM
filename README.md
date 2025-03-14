<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>William Meyer - Financial Planner</title>
    <style>
        /* General Reset and Body Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }

        /* Container that holds all content */
        .container {
            width: 60%;
            margin: 50px auto;
            background: #fff;
            padding: 30px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        /* Header and Subheader Styles */
        h1, h2 {
            color: #005B9F;
            font-weight: bold;
            margin-bottom: 10px;
        }

        /* Contact Info Section Styling */
        .contact-info {
            background: #005B9F;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 5px;
            margin-bottom: 20px;
        }

        .contact-info a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        /* General Section Styling */
        .section {
            margin-bottom: 30px;
        }

        .section ul {
            list-style-type: none;
            padding: 0;
        }

        .section li {
            margin-bottom: 10px;
        }

        /* Button Styling */
        .button {
            display: inline-block;
            padding: 12px 20px;
            background-color: #005B9F;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 15px;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #00407a;
        }

        /* Meeting Form Styling */
        .meeting-form {
            background: #e6f2ff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .meeting-form label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }

        .meeting-form input,
        .meeting-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .meeting-form button {
            background: #005B9F;
            color: white;
            padding: 12px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
            transition: background-color 0.3s ease;
        }

        .meeting-form button:hover {
            background: #00407a;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header Section -->
        <header>
            <h1>William Meyer</h1>
            <h2>Financial Planner</h2>
            <hr>
        </header>

        <!-- Contact Info Section -->
        <div class="contact-info">
            <p><strong>Contact Me</strong></p>
            <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
            <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
        </div>

        <!-- About Me Section -->
        <div class="section">
            <h2>About Me</h2>
            <p>I’m William Meyer, a passionate and dedicated financial planner who believes in hard work, perseverance, and continuous learning. I aim to help individuals and businesses make sound financial decisions that lead to long-term success. I thrive on challenges and always strive to provide valuable solutions that improve financial well-being.</p>
        </div>

        <!-- Qualifications Section -->
        <div class="section">
            <h2>Qualifications</h2>
            <ul>
                <li>BCom in Business Management</li>
                <li>2 Years of Experience in Financial Planning</li>
                <li>Authorised Financial Planner at Sanlam</li>
            </ul>
        </div>

        <!-- Services Offered Section -->
        <div class="section">
            <h2>Services Offered</h2>
            <ul>
                <li>Investment Advice</li>
                <li>Retirement Annuity</li>
                <li>Life Insurance</li>
                <li>Will and Estate Planning</li>
                <li>Business Insurance</li>
                <li>Unit Trusts</li>
                <li>Tax-Free Savings Accounts</li>
                <liShort-Term Insurance</li>
            </ul>
        </div>

        <!-- Location Section -->
        <div class="section">
            <h2>Location</h2>
            <p>Find me at: <strong>1st Floor, Century Way, The Colosseum, Cape Town, South Africa</strong></p>
        </div>

        <!-- Book a Meeting Form Section -->
        <div class="section meeting-form">
            <h2>Book a Meeting</h2>
            <form action="mailto:w.meyer@sanlam4u.co.za" method="post" enctype="text/plain">
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

        <!-- Connect with Me Section -->
        <div class="section">
            <h2>Connect with Me</h2>
            <p><a href="https://www.linkedin.com/in/william-meyer-a86677235/" target="_blank" class="button">Connect on LinkedIn</a></p>
        </div>
    </div>

</body>
</html>
