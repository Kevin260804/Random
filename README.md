<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
        header { background: #333; color: white; padding: 10px 20px; text-align: center; }
        section { margin: 20px; padding: 20px; background: white; }
        footer { background: #333; color: white; text-align: center; padding: 10px 20px; }
        .portfolio-item { margin-bottom: 20px; }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>Here's a showcase of my work.</p>
    </header>
    
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-item">
            <h3>Project Title 1</h3>
            <p>Description of the project. What was your role, what technologies were used, etc.</p>
        </div>
        <div class="portfolio-item">
            <h3>Project Title 2</h3>
            <p>Description of the project. What was your role, what technologies were used, etc.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <form action="submit_form.php" method="POST">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Send">
        </form>
    </section>

    <footer>
        <p>Copyright © Your Name 2024</p>
    </footer>
</body>
</html>
