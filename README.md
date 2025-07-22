<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Deepam Kumar - The Cinegineer</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background: linear-gradient(270deg, #0f2027, #203a43, #2c5364);
      background-size: 600% 600%;
      animation: gradientBG 15s ease infinite;
      color: #fff;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header {
      text-align: center;
      padding: 2rem;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid #fff;
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.5);
      animation: bounceIn 1s ease-out;
    }

    @keyframes bounceIn {
      0% { transform: scale(0.3); opacity: 0; }
      50% { transform: scale(1.1); opacity: 1; }
      70% { transform: scale(0.9); }
      100% { transform: scale(1); }
    }

    h1 {
      margin-top: 1rem;
      font-size: 2.5rem;
    }

    h2 {
      margin-top: 2rem;
      font-size: 2rem;
      border-bottom: 2px solid #fff;
      display: inline-block;
      padding-bottom: 0.5rem;
    }

    section {
      padding: 2rem;
      text-align: center;
    }

    .skills, .contact {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .skill, .contact a {
      background: rgba(255, 255, 255, 0.1);
      padding: 1rem 2rem;
      border-radius: 10px;
      transition: all 0.3s ease;
    }

    .skill:hover, .contact a:hover {
      background: rgba(255, 255, 255, 0.2);
      transform: scale(1.05);
    }

    .contact a {
      text-decoration: none;
      color: #fff;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background-color: rgba(255,255,255,0.05);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://www.excelrs.xyz/images/1000246933.png" alt="Deepam Kumar" onerror="this.onerror=null;this.src='https://via.placeholder.com/150';">
    <h1>Deepam Kumar</h1>
    <p>The Cinegineer 🎬⚙️</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>I am a student of Electronics & Communication Engineering with a deep passion for film direction and scriptwriting. My love for both technology and cinema defines me as 'The Cinegineer'.</p>
  </section>

  <section>
    <h2>Skills</h2>
    <div class="skills">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Python</div>
      <div class="skill">Video Editing</div>
      <div class="skill">Script Writing</div>
      <div class="skill">Direction</div>
      <div class="skill">AI & ChatGPT</div>
    </div>
  </section>

  <section>
    <h2>Connect With Me</h2>
    <div class="contact">
      <a href="mailto:kdeepam59@gmail.com">Email</a>
      <a href="https://www.linkedin.com/in/deepam-kumar-39332432b">LinkedIn</a>
      <a href="https://www.instagram.com/deepam_810">Instagram</a>
    </div>
  </section>

  <footer>
    © 2025 Deepam Kumar. All Rights Reserved.
  </footer>
</body>
</html>
