<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ram's Portfolio Banner</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(-45deg, #1e3c72, #2a5298, #1e3c72, #0f2027);
      background-size: 400% 400%;
      animation: gradientBG 15s ease infinite;
      color: white;
      text-align: center;
      padding: 2rem;
    }

    @keyframes gradientBG {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    h3 {
      font-size: 1.5rem;
      margin-bottom: 2rem;
    }

    img.banner {
      width: 100%;
      max-width: 900px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
      margin-bottom: 2rem;
    }

    section {
      max-width: 800px;
      margin: 0 auto 2rem;
      background-color: rgba(255,255,255,0.05);
      padding: 1rem 2rem;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.2);
    }

    .tech-stack img {
      margin: 0.5rem;
    }

    a {
      color: #00d8ff;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
    }

    .github-stats img {
      max-width: 100%;
      margin-top: 1rem;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <h1>👋 Hi, I'm Ram</h1>
  <h3>A passionate Full Stack Developer from India 🇮🇳</h3>

  <img class="banner" src="https://your-image-link.com/banner.png" alt="Banner" />

  <section>
    <h2>👨‍💻 About Me</h2>
    <p>🌱 I’m currently working on <strong>Think Flow Connect</strong></p>
    <p>💬 Ask me about <strong>AI, drones, and web development</strong></p>
    <p>📫 Reach me: 
      <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn</a> | 
      <a href="mailto:you@example.com">Email</a>
    </p>
    <p>⚡ Fun fact: I love hacking things together and exploring new tech!</p>
  </section>

  <section class="tech-stack">
    <h2>🛠️ Tech Stack</h2>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white" alt="Supabase" />
    <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  </section>

  <section class="github-stats">
    <h2>📊 GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=ramjs&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
  </section>

</body>
</html>
