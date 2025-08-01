# Electronic-Accessories-1
Discover top-quality electronic accessories designed to enhance your tech experience. From durable charging cables and fast adapters to stylish cases and smart gadgets, our collection combines reliability with cutting-edge design. Shop now for unbeatable prices and elevate your devices today!
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ElectroEssentials</title>
  <style>
    :root {
      --primary: #1e293b;
      --secondary: #3b82f6;
      --accent: #facc15;
      --bg: #f1f5f9;
      --text: #1f2937;
      --card-bg: #ffffff;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background-color: var(--primary);
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: var(--secondary);
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s ease;
    }

    nav a:hover {
      color: var(--accent);
    }

    .hero {
      background-color: white;
      text-align: center;
      padding: 60px 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }

    .hero h1 {
      font-size: 2.5em;
      color: var(--primary);
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2em;
      color: #555;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      padding: 60px 40px;
    }

    .product {
      background-color: var(--card-bg);
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
      padding: 20px;
      transition: transform 0.2s ease;
      text-align: center;
    }

    .product:hover {
      transform: translateY(-5px);
    }

    .product img {
      width: 100%;
      height: 160px;
      object-fit: contain;
      margin-bottom: 15px;
    }

    .product h3 {
      margin-bottom: 8px;
      color: var(--primary);
    }

    .product p {
      font-size: 0.95em;
      color: #666;
    }

    footer {
      background-color: var(--primary);
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2em;
      }
      .products {
        padding: 40px 20px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>ElectroEssentials</h1>
    <p>High-performance accessories for your digital lifestyle.</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    <h1>Power Your Tech</h1>
    <p>Premium cables, chargers, and accessories — built to last, priced to win.</p>
  </section>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/250x160?text=USB-C+Charger" alt="Charger">
      <h3>USB-C Fast Charger</h3>
      <p>Charge your devices in half the time with this 20W compact adapter.</p>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/250x160?text=Braided+Cable" alt="Cable">
      <h3>Durable Braided Cable</h3>
      <p>Tough, tangle-free 1.5m cable compatible with all USB-C devices.</p>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/250x160?text=Phone+Case" alt="Phone Case">
      <h3>Shockproof Case</h3>
      <p>Stylish impact-resistant case with matte finish for all popular phones.</p>
    </div>
  </section>

  <footer>
    &copy; 2025 ElectroEssentials. Built with 💡 by your favourite electronics hustler.
  </footer>

</body>
</html>
