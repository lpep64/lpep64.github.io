<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto">
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }

        header {
            background-color: #333;
            padding: 1em 0;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-around;
        }

        nav a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: color 0.3s ease-in-out;
        }

        nav a:hover {
            color: #66a0ff;
        }

        main {
            padding: 2em;
        }

        .project {
            background-color: #f4f4f4;
            border-radius: 8px;
            padding: 1em;
            margin-bottom: 1em;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
    </style>
    <title>My Personal Portfolio</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h1>About Me</h1>
            <p>Hello! I'm a software engineer specializing in front-end development. My passion lies in creating intuitive and user-friendly web experiences.</p>
            <p>Feel free to browse through my portfolio and learn more about my projects. If you have any questions or would like to collaborate, please don't hesitate to get in touch!</p>
        </section>
        <section id="projects">
            <h2>My Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>A brief description of Project 1</p>
                <a href="https://github.com/lpep64/project1">View on GitHub</a>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>A brief description of Project 2</p>
                <a href="https://github.com/lpep64/project2">View on GitHub</a>
            </div>
            <!-- Add more projects as needed -->
        </section>
        <section id="contact">
            <h2>Contact Me</h2>
            <p>If you'd like to get in touch, you can find me on:</p>
            <ul>
                <li><a href="https://twitter.com/lpep64">Twitter</a></li>
                <li><a href="https://linkedin.com/in/lpep64">LinkedIn</a></li>
                <li><a href="mailto:lpep64@example.com">Email</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Luke Pepin. All rights reserved.</p>
    </footer>
</body>
</html>
