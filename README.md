<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ritik Kumar | Video Editor</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }
    body {
      background: #0f0f0f;
      color: #fff;
      line-height: 1.6;
    }
    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
    }
    header span {
      color: #7c3aed;
    }
    header p {
      margin: 15px 0;
      color: #aaa;
    }
    .btn {
      padding: 10px 20px;
      margin: 10px;
      border: none;
      background: #7c3aed;
      color: #fff;
      cursor: pointer;
      border-radius: 5px;
      text-decoration: none;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    h2 {
      margin-bottom: 20px;
      font-size: 2rem;
    }
    .skills, .projects {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }
    .card {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      width: 200px;
      transition: 0.3s;
    }
    .card:hover {
      transform: translateY(-10px);
      background: #7c3aed;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
    }
  </style>
</head>
<body>
  <!-- Hero Section -->
  <header>
    <h1>Hi, I'm <span>Ritik Kumar</span></h1>
    <p>Creative Video Editor 🎥</p>
    <p>I turn raw clips into engaging stories.</p>
    <a href="#projects" class="btn">View My Work</a>
    <a href="#contact" class="btn">Contact Me</a>
  </header>
  <!-- About -->
  <section>
    <h2>About Me</h2>
    <p>
      I am a passionate video editor with a creative mindset and strong attention to detail.
      I specialize in transforming raw footage into visually appealing and engaging videos.
      Currently, I am continuously learning and improving my editing skills.
    </p>
  </section>
  <!-- Skills -->
  <section>
    <h2>Skills</h2>
    <div class="skills">
      <div class="card">Video Editing</div>
      <div class="card">Transitions</div>
      <div class="card">Color Correction</div>
      <div class="card">Reels / Shorts Editing</div>
    </div>
  </section>
  <!-- Projects -->
  <section id="projects">
    <h2>Projects</h2>
    <p>Projects coming soon... 🚀</p>
  </section>
  <!-- Contact -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: ritikthakur9708@gmail.com</p>
    <p>Instagram: @yourusername</p>
    <p>WhatsApp: +91 9234663428</p>
  </section>
  <!-- Footer -->
  <footer>
    <p>© 2026 Ritik Kumar | Video Editor</p>
  </footer>
</body>
</html>
