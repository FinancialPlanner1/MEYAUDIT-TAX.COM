<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>William Meyer - Financial Planner</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 60%;
            margin: 50px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0px 0px 10px #aaa;
            border-radius: 8px;
            text-align: center;
            position: relative;
        }
        h1, h2 {
            color: #005B9F;
        }
        .contact-info {
            background: #005B9F;
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
            background-color: #005B9F;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #00407a;
        }
        .meeting-form {
            background: #e6f2ff;
            padding: 15px;
            border-radius: 5px;
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
            background: #005B9F;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }
        button:hover {
            background: #00407a;
        }
        .profile {
            position: absolute;
            top: 20px;
            right: 20px;
            background: #005B9F;
            color: white;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
        }
        .profile a {
            color: white;
            text-decoration: none;
        }
        .profile img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Profile Section -->
        <div class="profile">
            <img src="your-profile-image.jpg" alt="William Meyer">
            <p><a href="https://www.linkedin.com/in/william-meyer-a86677235/" target="_blank">View Profile</a></p>
        </div>

        <h1>William Meyer</h1>
        <h2>Financial Planner at Lonfin MOB, authorised by Sanlam</h2>
        <hr>

        <!-- Contact Info Section -->
        <div class="contact-info">
            <p><strong>Contact Me</strong></p>
            <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
            <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
            <p>Sanlam website: <a href="https://www.sanlam.co.za/Pages/default.aspx" target="_blank">Sanlam</a></p>
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
                
            </ul>
        </div>

        <!-- Location Section -->
        <div class="section">
            <h2>Location</h2>
            <p>Find me at: <strong>1st Floor, Century Way, The Colosseum, Cape Town, South Africa</strong></p>
        </div>

        <!-- Book a Meeting Form -->
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
