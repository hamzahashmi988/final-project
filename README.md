<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project</title>

    <!-- Embedded CSS -->
    <style>
        /* Global styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header, footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 2rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
        }

        /* About Us Page */
        .about-us p {
            margin: 10px 0;
        }

        .about-us img {
            width: 100%;
            height: auto;
        }

        /* Contact Us Page */
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            padding: 2rem;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .contact-form label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .recommendations img {
            width: 48%;
            height: auto;
            margin: 1%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Beach and Temple Recommendations</h1>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <!-- Home Section -->
    <section id="home" class="container">
        <h2>Welcome to Our Travel Recommendations</h2>
        <p>Explore some of the most beautiful beach and temple destinations around the world.</p>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about-us container">
        <h2>About Us</h2>
        <p>We are passionate about exploring the world's best beaches and temples. Join us as we share our top picks.</p>
        <img src="about-us-image.jpg" alt="About Us Image">
    </section>

    <!-- Contact Us Section -->
    <section id="contact" class="contact-form container">
        <h2>Contact Us</h2>
        <form>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Beach Recommendation Section -->
    <section class="recommendations container">
        <h2>Beach Recommendations</h2>
        <div>
            <img src="beach1.jpg" alt="Beach 1">
            <img src="beach2.jpg" alt="Beach 2">
        </div>
    </section>

    <!-- Temple Recommendation Section -->
    <section class="recommendations container">
        <h2>Temple Recommendations</h2>
        <div>
            <img src="temple1.jpg" alt="Temple 1">
            <img src="temple2.jpg" alt="Temple 2">
        </div>
    </section>

    <!-- Recommendation Based on Country -->
    <section class="recommendations container">
        <h2>Recommendations by Country</h2>
        <div>
            <img src="country1.jpg" alt="Country 1">
            <img src="country2.jpg" alt="Country 2">
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Copyright &copy; 2024 Beach and Temple Recommendations</p>
    </footer>

    <!-- Embedded JavaScript -->
    <script>
        // Example JavaScript (for form submission, etc.)
        document.querySelector('form').addEventListener('submit', function (event) {
            event.preventDefault();
            alert('Thank you for your message!');
        });
    </script>
</body>

</html>

    </header>
    <main>
        <h1>Welcome to Our Website!</h1>
        <p>This is an introduction to our website. We provide travel recommendations based on your interests!</p>
    </main>
</body>
</html>
