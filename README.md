<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Saifee Electricals</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #0d1b2a; color: #fff; }
    header { background: #1b263b; padding: 20px; display: flex; justify-content: space-between; align-items: center; }
    header img { height: 50px; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; }
    .hero { text-align: center; padding: 50px 20px; background: #1b263b; }
    .hero h1 { font-size: 2em; margin-bottom: 10px; }
    .hero p { font-size: 1.2em; }
    .btn { background: #e76f51; color: #fff; padding: 10px 20px; text-decoration: none; border-radius: 5px; display: inline-block; margin-top: 20px; }
    .products, .services { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding: 40px 20px; background: #0d1b2a; }
    .card { background: #1b263b; padding: 20px; border-radius: 10px; width: 200px; text-align: center; }
    footer { background: #1b263b; padding: 20px; text-align: center; }
    a { color: #f4a261; }
  </style>
</head>
<body>
  <header>
    <img src="/logo.png" alt="Saifee Electricals Logo">
    <nav>
      <a href="#products">Products</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Your One-Stop Electrical Store</h1>
    <p>LEDs, Fans, Cables, Switches & Accessories. Sales and Service.</p>
    <a href="#products" class="btn">View Products</a>
  </section>

  <section id="products" class="products">
    <div class="card">LED Bulbs & Tube Lights</div>
    <div class="card">Ceiling & Exhaust Fans</div>
    <div class="card">Wires, Cables & Switches</div>
    <div class="card">HDMI, 3RC Cables & Accessories</div>
    <div class="card">Switch Boards, Plugs, Multi-Plugs</div>
  </section>

  <section id="services" class="services">
    <div class="card">House Electrical Repair Work</div>
    <div class="card">New Wiring (Single & Three Phase)</div>
    <div class="card">Industrial Wiring & Maintenance</div>
    <div class="card">Short Circuit / Fault Finding</div>
  </section>

  <footer id="contact">
    <h3>Contact Us</h3>
    <p><strong>Saifee Electricals</strong><br>
    719, Near Gandhi ni Pole, Opp. Kabir Ashram,<br>
    Saraspur, Ahmedabad – 380018</p>
    <p><a href="https://maps.app.goo.gl/PJWwefq63iPPzp2s7" target="_blank">View on Google Maps</a></p>
    <p>Call / WhatsApp: <a href="https://wa.me/919824935598">9824935598</a></p>
  </footer>
</body>
</html>
