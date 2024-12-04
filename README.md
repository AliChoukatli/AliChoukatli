<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    section {
      padding: 20px;
      margin: 10px;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
    }
    .skills, .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }
    .card {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 20px;
      width: 300px;
    }
    .card h3 {
      margin: 0 0 10px;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <p>Cybersecurity Professional | QA Expert | Web Developer</p>
  </header>

  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>Welcome to my portfolio! I'm a passionate cybersecurity professional and software tester with a focus on automation and risk analysis. I specialize in ensuring quality and security in software development, and I'm always learning new ways to improve systems.</p>
    </div>
  </section>

  <section id="skills">
    <div class="container">
      <h2>Skills</h2>
      <div class="skills">
        <div class="card">
          <h3>Cybersecurity</h3>
          <p>Risk analysis, penetration testing, and incident response.</p>
        </div>
        <div class="card">
          <h3>Software Testing</h3>
          <p>Manual testing, test automation, performance testing, and bug tracking.</p>
        </div>
        <div class="card">
          <h3>Web Development</h3>
          <p>HTML, CSS, JavaScript, React, and responsive design.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2>Projects</h2>
      <div class="projects">
        <div class="card">
          <h3>Project 1</h3>
          <p>A web application I built to demonstrate skills in React and Node.js.</p>
          <a href="https://github.com/yourusername/project1" target="_blank">View on GitHub</a>
        </div>
        <div class="card">
          <h3>Project 2</h3>
          <p>A tool to automate security testing with Selenium and Python.</p>
          <a href="https://github.com/yourusername/project2" target="_blank">View on GitHub</a>
        </div>
        <div class="card">
          <h3>Project 3</h3>
          <p>A portfolio site built using HTML, CSS, and JavaScript.</p>
          <a href="https://github.com/yourusername/portfolio" target="_blank">View on GitHub</a>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact</h2>
      <p>If you'd like to get in touch, feel free to reach out via the following:</p>
      <ul>
        <li>Email: your.email@example.com</li>
        <li>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn Profile</a></li>
        <li>GitHub: <a href="https://github.com/yourusername" target="_blank">GitHub Profile</a></li>
      </ul>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>
