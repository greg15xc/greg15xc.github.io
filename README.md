<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sweet Spot Construction</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Sweet Spot Construction</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="hero">
    <div class="container">
      <h2>Building the Future, One Project at a Time</h2>
      <p>Reliable. Professional. High-Quality Construction Services.</p>
      <a href="#contact" class="btn">Get a Quote</a>
    </div>
  </section>

  <section id="about" class="container">
    <h2>About Us</h2>
    <p>Sweet Spot Construction is a full-service construction company committed to building exceptional commercial and residential spaces. We bring expertise, transparency, and reliability to every project.</p>
  </section>

  <section id="services" class="container">
    <h2>Our Services</h2>
    <ul class="services-list">
      <li>🏗️ New Construction</li>
      <li>🛠️ Renovations & Remodeling</li>
      <li>📐 Design & Build</li>
      <li>🌆 Commercial Projects</li>
      <li>🏡 Residential Projects</li>
    </ul>
  </section>

  <section id="projects" class="container">
    <h2>Recent Projects</h2>
    <div class="projects">
      <div class="project">
        <img src="https://via.placeholder.com/300x200" alt="Project 1" />
        <h3>Modern Home Build</h3>
      </div>
      <div class="project">
        <img src="https://via.placeholder.com/300x200" alt="Project 2" />
        <h3>Downtown Office Renovation</h3>
      </div>
    </div>
  </section>

  <section id="contact" class="container">
    <h2>Contact Us</h2>
    <form action="mailto:your@email.com" method="POST" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Sweet Spot Construction. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
