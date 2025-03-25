<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hannah Sanders - Marketing Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #FFDEE9, #B5FFFC);
            color: #333;
            text-align: center;
        }
        header {
            background: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 20px 0;
            position: sticky;
            top: 0;
            width: 100%;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 50px;
        }
        .project {
            background: rgba(255, 255, 255, 0.8);
            padding: 20px;
            margin: 20px auto;
            border-radius: 10px;
            max-width: 600px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }
        form input, form textarea {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            background: #FF5E78;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            background: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 20px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hannah Sanders</h1>
        <p>Marketing & Event Branding Portfolio</p>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hi! I'm Hannah Sanders, an Integrated Marketing Communications specialist with a background in hospitality and a passion for branding, digital marketing, and event promotions.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Care/Of Vitamins Analysis</h3>
            <p>Conducted an in-depth analysis of Care/Of, a personalized vitamin subscription service, focusing on branding, target audience, and keyword optimization.</p>
        </div>
        <div class="project">
            <h3>Board Retreat Event Branding</h3>
            <p>Designed marketing collateral for a Board Retreat event, ensuring a professional and engaging visual identity.</p>
        </div>
        <div class="project">
            <h3>Small Business Expo Marketing</h3>
            <p>Developed promotional material and an invitation letter for a business expo supporting entrepreneurs.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Hannah Sanders | Marketing Portfolio</p>
    </footer>
</body>
</html>
