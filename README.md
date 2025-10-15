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

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body, html {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background: #f4f4f4;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
  padding: 20px 0;
}

header {
  background: #222;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  float: left;
  margin-left: 20px;
}

nav {
  float: right;
  margin-right: 20px;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline;
  margin-left: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
}

#hero {
  background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

#hero h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.btn {
  display: inline-block;
  background: #ff6600;
  color: #fff;
  padding: 10px 20px;
  margin-top: 15px;
  text-decoration: none;
  border-radius: 5px;
}

.services-list {
  list-style: none;
  padding: 0;
}

.services-list li {
  margin-bottom: 10px;
  font-size: 1.2rem;
}

.projects {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.project {
  flex: 1;
  min-width: 300px;
  background: white;
  padding: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.project img {
  max-width: 100%;
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
  border: 1px solid #ccc;
}

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 10px;
  margin-top: 40px;
}
