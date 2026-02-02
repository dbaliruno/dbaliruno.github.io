# dbaliruno.github.io
/yourusername.github.io │── index.html │── style.css │── script.js │── /images │     └── pen-logo.png
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PEN – Empowering People, Transforming Communities</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

<!-- NAV -->
<header class="nav">
  <img src="images/pen-logo.png" alt="PEN Logo" class="logo">
  <nav>
    <a href="#about">About</a>
    <a href="#programs">Programs</a>
    <a href="#book">Book</a>
    <a href="#contact">Contact</a>
    <a href="#donate" class="btn">Donate</a>
  </nav>
</header>

<!-- HERO -->
<section class="hero">
  <h1>Empowering People.<br>Transforming Communities.</h1>
  <p>Personal Empowerment Network (PEN) equips youth, churches, prisons, and communities with character, skills, and purpose.</p>
  <a href="#programs" class="btn">Our Work</a>
</section>

<!-- ABOUT -->
<section id="about">
  <h2>Who We Are</h2>
  <p>
    PEN is a values-driven NGO committed to raising ethical leaders, resilient entrepreneurs,
    and transformed communities across Uganda and beyond.
  </p>
</section>

<!-- PROGRAMS -->
<section id="programs" class="cards">
  <h2>Our Programs</h2>

  <div class="card">
    <h3>Youth Empowerment</h3>
    <p>Schools, universities, and youth conferences.</p>
  </div>

  <div class="card">
    <h3>Prison Outreach</h3>
    <p>Character transformation and reintegration programs.</p>
  </div>

  <div class="card">
    <h3>Church & Community Training</h3>
    <p>Leadership, stewardship, and cooperative development.</p>
  </div>
</section>

<!-- BOOK / PORTFOLIO -->
<section id="book" class="highlight">
  <h2>Featured Book</h2>
  <h3>From Hunter to Harvester</h3>
  <p>
    A powerful guide on character, purpose, and building a future bigger than your paycheck.
  </p>
  <a href="#" class="btn">Download / Buy Book</a>
</section>

<!-- CONTACT FORM -->
<section id="contact">
  <h2>Contact Us</h2>

  <form action="https://formspree.io/f/yourformid" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" placeholder="Your Message" required></textarea>
    <button type="submit" class="btn">Send Message</button>
  </form>
</section>

<!-- DONATE -->
<section id="donate" class="highlight">
  <h2>Support Our Mission</h2>
  <p>Your support helps transform lives.</p>
  <a href="https://www.paypal.me/yourlink" class="btn">Donate via PayPal</a>
  <a href="https://wa.me/256700000000" class="btn whatsapp">Donate via WhatsApp</a>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 Personal Empowerment Network (PEN)</p>
</footer>

<!-- WHATSAPP FLOAT -->
<a href="https://wa.me/256700000000" class="whatsapp-float">
  💬
</a>

<script src="script.js"></script>
</body>
</html>
