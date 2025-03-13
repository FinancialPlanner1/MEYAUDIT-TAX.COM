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
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background-color: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 600px;
            width: 100%;
        }
        h1, h2, h3 {
            color: #006f73;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
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
            margin-top: 10px;
        }
        button:hover {
            background-color: #004f53;
        }
        a {
            color: #1e90ff;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>William Meyer</h1>
        <h2>Financial Planner | BCom Business Management</h2>
        <h3>Authorised by Sanlam | Lonfin MOB</h3>

        <section>
            <h2>About Me</h2>
            <p>
                I’m a driven individual who is dedicated and passionate about personal growth. I believe in the power of hard work, perseverance, and continuous learning to achieve success. Challenges motivate me, and I am always striving to push beyond my limits to grow and improve. 
                My goal is to make a meaningful impact in everything I do, inspiring those around me to pursue their ambitions with confidence and determination. Success, for me, is not just about personal achievement but also about uplifting others and making a positive difference in the world.
            </p>
        </section>

        <section>
            <h2>Contact Information</h2>
            <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
            <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
            <p>Connect with me: 
                <a href="https://www.sanlam.co.za" target="_blank">Sanlam Website</a> | 
                <a href="https://www.linkedin.com/in/william-meyer" target="_blank">LinkedIn</a>
            </p>
        </section>

        <section>
            <h2>Book a Meeting</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Name and Surname" required>
                <input type="text" name="contact" placeholder="Contact Details" required>
                <input type="date" name="date" required>
                <input type="time" name="time" required>
                <button type="submit">Book Meeting</button>
            </form>
        </section>
    </div>
</body>
</html>
