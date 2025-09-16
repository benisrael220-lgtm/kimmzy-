# kimmzy-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kimzyy - Fresh Eggs Delivery</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f8f8f8; color: #333; }
    header { background: #ffcc00; padding: 20px; text-align: center; font-size: 24px; font-weight: bold; }
    nav { background: #333; padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    .container { width: 90%; max-width: 1000px; margin: auto; padding: 20px; }
    .section { margin: 40px 0; }
    .products, .gallery, .testimonials { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: white; border-radius: 10px; padding: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
    img { max-width: 100%; border-radius: 8px; }
    button { background: #ffcc00; border: none; padding: 10px 20px; margin-top: 10px; cursor: pointer; font-weight: bold; border-radius: 5px; }
    footer { background: #333; color: white; text-align: center; padding: 15px; margin-top: 40px; }
  </style>
</head>
<body>
  <header>🥚 Kimzyy Fresh Eggs Delivery</header>

  <nav>
    <a href="#products">Products</a>
    <a href="#gallery">Gallery</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#order">Order Now</a>
  </nav>

  <div class="container">
    <!-- Products Section -->
    <section id="products" class="section">
      <h2>Our Products</h2>
      <div class="products">
        <div class="card">
          <h3>1 Egg</h3>
          <p>Price: 15 Ksh</p>
          <button>Order 1 Egg</button>
        </div>
        <div class="card">
          <h3>1 Tray (30 Eggs)</h3>
          <p>Price: 450 Ksh</p>
          <button>Order Tray</button>
        </div>
      </div>
      <p><strong>Delivery Fees:</strong><br> Nairobi Area: 150 Ksh | Outside Nairobi: 200 Ksh</p>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="section">
      <h2>Our Gallery</h2>
      <div class="gallery">
        <div class="card"><img src="https://i.ibb.co/4tN0wvT/chickens.jpg" alt="Chickens"><p>Healthy Chickens</p></div>
        <div class="card"><img src="https://i.ibb.co/TY2m6nb/chicken-feed.jpg" alt="Chicken Feed"><p>Nutritious Chicken Feed</p></div>
        <div class="card"><img src="https://i.ibb.co/fnQ1mVH/egg-transport.jpg" alt="Egg Transport"><p>Safe Egg Transport</p></div>
      </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="section">
      <h2>What Our Customers Say</h2>
      <div class="testimonials">
        <div class="card">
          <p>"I bought from Kimzyy and I highly recommend them for the good work. Fresh eggs and timely delivery!"</p>
          <strong>- Ben Israel</strong>
        </div>
        <div class="card">
          <p>"Best egg delivery service I’ve used. Affordable and reliable."</p>
          <strong>- Mary W.</strong>
        </div>
      </div>
    </section>

    <!-- Order Section -->
    <section id="order" class="section">
      <h2>Place Your Order</h2>
      <form class="card">
        <label for="name">Full Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>

        <label for="phone">Phone Number:</label><br>
        <input type="tel" id="phone" name="phone" required><br><br>

        <label for="product">Select Product:</label><br>
        <select id="product" name="product" required>
          <option value="1egg">1 Egg - 15 Ksh</option>
          <option value="tray">1 Tray - 450 Ksh</option>
        </select><br><br>

        <label for="location">Delivery Location:</label><br>
        <select id="location" name="location" required>
          <option value="nairobi">Nairobi - 150 Ksh</option>
          <option value="outside">Outside Nairobi - 200 Ksh</option>
        </select><br><br>

        <button type="submit">Submit Order</button>
      </form>
    </section>
  </div>

  <footer>
    &copy; 2025 Kimzyy Fresh Eggs Delivery | All Rights Reserved
  </footer>
</body>
</html>
