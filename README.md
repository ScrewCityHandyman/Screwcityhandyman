<img width="1024" height="1024" alt="logo png" src="https://github.com/user-attachments/assets/b3e404e9-c581-4bac-9260-decf91df6509" />
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Screw City Handyman Services</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #0d0d0d;
      color: #f5f5f5;
    }
    header {
      background: #111;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      border-bottom: 1px solid #222;
    }
    header img {
      height: 60px;
    }
    nav a {
      margin: 0 15px;
      color: #f5f5f5;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }
    nav a:hover {
      color: #00aaff;
    }
    .hero {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(to bottom, #111, #1a1a1a);
    }
    .hero img {
      width: 160px;
      margin-bottom: 20px;
    }
    .hero h1 {
      font-size: 42px;
      margin: 10px 0;
      color: #00aaff;
    }
    .hero p {
      font-size: 18px;
      margin-bottom: 25px;
    }
    .btn {
      padding: 14px 28px;
      background: #00aaff;
      color: #fff;
      text-decoration: none;
      border-radius: 6px;
      font-weight: 600;
      transition: 0.3s;
    }
    .btn:hover {
      background: #0088cc;
    }
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 40px;
      color: #00aaff;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }
    .card {
      background: #1a1a1a;
      padding: 25px;
      border-radius: 10px;
      text-align: center;
      transition: 0.3s;
    }
    .card:hover {
      background: #222;
      transform: translateY(-5px);
    }
    .card h3 {
      margin: 15px 0;
      color: #00aaff;
    }
    .contact form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: auto;
    }
    .contact input, .contact textarea {
      padding: 12px;
      border-radius: 6px;
      border: none;
      font-size: 16px;
    }
    .contact button {
      padding: 14px;
      background: #00aaff;
      color: #fff;
      border: none;
      border-radius: 6px;
      font-weight: 600;
      cursor: pointer;
    }
    .contact button:hover {
      background: #0088cc;
    }
    footer {
      background: #111;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      border-top: 1px solid #222;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Screw City Handyman Logo">
    <nav>
      <a href="#">Home</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#specials">Specials</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <img src="logo.png" alt="Screw City Handyman">
    <h1>Screw City Handyman Services</h1>
    <p>Reliable • Affordable • Available 24/7</p>
    <a href="#contact" class="btn">Book Now</a>
  </div>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card"><h3>General Repairs</h3></div>
      <div class="card"><h3>Drywall & Painting</h3></div>
      <div class="card"><h3>Plumbing & Electrical</h3></div>
      <div class="card"><h3>Furniture Assembly</h3></div>
      <div class="card"><h3>Appliance Installation</h3></div>
      <div class="card"><h3>Home Maintenance</h3></div>
      <div class="card"><h3>Honey-Do Lists & More</h3></div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p style="text-align:center; max-width:800px; margin:auto;">
      At Screw City Handyman Services, we pride ourselves on providing top-quality, affordable home repairs and maintenance.
      Serving Northern Illinois & Southern Wisconsin, we’re available 24/7 for all your repair needs.
    </p>
  </section>

  <section id="specials">
    <h2>Special Offers</h2>
    <p style="text-align:center; font-size:18px;">
      🎉 Opening Deal: <strong>50% off labor costs for the first month!</strong>
    </p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p style="text-align:center;">📞 Call/Text: <a href="tel:8153295371" style="color:#00aaff;">815-329-5371</a> | 
       📧 Email: <a href="mailto:ScrewCityRepairs@gmail.com" style="color:#00aaff;">ScrewCityRepairs@gmail.com</a></p>
    <form>
      <input type="text" placeholder="Your Name">
      <input type="email" placeholder="Your Email">
      <textarea rows="5" placeholder="How can we help?"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    © 2025 Screw City Handyman Services – Serving Northern Illinois & Southern Wisconsin
  </footer>
</body>
</html>
