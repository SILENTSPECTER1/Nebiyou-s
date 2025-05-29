<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Your Name | Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --main-color: #2c3e50;
      --accent-color: #3498db;
      --bg-color: #ecf0f1;
      --text-color: #222;
      --card-bg: #fff;
      --shadow: 0 2px 8px rgba(44, 62, 80, 0.08);
    }
    body {
      margin: 0;
      padding: 0;
      background: var(--bg-color);
      font-family: 'Segoe UI', Arial, sans-serif;
      color: var(--text-color);
    }
    header {
      background: var(--main-color);
      color: #fff;
      padding: 2rem 0 1rem 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin: 0.5rem 0 1.5rem 0;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 1.2rem;
      font-weight: bold;
      transition: color 0.2s;
    }
    nav a:hover {
      color: var(--accent-color);
    }
    .container {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      margin-bottom: 2.5rem;
    }
    h2 {
      color: var(--main-color);
      margin-bottom: 0.5rem;
      border-bottom: 2px solid var(--accent-color);
      display: inline-block;
      padding-bottom: 0.25rem;
    }
    .about {
      background: var(--card-bg);
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: var(--shadow);
      margin-bottom: 2rem;
      line-height: 1.7;
    }
    .projects {
      display: grid;
      gap: 1.5rem;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
    .project-card {
      background: var(--card-bg);
      border-radius: 10px;
      box-shadow: var(--shadow);
      padding: 1.2rem;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .project-card:hover {
      transform: translateY(-5px) scale(1.02);
      box-shadow: 0 8px 24px rgba(44,62,80,0.13);
    }
    .project-card h3 {
      margin-top: 0;
      color: var(--accent-color);
    }
    .project-card p {
      font-size: 1rem;
      color: #444;
    }
    .project-card a {
      display: inline-block;
      margin-top: 0.8rem;
      color: var(--accent-color);
      text-decoration: none;
      font-weight: 500;
    }
    .project-card a:hover {
      text-decoration: underline;
    }
    .contact {
      background: var(--card-bg);
      padding: 1.2rem;
      border-radius: 10px;
      box-shadow: var(--shadow);
      text-align: center;
    }
    .social-links a {
      display: inline-block;
      margin: 0 0.7rem;
      color: var(--main-color);
      font-size: 1.5rem;
      transition: color 0.2s;
      text-decoration: none;
    }
    .social-links a:hover {
      color: var(--accent-color);
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      .projects {
        grid-template-columns: 1fr;
      }
    }
  </style>
  <!-- Font Awesome for icons (CDN) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <p>Web Developer • Designer • Programmer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  
  <div class="container">
    <section id="about">
      <h2>About Me</h2>
      <div class="about">
        <p>
          Hi! I'm <strong>Your Name</strong>, a passionate web developer with experience in building modern, responsive websites and applications.<br>
          I love working with <b>HTML</b>, <b>CSS</b>, <b>JavaScript</b>, and frameworks like <b>React</b>.<br>
          I'm always eager to learn new technologies and take on exciting challenges!
        </p>
      </div>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="projects">
        <div class="project-card">
          <h3>Portfolio Website</h3>
          <p>A personal website to showcase my projects, skills, and contact info. Built with HTML, CSS, and a sprinkle of JavaScript for interactivity.</p>
          <a href="#" target="_blank">View Project</a>
        </div>
        <div class="project-card">
          <h3>ToDo App</h3>
          <p>A simple and effective ToDo list application allowing users to keep track of tasks. Built using React and local storage.</p>
          <a href="#" target="_blank">View Project</a>
        </div>
        <div class="project-card">
          <h3>Weather Dashboard</h3>
          <p>Displays real-time weather info for any city using a public API. Developed with JavaScript and OpenWeatherMap API.</p>
          <a href="#" target="_blank">View Project</a>
        </div>
        <!-- Add more projects as needed -->
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="contact">
        <p>
          Want to work together or have a question?<br>
          <b>Email:</b> <a href="mailto:your.email@example.com">your.email@example.com</a>
        </p>
        <div class="social-links">
          <a href="https://github.com/yourusername" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
          <a href="https://linkedin.com/in/yourlinkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
          <a href="https://twitter.com/yourtwitter" target="_blank" title="Twitter"><i class="fab fa-twitter"></i></a>
        </div>
      </div>
    </section>
  </div>
</body>
</html>

