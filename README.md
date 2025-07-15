<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deepam Kumar | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }
    body {
      background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
      color: white;
      overflow-x: hidden;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 2rem;
      background-color: #121212;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
    }
    header img {
      height: 80px;
      border-radius: 50%;
    }
    header h1 {
      font-size: 2rem;
      color: #00ffc3;
    }
    section.hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 4rem 2rem;
      position: relative;
    }
    section.hero::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('https://assets-global.website-files.com/5fa85d30d2f0111e7c270a1b/5fc65a3f2ed18b8be7f9f2dc_wave-haikei.svg') no-repeat center center/cover;
      z-index: -1;
      opacity: 0.1;
    }
    section.hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      color: #00d8ff;
    }
    section.hero p {
      font-size: 1.2rem;
      max-width: 800px;
    }
    .socials {
      margin-top: 2rem;
    }
    .socials a {
      margin: 0 1rem;
      font-size: 1.8rem;
      color: white;
      text-decoration: none;
      transition: color 0.3s;
    }
    .socials a:hover {
      color: #00ffc3;
    }
    section {
      padding: 4rem 2rem;
    }
    section h3 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
      color: #00d8ff;
      text-align: center;
    }
    .grid-2 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .card {
      background-color: #222;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 0 20px rgba(0,255,195,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 25px rgba(0,255,195,0.3);
    }
    section.testimonials {
      background: #181818;
    }
    .testimonial {
      font-style: italic;
      font-size: 1rem;
      color: #ccc;
      border-left: 4px solid #00ffc3;
      padding-left: 1rem;
    }
    .resume {
      text-align: center;
      margin-top: 2rem;
    }
    .resume a {
      background-color: #00d8ff;
      padding: 0.8rem 2rem;
      color: #000;
      text-decoration: none;
      border-radius: 2rem;
      font-weight: bold;
      transition: background 0.3s;
    }
    .resume a:hover {
      background-color: #00ffc3;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background-color: #111;
      font-size: 0.9rem;
      color: #ccc;
    }
  </style>
</head>
<body>
  <header>
    <h1>Deepam Kumar</h1>
    <img src="https://www.excelrs.xyz/images/1000246933.png" alt="Deepam Kumar">
  </header>  <section class="hero" data-aos="fade-up">
    <h2>Creative Developer | Designer | Dreamer</h2>
    <p>I am Deepam Kumar, a passionate individual with a vision to innovate and inspire. From engineering to design and beyond, I believe in turning ideas into reality with creativity and dedication.</p>
    <div class="socials">
      <a href="mailto:kdeepam59@gmail.com">📧</a>
      <a href="https://www.linkedin.com/in/deepam-kumar-39332432b" target="_blank">💼</a>
      <a href="https://www.instagram.com/deepam_810" target="_blank">📸</a>
    </div>
  </section>  <section class="about" data-aos="fade-up">
    <h3>About Me</h3>
    <p>I’m currently pursuing B.Tech in Electronics and Communication Engineering and a BA in Economics. I'm the founder of startups like Divyanshi AlkaFresh and RePlastX. I’m a dreamer, a doer, and a believer in making life better through design, tech, and grit. I dream of my Tata Harrier and building tools that change the world.</p>
  </section>  <section class="skills" data-aos="fade-up">
    <h3>Skills</h3>
    <div class="grid-2">
      <div class="card">💻 HTML, CSS, JavaScript</div>
      <div class="card">🎨 UI/UX Design, Canva, Figma</div>
      <div class="card">🤖 ChatGPT Prompt Engineering</div>
      <div class="card">🚀 Startup Planning & Execution</div>
      <div class="card">🧠 Branding & Marketing</div>
      <div class="card">🖼️ Poster, Logo & Invite Design</div>
    </div>
  </section>  <section class="projects" data-aos="fade-up">
    <h3>Projects</h3>
    <div class="grid-2">
      <div class="card"><strong>Divyanshi AlkaFresh</strong><br>Alkaline water startup bringing pure hydration to life.</div>
      <div class="card"><strong>RePlastX</strong><br>Plastic exchange-for-rewards model for sustainable recycling.</div>
      <div class="card"><strong>SRXplore Internship Hub</strong><br>Helping 1st-year students access real opportunities.</div>
      <div class="card"><strong>Emotional AI Video</strong><br>Voice, visuals & dreams combined to move hearts.</div>
    </div>
  </section>  <section class="education" data-aos="fade-up">
    <h3>Education</h3>
    <div class="grid-2">
      <div class="card"><strong>B.Tech in ECE</strong><br>JUT University | CGPA: 8.9</div>
      <div class="card"><strong>BA in Economics</strong><br>RPS College, Harnaut</div>
      <div class="card"><strong>10th - 65%</strong><br>12th - 55%</div>
    </div>
  </section>  <section class="testimonials" data-aos="fade-up">
    <h3>What People Say</h3>
    <div class="grid-2">
      <div class="testimonial">“Deepam’s ideas are innovative and full of passion.”</div>
      <div class="testimonial">“His designs always feel fresh and meaningful.”</div>
    </div>
  </section>  <section class="contact" data-aos="fade-up">
    <h3>Get In Touch</h3>
    <p>
      📧 kdeepam59@gmail.com <br>
      📍 Harnaut, Nalanda, Bihar <br>
      📱 DM me on Instagram: @deepam_810
    </p>
    <div class="resume">
      <a href="#">📄 Download Resume</a>
    </div>
  </section>  <footer>
    &copy; 2025 Deepam Kumar | Designed with ❤️ and powered by vision.
  </footer>  <script src="https://unpkg.com/aos@next/dist/aos.js"></script>  <script>
    AOS.init({ duration: 1000 });
  </script></body>
</html>