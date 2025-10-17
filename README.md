<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>KL Student Portfolio - Your Name</title>
  <style>
    /* ====== Global Styles ====== */
    body {
      font-family: "Poppins", sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f7fa;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #003366;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    header p {
      font-size: 1.1rem;
    }

    /* ====== Main Layout ====== */
    main {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
      gap: 2rem;
    }

    section {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      padding: 1.5rem;
      flex: 1 1 300px;
      max-width: 600px;
    }

    h2 {
      border-bottom: 2px solid #003366;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }

    /* ====== Project Cards ====== */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .project-card {
      background: #e6ecf3;
      padding: 1rem;
      border-radius: 8px;
      transition: transform 0.3s ease;
    }

    .project-card:hover {
      transform: translateY(-5px);
    }

    /* ====== Footer ====== */
    footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    /* ====== Responsive Design ====== */
    @media (max-width: 768px) {
      header h1 {
        font-size: 1.5rem;
      }

      main {
        flex-direction: column;
        padding: 1rem;
      }

      section {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <p>KL University Student | Web Developer | Tech Enthusiast</p>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        Hello! I'm a student at KL University passionate about web development,
        design, and problem-solving. I enjoy creating clean, user-friendly
        interfaces and learning new technologies.
      </p>
    </section>

    <section id="projects">
      <h2>My Projects</h2>
      <div class="projects">
        <div class="project-card">
          <h3>Portfolio Website</h3>
          <p>A personal portfolio showcasing my projects and skills using HTML, CSS, and JavaScript.</p>
        </div>
        <div class="project-card">
          <h3>Student Portal App</h3>
          <p>An interactive dashboard for students to view grades, attendance, and announcements.</p>
        </div>
        <div class="project-card">
          <h3>Weather App</h3>
          <p>A responsive web app that fetches real-time weather data using an API.</p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2025 Your Name | KL Student Portfolio</p>
  </footer>
</body>
</html>
