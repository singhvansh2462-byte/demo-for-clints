<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Vansh | Portfolio</title>
  <style>
    body {
      background: #0f0f0f;
      color: #fff;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      scroll-behavior: smooth;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background: #111;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      margin: 0;
      padding: 0;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .hire-btn {
      background: #00f;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      color: #fff;
      font-weight: bold;
    }
    section {
      min-height: 100vh;
      padding: 120px 50px 50px;
    }
    h1, h2 {
      background: linear-gradient(90deg, #00f, #f0f);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .card-3d {
      background: #222;
      padding: 20px;
      margin: 20px;
      border-radius: 10px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.5);
      transition: transform 0.3s ease;
      display: inline-block;
      width: 250px;
    }
    .card-3d:hover {
      transform: perspective(1000px) rotateY(10deg) scale(1.05);
    }
    .btn-3d {
      padding: 10px 20px;
      background: #00f;
      color: #fff;
      border: none;
      border-radius: 5px;
      transition: transform 0.3s ease;
      cursor: pointer;
    }
    .btn-3d:hover {
      transform: perspective(500px) translateZ(20px);
    }
    form input, form textarea {
      width: 300px;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: none;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#portfolio">Portfolio</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="#pricing">Pricing</a></li>
    </ul>
    <a href="#contact" class="hire-btn">Hire Me</a>
  </nav>

  <!-- Home -->
  <section id="home">
    <h1>DIGITAL CRAFTSMANSHIP</h1>
    <p>Designing Premium Websites That Speak Your Brand.</p>
    <p>I’m Vansh, only 15, a creative web designer from India...</p>
    <button class="btn-3d">Get Started</button>
  </section>

  <!-- Portfolio -->
  <section id="portfolio">
    <h2>My Work</h2>
    <div class="card-3d">
      <h3>Business Website</h3>
      <p>Modern UI overhaul focusing on conversion...</p>
    </div>
    <div class="card-3d">
      <h3>Digital Storefront</h3>
      <p>Responsive retail experience designed for seamless shopping.</p>
    </div>
  </section>

  <!-- Services -->
  <section id="services">
    <h2>Services I Offer</h2>
    <div class="card-3d">UI/UX Design</div>
    <div class="card-3d">Branding & Identity</div>
    <div class="card-3d">Web Design & Development</div>
  </section>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <p>Freelance web designer specializing in premium website design and branding. Skilled in HTML, CSS, JavaScript, Figma, Adobe XD, Photoshop.</p>
    <div class="card-3d">HTML/CSS</div>
    <div class="card-3d">JavaScript</div>
    <div class="card-3d">Figma</div>
    <div class="card-3d">Adobe XD</div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Let’s Connect</h2>
    <form>
      <input type="text" placeholder="Name"><br>
      <input type="email" placeholder="Email"><br>
      <textarea placeholder="Message"></textarea><br>
      <button class="btn-3d">Send Message</button>
    </form>
    <p>Instagram: vanshcodes.x</p>
    <p>Email: anubhavv8777@gmail.com</p>
    <p>Phone: +91 9456853697</p>
  </section>

  <!-- Pricing -->
  <section id="pricing">
    <h2>Choose Your Plan</h2>
    <div class="card-3d">Basic Website ₹5,000 – ₹10,000</div>
    <div class="card-3d">Standard Website ₹12,000 – ₹25,000</div>
    <div class="card-3d">Advanced Website ₹30,000 – ₹70,000+</div>
    <div class="card-3d">E-commerce ₹40,000 – ₹1,50,000+</div>
  </section>

  <script>
    document.querySelectorAll('.card-3d').forEach(card => {
      card.addEventListener('mousemove', e => {
        const rect = card.getBoundingClientRect();
        const x = e.clientX - rect.left;
        const y = e.clientY - rect.top;
        card.style.transform =
          `perspective(1000px) rotateY(${(x/rect.width - 0.5)*20}deg) rotateX(${(y/rect.height - 0.5)*-20}deg)`;
      });
      card.addEventListener('mouseleave', () => {
        card.style.transform = 'perspective(1000px) rotateY(0deg) rotateX(0deg)';
      });
    });
  </script>

</body>
</html>
