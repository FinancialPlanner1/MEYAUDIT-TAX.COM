<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Financial Planner | Lonfin MOB Authorised by S</title
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
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
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
        .form-group {
            margin: 10px 0;
        }
        input, textarea {
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
        <h1>Financial Planner </h1>
        <p>(Bcom Business Management)</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>I’m a driven individual who is dedicated and passionate about personal growth. I believe in the power of hard work, perseverance, and continuous learning to achieve success. Challenges motivate me, and I am always striving to push beyond my limits to grow and improve. My goal is to make a meaningful impact in everything I do, inspiring those around me to pursue their ambitions with confidence and determination. Success, for me, is not just about personal achievement but also about uplifting others and making a positive difference in the world.</p>
    </section>

    <section class="contact-info">
        <h2>Contact Information</h2>
        <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
        <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
    </section>

    <section class="book-meeting">
        <h2>Book a Meeting</h2>
        <form action="#" method="post">
            <div class="form-group">
                <label for="name">Name and Surname</label>
                <input type="text" id="name" name="name" placeholder="Your Name and Surname" required>
            </div>
            <div class="form-group">
                <label for="contact">Contact Details</label>
                <input type="text" id="contact" name="contact" placeholder="Your Contact Details" required>
            </div>
            <div class="form-group">
                <label for="date">Preferred Date</label>
                <input type="date" id="date" name="date" required>
            </div>
            <div class="form-group">
                <label for="time">Preferred Time</label>
                <input type="time" id="time" name="time" required>
            </div>
            <button type="submit">Book Meeting</button>
        </form>
    </section>

    <footer>
        <p>Connect with me: 
            <a href="https://www.sanlam.co.za" target="_blank">Sanlam Website</a> |
            <a href="https://www.linkedin.com/in/william-meyer" target="_blank">LinkedIn</a>
        </p>
    </footer>

</body>
</html>
