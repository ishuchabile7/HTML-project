
Page 1: index.html (Homepage)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h2>Hi, I'm [Your Name]</h2>
            <p>A passionate [Your Profession] showcasing my work.</p>
            <a href="projects.html" class="button">View My Projects</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 [Your Name]</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

Page 2: about.html (About Me)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <h1>About Me</h1>
    </header>
    <main>
        <section class="about-content">
            <p>Here you can write a detailed description about yourself, your background, and your interests. Talk about your journey and what drives you.</p>
            <p>You can also include information about your education and experiences.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 [Your Name]</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

Page 3: projects.html (Projects)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Projects</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <h1>My Projects</h1>
    </header>
    <main>
        <section class="project-list">
            <div class="project-item">
                <h3>Project 1</h3>
                <p>A brief description of Project 1.</p>
                <a href="#">View Project</a>
            </div>
            <div class="project-item">
                <h3>Project 2</h3>
                <p>A brief description of Project 2.</p>
                <a href="#">View Project</a>
            </div>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 [Your Name]</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

Page 4: skills.html (Skills)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Skills</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <h1>My Skills</h1>
    </header>
    <main>
        <section class="skills-list">
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>[Add more skills here]</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 [Your Name]</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

Page 5: contact.html (Contact)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <h1>Contact Me</h1>
    </header>
    <main>
        <section class="contact-form">
            <p>Feel free to reach out to me!</p>
            </section>
    </main>
    <footer>
        <p>&copy; 2025 [Your Name]</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

style.css (Basic CSS - You'll need to create this file):
body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin-right: 1em;
}

nav a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.hero {
    text-align: center;
    padding: 50px 0;
}

.button {
    display: inline-block;
    background-color: #5cb85c;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.project-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.project-item {
    background-color: white;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.skills-list ul {
    list-style: disc;
    padding-left: 20px;
}

footer {
    text-align: center;
    padding: 1em;
    background-color: #333;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}

