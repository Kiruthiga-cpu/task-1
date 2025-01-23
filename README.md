# task-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Your Name</h1>
        <p>Your Introduction or Tagline</p>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="your-image.jpg" alt="Your Name">
        <p>Short bio highlighting your skills and experience.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Skill 1</li>
            <li>Skill 2</li>
            <li>Skill 3</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title</h3>
            <img src="project-image.jpg" alt="Project Title">
            <p>Project description.</p>
        </div>
    </section>

    <!-- Resume Section -->
    <section id="resume">
        <h2>Resume</h2>
        <a href="your-resume.pdf" download>Download My Resume</a>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: your-email@example.com</p>
        <p>Phone: your-phone-number</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
#css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

section {
    margin: 20px;
    padding: 20px;
    border-bottom: 1px solid #ddd;
}

h2 {
    border-bottom: 2px solid #333;
}

#about img, .project img {
    max-width: 100%;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
