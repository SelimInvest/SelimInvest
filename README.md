<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selim Invest - Personal Webpage</title>
    <style>
        /* Reset styles */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            color: #333;
        }

        /* Container styles */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Header styles */
        header {
            background-color: #004d40;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 18px;
        }

        /* Navigation styles */
        nav {
            background-color: #00796b;
            text-align: center;
            padding: 10px 0;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-size: 18px;
        }

        /* Main content styles */
        main {
            padding: 20px 0;
        }

        h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }

        p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 20px;
        }

        /* Membership section styles */
        .membership-section {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .membership-section h2 {
            color: #004d40;
            margin-bottom: 10px;
        }

        .membership-section p {
            margin-bottom: 20px;
        }

        .membership-form {
            max-width: 400px;
            margin: 0 auto;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            font-weight: bold;
            margin-bottom: 5px;
            color: #333;
        }

        .form-group input[type="text"],
        .form-group input[type="email"] {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }

        .form-group input[type="submit"] {
            background-color: #004d40;
            color: #fff;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .form-group input[type="submit"]:hover {
            background-color: #00796b;
        }

        footer {
            background-color: #004d40;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Selim Invest</h1>
            <p>Welcome to my personal webpage!</p>
        </header>

        <nav>
            <ul>
                <li><a href="#membership">Membership</a></li>
                <li><a href="#bio">Bio</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#projects">Projects</a></li>
            </ul>
        </nav>

        <main>
            <section id="membership" class="membership-section">
                <h2>Membership Sign-up</h2>
                <p>Join our exclusive membership for access to premium content and special offers!</p>
                <form class="membership-form">
                    <div class="form-group">
                        <label for="fullname">Full Name:</label>
                        <input type="text" id="fullname" name="fullname" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email Address:</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <input type="submit" value="Sign Up">
                    </div>
                </form>
            </section>

            <section id="bio">
                <h2>Bio</h2>
                <p>Welcome to my personal webpage! I'm Selim Invest.</p>
            </section>

            <section id="contact">
                <h2>Contact Information</h2>
                <p>Email: selim@example.com</p>
                <p>Phone: +123456789</p>
                <p>Location: City, Country</p>
            </section>

            <section id="portfolio">
                <h2>Portfolio</h2>
                <div class="portfolio-content">
                    <div class="portfolio-item">
                        <h3>Project 1</h3>
                        <p>Description of Project 1</p>
                    </div>
                    <div class="portfolio-item">
                        <h3>Project 2</h3>
                        <p>Description of Project 2</p>
                    </div>
                    <div class="portfolio-item">
                        <h3>Project 3</h3>
                        <p>Description of Project 3</p>
                    </div>
                </div>
            </section>

            <section id="blog">
                <h2>Blog</h2>
                <div class="blog-post">
                    <h3>Blog Post 1</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam aliquet est euismod, efficitur elit ac, sodales nisl.</p>
                    <a href="#">Read More</a>
                </div>
                <div class="blog-post">
                    <h3>Blog Post 2</h3>
                    <p>Integer at nisl id augue pretium tincidunt. Fusce id nisi nec mi varius fringilla eu sit amet eros.</p>
                    <a href="#">Read More</a>
                </div>
            </section>
        </main>

        <footer>
            <p>&copy; 2024 Selim Invest</p>
        </footer>
    </div>
</body>
</html>
