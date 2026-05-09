<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VanshCodes Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(180deg, #000000, #0a0f2c);
      color: #f0f0f0;
      overflow-x: hidden;
    }

    nav {
      position: sticky;
      top: 0;
      background: rgba(0,0,0,0.9);
      padding: 15px;
      text-align: center;
      backdrop-filter: blur(5px);
      z-index: 1000;
    }
    nav a {
      color: #00aaff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s, text-shadow 0.3s;
    }
    nav a:hover {
      color: #ffaa00;
      text-shadow: 0 0 10px #ffaa00;
    }

    section {
      padding: 100px 20px;
      text-align: center;
      position: relative;
    }
    h1, h2 {
      color: #00aaff;
    }

    #home {
      background: url('https://picsum.photos/1920/1080?blur') no-repeat center center/cover;
      color: #fff;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background-attachment: fixed;
    }
    #home h1 {
      font-size: 3em;
      text-shadow: 0 0 20px #00aaff;
    }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      background: #00aaff;
      color: #000;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: transform 0.3s, background 0.3s;
    }
    .btn:hover {
      background: #ffaa00;
      transform: scale(1.1) rotate(2deg);
    }

    .card {
      background: #0a0f2c;
      border: 1px solid #00aaff;
      border-radius: 10px;
      padding: 20px;
      margin: 20px;
      display: inline-block;
      width: 250px;
      transition: transform 0.5s, box-shadow 0.5s;
      perspective: 1000px;
    }
    .card:hover {
      transform: rotateY(10deg) scale(1.05);
      box-shadow: 0 20px 40px rgba(0,0,0,0.7);
      border-color: #ffaa00;
    }

    footer {
      background: #000;
      padding: 20px;
      text-align: center;
      color: #888;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h1>Need a Professional Website?</h1>
    <p>Here’s the Solution 🚀</p>
    <a href="#contact" class="btn">Get Started</a>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m Vansh, only 15, passionate web designer from India.</p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="card">
      <h3>Business Websites</h3>
      <p>Premium UI/UX for your brand.</p>
    </div>
    <div class="card">
      <h3>Portfolio Sites</h3>
      <p>Showcase your work in style.</p>
    </div>
    <div class="card">
      <h3>E‑Commerce</h3>
      <p>Sell online with confidence.</p>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>Coming Soon...</p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: anubhavv8777@gmail.com</p>
    <p>Phone: +91 9456853697</p>
    <p>Instagram: @vanshcodes.x</p>
  </section>

  <footer>
    <p>© 2026 VanshCodes | All Rights Reserved</p>
  </footer>

  <!-- ScrollReveal Script -->
  <script src="https://unpkg.com/scrollreveal"></script>
  <script>
    ScrollReveal().reveal('h1, h2, p, .card, .btn', {
      duration: 1200,
      distance: '50px',
      origin: 'bottom',
      easing: 'ease-in-out',
      reset: true
    });
  </script>
</body>
</html>
