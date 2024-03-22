  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Guide</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #000; /* Black background */
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .main-content {
            padding: 20px;
            text-align: center;
        }

        .destination {
            margin-bottom: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Form Styles */
        form {
            background-color: #fff;
            border-radius: 5px;
            padding: 20px;
            width: 300px;
            margin: 0 auto;
        }

        input[type="text"],
        textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        textarea {
            height: 100px;
        }

        input[type="submit"] {
            background-color: #007bff;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }

        /* Image Styles */
        .destination img {
            max-width: 100%;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Travel Guide</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#search">Search</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#feedback">Feedback</a></li>
            </ul>
        </nav>
    </header>

    <div id="home" class="main-content">
        <h2>Welcome to the Travel Guide!</h2>
        <p>Discover your next adventure...</p>
    </div>

    <div id="destinations" class="main-content">
        <h2>Explore Popular Destinations</h2>
        <div class="destination">
            <img src="destination1.jpg" alt="Destination 1">
            <p>Description of Destination 1</p>
        </div>
        <div class="destination">
            <img src="destination2.jpg" alt="Destination 2">
            <p>Description of Destination 2</p>
        </div>
        <!-- Add more destinations as needed -->
    </div>

    <div id="search" class="main-content">
        <h2>Search for Your Dream Destination</h2>
        <p>Find the perfect place for your next adventure...</p>
    </div>

    <div id="about" class="main-content">
        <h2>About Travel Guide</h2>
        <p>Learn more about our mission and vision...</p>
    </div>

    <div id="feedback" class="main-content">
        <h2>Feedback</h2>
        <p>We'd love to hear from you!</p>
        <form action="submit_feedback.php" method="POST">
            <input type="text" name="name" placeholder="Your Name" required><br>
            <input type="text" name="email" placeholder="Your Email" required><br>
            <textarea name="message" placeholder="Your Message" required></textarea><br>
            <input type="submit" value="Submit">
        </form>
    </div>

    <footer>
        <p>&copy; 2024 Travel Guide. All rights reserved.</p>
    </footer>
</body>
</html>
