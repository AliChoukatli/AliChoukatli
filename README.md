<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ali Choukatli - Portfolio</title>
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
    <h1>Ali Choukatli</h1>
    <p>Passionné de cybersécurité | Expert en Assurance Qualité | Développeur Web</p>
  </header>

  <section id="about">
    <div class="container">
      <h2>À propos de moi</h2>
      <p>Je suis un professionnel de la cybersécurité et de l'assurance qualité avec un fort intérêt pour l'automatisation des tests et la gestion des risques. Mon objectif est d'apporter de la valeur en améliorant la sécurité et l'efficacité des systèmes en utilisant mes compétences en analyse des risques et en gestion de la continuité des affaires.</p>
    </div>
  </section>

  <section id="skills">
    <div class="container">
      <h2>Compétences</h2>
      <div class="skills">
        <div class="card">
          <h3>Cybersécurité</h3>
          <p>Analyse des risques, tests d'intrusion, réponse aux incidents.</p>
        </div>
        <div class="card">
          <h3>Assurance Qualité</h3>
          <p>Tests manuels, automatisation des tests, suivi des bogues et validation.</p>
        </div>
        <div class="card">
          <h3>Développement Web</h3>
          <p>HTML, CSS, JavaScript, React, et conception responsive.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2>Projets</h2>
      <div class="projects">
        <div class="card">
          <h3>Projet 1</h3>
          <p>Un outil de test de sécurité automatisé développé avec Selenium et Python.</p>
          <a href="https://github.com/yourusername/project1" target="_blank">Voir sur GitHub</a>
        </div>
        <div class="card">
          <h3>Projet 2</h3>
          <p>Une application web pour démontrer mes compétences en développement frontend avec React.</p>
          <a href="https://github.com/yourusername/project2" target="_blank">Voir sur GitHub</a>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact</h2>
      <p>Si vous souhaitez me contacter, vous pouvez m'envoyer un message via les plateformes suivantes :</p>
      <ul>
        <li>Email: <a href="mailto:ali@example.com">ali@example.com</a></li>
        <li>LinkedIn: <a href="https://www.linkedin.com/in/ali-choukatli" target="_blank">Mon profil LinkedIn</a></li>
        <li>GitHub: <a href="https://github.com/ali" target="_blank">Mon profil GitHub</a></li>
      </ul>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Ali Choukatli. Tous droits réservés.</p>
  </footer>

</body>
</html>
