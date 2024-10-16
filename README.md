# grigoliAI<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Website</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }

        header {
            background-color: #007bff;
            padding: 20px;
            text-align: center;
            color: #fff;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            background-color: #343a40;
            padding: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: 700;
        }

        nav a:hover {
            color: #007bff;
        }

        .section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        #about {
            background-color: #ffffff;
        }

        #projects {
            background-color: #f0f0f0;
        }

        #contact {
            background-color: #ffffff;
        }

        footer {
            background-color: #343a40;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        .btn {
            background-color: #007bff;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>

<body>
    <header>
        <h1>Business Name</h1>
        <p>Connecting opportunities in HORECA</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about" class="section">
        <h2>About Me</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.</p>
    </section>

    <section id="projects" class="section">
        <h2>My Projects</h2>
        <div class="projects">
            <p>Project 1: Description of the project goes here.</p>
            <p>Project 2: Description of the project goes here.</p>
            <p>Project 3: Description of the project goes here.</p>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Me</h2>
        <p>If you would like to get in touch, please email me at <a href="mailto:info@business.com">info@business.com</a> or use the contact form below:</p>
        <form action="#">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
            <input type="submit" value="Send">
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Business Name. All rights reserved.</p>
    </footer>
</body>

</html>
