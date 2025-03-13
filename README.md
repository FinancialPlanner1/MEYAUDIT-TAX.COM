<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>William Meyer - Financial Planner</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #006f73;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            color: #006f73;
        }
        .contact-info p {
            margin: 5px 0;
        }
        .services-list ul {
            list-style: none;
            padding-left: 0;
        }
        .services-list li {
            background: #006f73;
            color: white;
            margin: 5px 0;
            padding: 8px;
            border-radius: 4px;
        }
        .form-group {
            margin: 10px 0;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
        button {
            background-color: #006f73;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #004f53;
        }
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 30px;
        }
        footer a {
            color: #1e90ff;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>William Meyer - Financial Planner</h1>
        <p>Authorised by Sanlam | Lonfin Group</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>I’m William Meyer, a driven individual who is dedicated and passionate about personal growth. I believe in the power of hard work, perseverance, and continuous learning to achieve success. Challenges motivate me, and I am always striving to push beyond my limits to grow and improve. My goal is to make a meaningful impact in everything I do, inspiring those around me to pursue their ambitions with confidence and determination. Success, for me, is not just about personal achievement but also about uplifting others and making a positive difference in the world.</p>
    </section>

    <section class="qualifications">
        <h2>Qualifications</h2>
        <ul>
            <li>BCom in Business Management</li>
            <li>2 Years of Experience in Financial Planning</li>
            <li>Authorised Financial Planner at Sanlam</li>
        </ul>
    </section>

    <section class="services">
        <h2>Services Offered</h2>
        <div class="services-list">
            <h3>Investment Solutions</h3>
            <ul>
                <li>Unit Trusts</li>
                <li>Tax-Free Savings Accounts</li>
                <li>Wealth and Portfolio Management</li>
            </ul>

            <h3>Retirement Planning</h3>
            <ul>
                <li>Retirement Annuities</li>
                <li>Pension and Provident Funds</li>
                <li>Preservation Funds</li>
            </ul>

            <h3>Insurance Solutions</h3>
            <ul>
                <li>Life Insurance</li>
                <li>Disability Cover</li>
                <li>Income Protection</li>
                <li>Severe Illness Cover</li>
            </ul>

            <h3>Estate and Legacy Planning</h3>
            <ul>
                <li>Wills and Trusts</li>
                <li>Estate Administration</li>
            </ul>

            <h3>Business Financial Planning</h3>
            <ul>
                <li>Business Assurance</li>
                <li>Key Person Insurance</li>
                <li>Buy-and-Sell Agreements</li>
            </ul>
        </div>
    </section>

    <section class="contact-info">
        <h2>Contact Information</h2>
        <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
        <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
        <p>Location: 1st Floor, Century Way, The Colosseum, Cape Town, South Africa</p>
    </section>

    <section class="book-meeting">
        <h2>Book a Meeting</h2>
        <form action="#" method="post">
            <div class="form-group">
                <label for="first-name">Name</label>
                <input type="text" id="first-name" name="first-name" placeholder="Your First Name" required>
            </div>
            <div class="form-group">
                <label for="surname">Surname</label>
                <input type="text" id="surname" name="surname" placeholder="Your Surname" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="Your Email" required>
            </div>
            <div class="form-group">
                <label for="contact-number">Contact Number</label>
                <input type="tel" id="contact-number" name="contact-number" placeholder="Your Contact Number" required>
            </div>
            <div class="form-group">
                <label for="preferred-day">Preferred Meeting Day</label>
                <input type="date" id="preferred-day" name="preferred-day" required>
            </div>
            <div class="form-group">
                <label for="preferred-time">Preferred Time</label>
                <input type="time" id="preferred-time" name="preferred-time" required>
            </div>
            <div class="form-group">
                <label for="additional-details">Additional Details</label>
                <textarea id="additional-details" name="additional-details" placeholder="Any additional details..." rows="4"></textarea>
            </div>
            <button type="submit">Send Meeting Request</button>
        </form>
    </section>

    <footer>
        <p>Connect with Me: 
            <a href="https://www.sanlam4u.co.za" target="_blank">Visit Sanlam's Website</a> | 
            <a href="https://www.linkedin.com/in/william-meyer" target="_blank">LinkedIn</a>
        </p>
    </footer>

</body>
</html>
