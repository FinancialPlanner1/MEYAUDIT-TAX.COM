<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile</title>
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
    </style>
</head>
<body>

    <header>
        <h1>Personal Profile</h1>
        <p>Authorised by Sanlam | Lonfin Group</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>I am a driven individual who is dedicated and passionate about personal growth. I believe in the power of hard work, perseverance, and continuous learning to achieve success. Challenges motivate me, and I am always striving to push beyond my limits to grow and improve. My goal is to make a meaningful impact in everything I do, inspiring those around me to pursue their ambitions with confidence and determination. Success, for me, is not just about personal achievement but also about uplifting others and making a positive difference in the world.</p>
    </section>

    <section class="qualifications">
        <h2>Qualifications</h2>
        <ul>
            <li>BCom in Business Management</li>
            <li>2 Years of Experience in Financial Planning</li>
            <li>Authorised Financial Planner at Sanlam</li>
        </ul>
    </section>

    <section class="contact-info">
        <h2>Contact Information</h2>
        <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
        <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
    </section>

    <section class="book-meeting">
        <h2>Book a Meeting</h2>
        <form action="#" method="post">
            <label>Name and Surname:</label><br>
            <input type="text" name="name" required><br><br>

            <label>Contact Details:</label><br>
            <input type="text" name="contact" required><br><br>

            <label>Preferred Date:</label><br>
            <input type="date" name="date" required><br><br>

            <label>Preferred Time:</label><br>
            <input type="time" name="time" required><br><br>

            <button type="submit">Book Meeting</button>
        </form>
    </section>

    <footer>
        <p>Disclaimer: Sanlam Life Insurance Limited is a Licensed Financial Services Provider.</p>
    </footer>

</body>
</html>
