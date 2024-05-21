<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cake Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #f2f2f2;
      padding: 20px;
      text-align: center;
    }
    nav {
      text-align: center;
      margin-top: 20px;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #333;
    }
    .container {
      width: 80%;
      margin: auto;
      text-align: center;
    }
    .cake {
      margin-bottom: 30px;
    }
    .cake img {
      width: 100%;
      max-width: 300px;
    }
    .cake h2 {
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Cake World!</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#menu">Menu</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  
  <div id="home" class="container">
    <h2>About Us</h2>
    <p>Welcome to Cake World! We specialize in creating delicious cakes for all occasions.</p>
    <img src="cake.jpg" alt="Cake">
  </div>
  
  <div id="about" class="container">
    <h2>About Us</h2>
    <p>We are a team of passionate bakers dedicated to crafting beautiful and mouthwatering cakes that will make your special moments even sweeter.</p>
  </div>
  
  <div id="menu" class="container">
    <h2>Our Menu</h2>
    <div class="cake">
      <img src="cake1.jpg" alt="Cake 1">
      <h2>Chocolate Cake</h2>
      <p>A rich and decadent chocolate cake, perfect for any chocolate lover.</p>
    </div>
    <div class="cake">
      <img src="cake2.jpg" alt="Cake 2">
      <h2>Vanilla Cake</h2>
      <p>A classic vanilla cake with a light and fluffy texture, ideal for any celebration.</p>
    </div>
    <div class="cake">
      <img src="cake3.jpg" alt="Cake 3">
      <h2>Strawberry Cake</h2>
      <p>A delightful strawberry cake bursting with fresh fruit flavor, sure to brighten any occasion.</p>
    </div>
  </div>
  
  <div id="contact" class="container">
    <h2>Contact Us</h2>
    <p>If you have any questions or inquiries, feel free to reach out to us:</p>
    <p>Email: info@cakeworld.com</p>
    <p>Phone: 123-456-7890</p>
  </div>
</body>
</html>
