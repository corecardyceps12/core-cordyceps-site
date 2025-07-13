<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Core Cordyceps Production</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background-color: #f5fff5; color: #333; }
    header { background-color: #14532d; color: white; padding: 1rem; text-align: center; }
    nav { background: #064e3b; display: flex; justify-content: center; gap: 1.5rem; padding: 0.5rem; }
    nav a { color: white; text-decoration: none; font-weight: bold; }
    .hero { background: url('cordyceps-banner.jpg') no-repeat center center/cover; height: 300px; color: white; display: flex; align-items: center; justify-content: center; text-shadow: 1px 1px 3px #000; }
    .hero h1 { font-size: 2.5rem; }
    .content { padding: 2rem; text-align: center; }
    .btn { background-color: #16a34a; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; }
  </style>
</head>
<body>
  <header>
    <h1>Core Cordyceps Production Company</h1>
    <p>Lab-Grown | Natural | Trusted</p>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About Us</a>
    <a href="products.html">Products</a>
    <a href="gallery.html">Gallery</a>
    <a href="contact.html">Contact</a>
  </nav>
  <div class="hero">
    <h1>Premium Cordyceps Grown with Care</h1>
  </div>
  <div class="content">
    <h2>Welcome to Core</h2>
    <p>
      We specialize in the production and selling of high-quality, lab-grown Cordyceps militaris. Pure, potent, and packed with natural benefits.
    </p>
    <a class="btn" href="products.html">See Our Products</a>
  </div>
</body>
</html>

<!-- about.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>About Us - Core Cordyceps</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background-color: #ffffff; color: #333; padding: 2rem; }
    h1 { color: #14532d; text-align: center; }
  </style>
</head>
<body>
  <h1>About Core</h1>
  <p>
    Core Cordyceps Production Company is the dream of Faisal and Esma. We grow and supply high-quality Cordyceps militaris using cutting-edge lab techniques. 
    Our facility is equipped to ensure the purest, most potent medicinal fungi for health-conscious customers.
  </p>
</body>
</html>

<!-- products.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Products - Core Cordyceps</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f0fff0; padding: 2rem; }
    h1 { color: #14532d; text-align: center; }
    .product { border: 1px solid #ccc; padding: 1rem; margin: 1rem auto; max-width: 400px; background: white; border-radius: 8px; }
    .product img { width: 100%; border-radius: 8px; }
    .btn { background: #16a34a; color: white; padding: 10px; display: inline-block; margin-top: 10px; text-decoration: none; border-radius: 4px; }
  </style>
</head>
<body>
  <h1>Our Products</h1>
  <div class="product">
    <img src="cordyceps-dried.jpg" alt="Cordyceps Dried">
    <h2>Dried Cordyceps militaris (10g)</h2>
    <p>Price: ₹1500</p>
    <a class="btn" href="contact.html">Order Now</a>
  </div>
</body>
</html>

<!-- gallery.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gallery - Core Cordyceps</title>
  <style>
    body { font-family: Arial, sans-serif; background: #fff; padding: 2rem; }
    h1 { text-align: center; color: #14532d; }
    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; margin-top: 2rem; }
    .gallery img { width: 100%; border-radius: 8px; border: 1px solid #ccc; }
  </style>
</head>
<body>
  <h1>Lab & Product Gallery</h1>
  <div class="gallery">
    <img src="lab-1.jpg" alt="Lab Setup">
    <img src="cordyceps-jar.jpg" alt="Cordyceps in Jar">
    <img src="fruiting-room.jpg" alt="Fruiting Room">
    <img src="cordyceps-packaged.jpg" alt="Packaged Cordyceps">
  </div>
</body>
</html>

<!-- contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Core Cordyceps</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f0fff0; padding: 2rem; }
    h1 { text-align: center; color: #14532d; }
    form { max-width: 500px; margin: auto; display: flex; flex-direction: column; gap: 1rem; }
    input, textarea { padding: 10px; border: 1px solid #ccc; border-radius: 5px; }
    button { background: #16a34a; color: white; padding: 10px; border: none; border-radius: 5px; }
  </style>
</head>
<body>
  <h1>Contact Us</h1>
  <form action="#" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" rows="5" placeholder="Your Message"></textarea>
    <button type="submit">Send Message</button>
  </form>
</body>
</html>
