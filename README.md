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

    /* Animated Gradient Text for Headings */
    h1, h2, h3 {
      background: linear-gradient(270deg, #001f4d, #004080, #00aaff, #001f4d);
      background-size: 600% 600%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: textFlow 8s linear infinite;
    }
    @keyframes textFlow {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
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

    /* Card Styling with Animated Gradient Border */
    .card {
      background: #000;
      border: 3px solid transparent;
      border-radius: 12px;
      padding: 20px;
      margin: 20px;
      display: inline-block;
      width: 250px;
      transition: transform 0.5s, box-shadow 0.5s;
      position: relative;
      overflow: hidden;
    }
    .card::before {
      content: "";
      position: absolute;
      top: -3px;
      left: -3px;
      right: -3px;
      bottom: -3px;
      border-radius: 12px;
      background: linear-gradient(270deg, #001f4d, #004080, #00aaff, #001f4d);
      background-size: 600% 600%;
      animation: borderFlow 8s linear infinite;
      z-index: -1;
    }
    @keyframes borderFlow {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 30px rgba(0, 170, 255, 0.6);
    }
    .card h3, .card p {
      position: relative;
      z-index: 1;
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
    <a href="#pricing">Pricing</a>
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
    <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:20px;">
      <div class="card">
        <img src="IMAGE1.jpg" alt="Contact Page Design" style="width:100%;border-radius:8px;">
        <h3>Contact Page</h3>
        <p>Modern layout with form, FAQ & map.</p>
      </div>
      <div class="card">
        <img src="IMAGE2.jpg" alt="Agency Branding Layout" style="width:100%;border-radius:8px;">
        <h3>Branding Agency</h3>
        <p>Dark theme, neon accents, portfolio showcase.</p>
      </div>
      <div class="card">
        <img src="IMAGE3.jpg" alt="Travel Website Layout" style="width:100%;border-radius:8px;">
        <h3>Travel Website</h3>
        <p>Tour packages, gallery & inspiration section.</p>
      </div>
    </div>
  </section>

  <section id="pricing">
    <h2>Price List</h2>
    <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:20px;">
      <div class="card">
        <h3>Basic Package</h3>
        <p>1‑Page Website</p>
        <p><strong>₹2,999</strong></p>
      </div>
      <div class="card">
        <h3>Standard Package</h3>
        <p>Multi‑Page + Animations</p>
        <p><strong>₹6,999</strong></p>
      </div>
      <div class="card">
        <h3>Premium Package</h3>
        <p>Custom Design + Branding + SEO</p>
        <p><strong>₹14,999</strong></p>
      </div>
    </div>
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
    ScrollReveal().reveal('h1, h2, h3, p, .card, .btn', {
      duration: 1200,
      distance: '50px',
      origin: 'bottom',
      easing: 'ease-in-out',
      reset: true
    });
  </script>
</body>
</html>
