<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Let’s Talk About It | Faith-Based Counseling & Therapy</title>
  <meta name="description" content="Faith-based counseling, single and couple therapy, and spiritual support in a safe, confidential space.">

  <style>
    :root {
      --burgundy:#800020;
      --black:#000;
      --white:#fff;
      --light:#f6f6f6;
    }

    * {
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background:var(--white);
      color:var(--black);
      line-height:1.6;
      scroll-behavior:smooth;
    }

    /* NAVBAR */
    header {
      position:sticky;
      top:0;
      background:var(--white);
      border-bottom:2px solid var(--burgundy);
      z-index:1000;
    }

    .navbar {
      max-width:1200px;
      margin:auto;
      padding:1rem;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    .logo {
      color:var(--burgundy);
      font-weight:bold;
      font-size:1.2rem;
      animation:fadeIn 1s ease-in-out;
    }

    .nav-links {
      list-style:none;
      display:flex;
    }

    .nav-links li {
      margin-left:20px;
    }

    .nav-links a {
      text-decoration:none;
      color:var(--black);
      font-weight:500;
      position:relative;
    }

    .nav-links a::after {
      content:"";
      position:absolute;
      width:0;
      height:2px;
      background:var(--burgundy);
      bottom:-5px;
      left:0;
      transition:.3s;
    }

    .nav-links a:hover::after {
      width:100%;
    }

    .menu-toggle {
      display:none;
      font-size:1.5rem;
      cursor:pointer;
    }

    /* HERO */
    .hero {
      height:90vh;
      background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
      url("https://images.unsplash.com/photo-1506126613408-eca07ce68773") center/cover;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      color:var(--white);
      padding:2rem;
    }

    .hero h1 {
      font-size:2.6rem;
      margin-bottom:1rem;
      animation:slideUp 1.2s ease;
    }

    .hero p {
      animation:fadeIn 2s ease;
    }

    .btn {
      display:inline-block;
      background:var(--burgundy);
      color:var(--white);
      padding:.8rem 1.6rem;
      margin-top:1.5rem;
      text-decoration:none;
      border-radius:4px;
      transition:.3s;
    }

    .btn:hover {
      transform:translateY(-3px);
      opacity:.9;
    }

    /* SECTIONS */
    section {
      max-width:1200px;
      margin:auto;
      padding:4rem 2rem;
      animation:fadeIn 1.2s ease;
    }

    h2 {
      text-align:center;
      color:var(--burgundy);
      margin-bottom:2rem;
    }

    /* SERVICES */
    .cards {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:1.5rem;
    }

    .card {
      background:var(--light);
      padding:2rem;
      border-radius:6px;
      transition:.3s;
    }

    .card:hover {
      transform:translateY(-5px);
    }

    /* CONTACT */
    .contact-info {
      text-align:center;
      line-height:2;
    }

    .contact-info a {
      color:var(--burgundy);
      text-decoration:none;
      font-weight:bold;
    }

    /* WHATSAPP */
    .whatsapp {
      position:fixed;
      bottom:20px;
      right:20px;
      background:#25d366;
      color:#fff;
      padding:15px;
      border-radius:50%;
      font-size:22px;
      text-decoration:none;
      z-index:2000;
      animation:pulse 2s infinite;
    }

    /* FOOTER */
    footer {
      background:var(--black);
      color:var(--white);
      text-align:center;
      padding:1.5rem;
    }

    /* ANIMATIONS */
    @keyframes fadeIn {
      from {opacity:0;}
      to {opacity:1;}
    }

    @keyframes slideUp {
      from {transform:translateY(40px); opacity:0;}
      to {transform:translateY(0); opacity:1;}
    }

    @keyframes pulse {
      0% {transform:scale(1);}
      50% {transform:scale(1.1);}
      100% {transform:scale(1);}
    }

    /* MOBILE */
    @media(max-width:768px){
      .nav-links {
        display:none;
        flex-direction:column;
        position:absolute;
        background:var(--white);
        top:60px;
        right:20px;
        padding:1rem;
        border:1px solid #ddd;
      }

      .nav-links.active {
        display:flex;
      }

      .menu-toggle {
        display:block;
      }
    }
  </style>
</head>

<body>

<header>
  <nav class="navbar">
    <div class="logo">Let’s Talk About It</div>
    <ul class="nav-links" id="navLinks">
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <div class="menu-toggle" id="menuToggle">&#9776;</div>
  </nav>
</header>

<section class="hero" id="home">
  <div>
    <h1>A Safe Space for Healing, Hope & Restoration</h1>
    <p>Faith-based counseling and therapy rooted in compassion, wisdom, and confidentiality.</p>
    <a href="#contact" class="btn">Get in Touch</a>
  </div>
</section>

<section id="about">
  <h2>About Us</h2>
  <p><strong>Let’s Talk About It</strong> provides professional counseling, therapy, and spiritual support for individuals and couples navigating emotional, relational, and spiritual challenges.</p>
  <p>We blend evidence-based counseling with faith-sensitive care, addressing the heart, mind, and spirit in a safe and respectful environment.</p>
</section>

<section id="services">
  <h2>Our Services</h2>
  <div class="cards">
    <div class="card">
      <h3>Counseling</h3>
      <p>One-on-one faith-sensitive counseling for emotional healing, clarity, and personal growth.</p>
    </div>
    <div class="card">
      <h3>Single & Couple Therapy</h3>
      <p>Therapeutic support for communication, trust-building, conflict resolution, and restored relationships.</p>
    </div>
    <div class="card">
      <h3>Spiritual Services</h3>
      <p>Faith-based guidance and prayerful support for purpose, direction, and inner peace.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <div class="contact-info">
    <p><strong>Call / WhatsApp:</strong> <a href="tel:08060013957">08060013957</a></p>
    <p><strong>WhatsApp Chat:</strong> <a href="https://wa.me/2348060013957" target="_blank">Start Chat</a></p>
    <p><strong>Instagram:</strong> <a href="https://instagram.com/aj.ero.gratton" target="_blank">@aj.ero.gratton</a></p>
  </div>
</section>

<footer>
  <p>&copy; 2025 Let’s Talk About It. All Rights Reserved.</p>
</footer>

<a href="https://wa.me/2348060013957" class="whatsapp" target="_blank">💬</a>

<script>
  const menuToggle=document.getElementById("menuToggle");
  const navLinks=document.getElementById("navLinks");
  menuToggle.addEventListener("click",()=>navLinks.classList.toggle("active"));
</script>

</body>
</html>
