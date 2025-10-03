<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Screw City Handyman Services</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #eee;
    }
    header {
      background: #000;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 24px;
      color: #ff9900;
    }
    nav a {
      margin: 0 10px;
      color: #eee;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #ff9900;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: #222;
    }
    .hero h2 {
      font-size: 36px;
      margin-bottom: 20px;
      color: #ff9900;
    }
    .btn {
      display: inline-block;
      padding: 12px 25px;
      background: #ff9900;
      color: #000;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h3 {
      color: #ff9900;
      margin-bottom: 15px;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Screw City Handyman</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Services</a>
      <a href="#">About</a>
      <a href="#">Specials</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Your Local Handyman – Reliable & Affordable</h2>
    <p>Serving Northern Illinois & Southern Wisconsin</p>
    <a href="#contact" class="btn">Book Now</a>
  </div>

  <section id="services">
    <h3>Our Services</h3>
    <ul>
      <li>✔ General Repairs</li>
      <li>✔ Drywall & Painting</li>
      <li>✔ Plumbing & Electrical Fixes</li>
      <li>✔ Furniture Assembly</li>
      <li>✔ Appliance Installation</li>
      <li>✔ Home Maintenance</li>
      <li>✔ Honey-Do Lists & More</li>
    </ul>
  </section>

  <section id="about">
    <h3>About Us</h3>
    <p>At Screw City Handyman Services, we take pride in providing reliable, affordable, and top-quality repairs. From small fixes to larger projects, we’re here to make your home run smoothly 24/7.</p>
  </section>

  <section id="specials">
    <h3>Special Offers</h3>
    <p>🎉 Opening Special: <strong>50% off labor costs for the first month!</strong></p>
  </section>

  <section id="contact">
    <h3>Contact Us</h3>
    <p>📞 Call/Text: <a href="tel:8153295371">815-329-5371</a></p>
    <p>📧 Email: <a href="mailto:ScrewCityRepairs@gmail.com">ScrewCityRepairs@gmail.com</a></p>
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>
      <label for="message">Message:</label><br>
      <textarea id="message" name="message"></textarea><br><br>
      <button type="submit" class="btn">Send</button>
    </form>
  </section>

  <footer>
    © 2025 Screw City Handyman Services – Serving Northern Illinois & Southern Wisconsin
  </footer>
</body>
</html>
