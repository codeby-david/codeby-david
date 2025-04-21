<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>About Me | David</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0f172a;
      color: #f8fafc;
      line-height: 1.6;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
    }

    h1, h2 {
      color: #38bdf8;
    }

    hr {
      border: none;
      height: 2px;
      background: linear-gradient(to right, #38bdf8, #3b82f6, #6366f1);
      margin: 2rem 0;
    }

    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      justify-content: center;
      padding: 2rem;
      background-color: #1e293b;
      border-radius: 1rem;
    }

    .tech-icon {
      font-size: 3rem;
      animation: twinkle 3s ease-in-out infinite;
    }

    .tech-icon:nth-child(2n) { animation-delay: 0.3s; }
    .tech-icon:nth-child(3n) { animation-delay: 0.6s; }
    .tech-icon:nth-child(4n) { animation-delay: 0.9s; }

    @keyframes twinkle {
      0%, 100% { transform: scale(1); opacity: 1; }
      50% { transform: scale(1.2); opacity: 0.6; }
    }

    a {
      color: #38bdf8;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>👋 Hi, I'm David</h1>
    <p>
      I'm a passionate Software Developer who thrives on solving real-world problems through code. I specialize in:
    </p>
    <ul>
      <li>🌐 Web Application Development</li>
      <li>📱 Mobile Application Development</li>
    </ul>
    <p>
      💡 <em>"Always up for a challenge!"</em><br>
      Or as my friends and colleagues like to say — I’m someone who thrives on exploring new ideas, experimenting, and constantly learning.
    </p>
    <p>
      ⚡ I'm currently sharpening my skills in <strong>Java, C++, PHP (Laravel), JavaScript, React, Tailwind CSS, TypeScript, Next.js, and APIs</strong>,
      with a strong focus on crafting innovative and impactful solutions.
    </p>

    <hr>

    <h2>🧰 Tech Stack</h2>

    <div class="tech-stack">
      <i class="devicon-html5-plain colored tech-icon"></i>
      <i class="devicon-css3-plain colored tech-icon"></i>
      <i class="devicon-javascript-plain colored tech-icon"></i>
      <i class="devicon-java-plain colored tech-icon"></i>
      <i class="devicon-c-plain colored tech-icon"></i>
      <i class="devicon-php-plain colored tech-icon"></i>
      <i class="devicon-flutter-plain colored tech-icon"></i>
      <i class="devicon-tailwindcss-plain colored tech-icon"></i>
      <i class="devicon-react-original colored tech-icon"></i>
      <i class="devicon-nextjs-original tech-icon" style="color:white;"></i>
      <i class="devicon-nodejs-plain colored tech-icon"></i>
      <i class="devicon-git-plain colored tech-icon"></i>
      <i class="devicon-github-original tech-icon" style="color:white;"></i>
      <i class="devicon-stackoverflow-plain colored tech-icon"></i>
    </div>

    <hr>

    <h2>🤝 Let’s Connect</h2>
    <ul>
      <li>💌 <a href="mailto:machariacodes@gmail.com">Email Me</a></li>
      <li>💼 <a href="https://www.linkedin.com/indavid-macharia001" target="_blank">LinkedIn</a></li>
      
    </ul>

    <p>👉 <em>Let’s build something <strong>awesome</strong> together!</em></p>
  </div>

</body>
</html>
