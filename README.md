# VR-WORLD-SITE<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SibusisoseHlanhla VR World</title>
  <link rel="stylesheet" href="styles.css" />
  <style>
    body { margin: 0; font-family: 'Segoe UI', sans-serif; background-color: #0a0a0a; color: white; }
    header, footer { background: #000e1a; padding: 1em; text-align: center; }
    nav a { margin: 0 1em; color: #00bfff; text-decoration: none; font-weight: bold; }
    nav a:hover { color: #0ff; }
    .hero { background: url('vr-hero.jpg') center/cover no-repeat; padding: 5em 1em; text-align: center; }
    .hero h1 { font-size: 3em; color: #00bfff; text-shadow: 0 0 10px #0ff; }
    .section { padding: 3em 1em; max-width: 1000px; margin: auto; }
    .booking-form input, .booking-form select, .booking-form textarea { display: block; width: 100%; margin: 0.5em 0; padding: 0.8em; border-radius: 5px; border: none; }
    .booking-form button { padding: 0.8em 2em; background: #00bfff; border: none; color: #fff; font-weight: bold; cursor: pointer; }
    .booking-form button:hover { background: #009acd; }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="VR World Logo" style="height: 80px;">
    <h2>"Escaping to Virtual Reality is not a game."</h2>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#booking">Booking</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Welcome to SibusisoseHlanhla VR World</h1>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>Located in Ennerdale, Johannesburg, our 750sqm facility offers cutting-edge virtual reality experiences for all ages. With 8 fully equipped VR stations, snacks, board games, and event hosting, SibusisoseHlanhla VR World is your gateway to another dimension.</p>
  </section>

  <section id="services" class="section">
    <h2>Our Services</h2>
    <ul>
      <li>VR Station Gaming</li>
      <li>Party & Event Hosting</li>
      <li>Snack Bar</li>
      <li>Board Games Area</li>
      <li>Private Bookings & Team Building</li>
    </ul>
    <h3>Pricing</h3>
    <p>R80 - R150 per session. Event packages available on request.</p>
  </section>

  <section id="booking" class="section">
    <h2>Book Your Experience</h2>
    <form class="booking-form">
      <input type="text" placeholder="Full Name" required />
      <input type="email" placeholder="Email Address" required />
      <input type="tel" placeholder="Phone Number" required />
      <select required>
        <option value="">Select Service</option>
        <option value="vr-session">VR Station Session</option>
        <option value="event">Event Booking</option>
      </select>
      <input type="date" required />
      <textarea placeholder="Any special requests..."></textarea>
      <button type="submit">Submit Booking</button>
    </form>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> 5584/15 Zeolite Street, Ennerdale Ext 8, Johannesburg, Gauteng</p>
    <p><strong>Email:</strong> info@vrworld.co.za</p>
    <p><strong>Phone:</strong> +27 73 456 7890</p>
    <p><strong>Facebook:</strong> <a href="#" style="color: #0ff">@VRWorldEnnerdale</a></p>
  </section>

  <footer>
    <p>&copy; 2025 SibusisoseHlanhla VR World. All rights reserved.</p>
  </footer>
</body>
</html>
