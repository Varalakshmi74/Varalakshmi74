<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Varalakshmi | AI/ML Developer</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      min-height: 100vh;
      background: #050505;
      color: white;
      overflow-x: hidden;
    }

    /* 3D Background */
    .background {
      position: fixed;
      inset: 0;
      overflow: hidden;
      z-index: -1;
      background:
        radial-gradient(circle at 20% 20%, #24104d 0%, transparent 35%),
        radial-gradient(circle at 80% 70%, #063b55 0%, transparent 35%),
        #050505;
    }

    .cube {
      position: absolute;
      width: 180px;
      height: 180px;
      border: 2px solid rgba(0, 255, 255, 0.3);
      transform: rotate(45deg);
      animation: float 8s infinite ease-in-out;
      box-shadow: 0 0 40px rgba(0,255,255,.15);
    }

    .cube:nth-child(1) {
      top: 15%;
      left: 8%;
    }

    .cube:nth-child(2) {
      right: 10%;
      bottom: 15%;
      width: 250px;
      height: 250px;
      border-color: rgba(150, 0, 255, .3);
      animation-delay: 2s;
    }

    @keyframes float {
      0%,100% {
        transform: rotate(45deg) translateY(0);
      }

      50% {
        transform: rotate(65deg) translateY(-35px);
      }
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
      padding: 80px 0;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    .tag {
      color: #00ffff;
      letter-spacing: 4px;
      font-size: 14px;
      margin-bottom: 20px;
    }

    h1 {
      font-size: clamp(45px, 8vw, 90px);
      line-height: 1;
      background: linear-gradient(90deg, #fff, #00ffff, #9b5cff);
      -webkit-background-clip: text;
      color: transparent;
      margin-bottom: 25px;
    }

    .subtitle {
      font-size: 22px;
      color: #aaa;
      max-width: 700px;
      line-height: 1.6;
    }

    .buttons {
      margin-top: 35px;
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 14px 25px;
      border-radius: 30px;
      text-decoration: none;
      color: white;
      border: 1px solid rgba(0,255,255,.5);
      background: rgba(0,255,255,.08);
      backdrop-filter: blur(10px);
      transition: .3s;
    }

    .btn:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 30px rgba(0,255,255,.4);
      background: rgba(0,255,255,.18);
    }

    .section {
      padding: 70px 0;
    }

    .section h2 {
      font-size: 40px;
      margin-bottom: 35px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 20px;
    }

    .card {
      padding: 30px;
      min-height: 180px;
      border-radius: 20px;
      background: rgba(255,255,255,.05);
      border: 1px solid rgba(255,255,255,.1);
      backdrop-filter: blur(15px);
      transition: .4s;
      transform-style: preserve-3d;
    }

    .card:hover {
      transform: perspective(800px) rotateX(8deg) rotateY(-8deg) translateY(-8px);
      border-color: rgba(0,255,255,.5);
      box-shadow: 0 20px 50px rgba(0,0,0,.5);
    }

    .card h3 {
      color: #00ffff;
      margin-bottom: 15px;
      font-size: 22px;
    }

    .card p {
      color: #aaa;
      line-height: 1.6;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .skill {
      padding: 12px 20px;
      border-radius: 25px;
      background: rgba(155,92,255,.12);
      border: 1px solid rgba(155,92,255,.4);
      transition: .3s;
    }

    .skill:hover {
      transform: scale(1.08);
      box-shadow: 0 0 20px rgba(155,92,255,.4);
    }

    footer {
      text-align: center;
      padding: 50px 0;
      color: #666;
    }
  </style>
</head>

<body>

  <div class="background">
    <div class="cube"></div>
    <div class="cube"></div>
  </div>

  <main class="container">

    <section class="hero">

      <div class="tag">HELLO, WORLD! 👋</div>

      <h1>I'm Varalakshmi</h1>

      <p class="subtitle">
        🤖 AI/ML Enthusiast · 💻 Developer · 🚀 Builder ·
        Full-Stack Explorer
      </p>

      <p class="subtitle">
        Building AI-powered solutions for real-world problems,
        exploring Computer Vision, OpenCV and modern web technologies.
      </p>

      <div class="buttons">
        <a class="btn" href="https://github.com/Varalakshmi74">
          GitHub ↗
        </a>

        <a class="btn" href="#">
          Projects ↗
        </a>
      </div>

    </section>


    <section class="section">

      <h2>⚡ What I Do</h2>

      <div class="cards">

        <div class="card">
          <h3>🤖 AI / ML</h3>
          <p>
            Building intelligent solutions using Machine Learning
            and Artificial Intelligence.
          </p>
        </div>

        <div class="card">
          <h3>👁️ Computer Vision</h3>
          <p>
            Exploring OpenCV, image processing and
            vision-based applications.
          </p>
        </div>

        <div class="card">
          <h3>🌐 Full Stack</h3>
          <p>
            Creating modern web applications and connecting
            ML models with web technologies.
          </p>
        </div>

        <div class="card">
          <h3>🚀 Projects</h3>
          <p>
            Turning ideas into practical projects and
            real-world applications.
          </p>
        </div>

      </div>

    </section>


    <section class="section">

      <h2>🧠 Tech Stack</h2>

      <div class="skills">

        <span class="skill">Python</span>
        <span class="skill">C++</span>
        <span class="skill">HTML</span>
        <span class="skill">CSS</span>
        <span class="skill">JavaScript</span>
        <span class="skill">Machine Learning</span>
        <span class="skill">OpenCV</span>
        <span class="skill">Git</span>
        <span class="skill">GitHub</span>

      </div>

    </section>

    <footer>
      © 2026 Varalakshmi · Built with 💜 & code
    </footer>

  </main>

</body>
</html>
