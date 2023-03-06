# my-website
HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
    <title>Foodies</title>
    <link rel="stylesheet" href="style.css" type="text/css" media="screen" />
  </head>
  <body>
    <div class="banner">
      <img src="images/image1.jpeg" alt="Foodies banner">
    </div>
    <div class="container">
      <h1>Welcome to Foodies</h1>
      <p>Order delicious meals from your favorite restaurants.</p>
      <button class="btn-primary">Order Now</button>
    </div>
  </div>
  <section class="about">
    <div class="container">
      <h2>About Foodies</h2>
      <p>Foodies is a food delivery service that allows you to order food from your favorite restaurants and have it delivered right to your doorstep. With Foodies, you can easily browse menus, place orders, and track your deliveries in real-time.</p>
    </div>
  </section>
  <section class="how-it-works">
    <div class="container">
      <h2>How It Works</h2>
      <div class="step">
        <img src="images/step-1.png" alt="Step 1">
        <h3>Browse Menus</h3>
        <p>Find your favorite restaurants and browse their menus to find the perfect meal.</p>
      </div>
      <div class="step">
        <img src="images/image2.jpeg" alt="Step 2">
        <h3>Place Your Order</h3>
        <p>Add items to your cart, select your payment method, and place your order.</p>
      </div>
      <div class="step">
        <img src="images/image2.jpeg" alt="Step 3">
        <h3>Track Your Delivery</h3>
        <p>Get real-time updates on your delivery and track your driver on a map.</p>
      </div>
    </div>
  </section>
  <section class="teachers">
    <div class="container">
      <h2>Popular Restaurants</h2>
      <div class="teachers">
        <img src="images/image3.jpeg" alt="Teacher 1">
        <h3>La Pizzeria</h3>
        <p>Italian, Pizza</p>
        <a href="#" class="btn-blue">Order Now</a>
      </div>
      <div class="teachers">
        <img src="images/image4.jpeg" alt="Teacher 2">
        <h3>El Chiringuito</h3>
        <p>Spanish, Seafood</p>
        <a href="#" class="btn-blue">Order Now</a>
      </div>
      <div class="teachers">
        <img src="images/image5.jpeg" alt="Teacher 3">
        <h3>Sushi Express</h3>
        <p>Japanese, Sushi</p>
        <a href="#" class="btn-blue">Order Now</a>
      </div>
    </div>
  </section>
</body>
</html>

Css :

* Ajout de bordures et ombres */
body {
  border: 1px solid #ddd;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
}
 
.header {
  border-bottom: 1px solid #ddd;
  padding: 10px;
  box-shadow: 0 5px 10px rgba(0,0,0,0.1);
}
 
img {
  border: 1px solid #ddd;
  border-radius: 5px;
  box-shadow: 0 0 5px rgba(0,0,0,0.2);
}
 
.step img {
  max-width: 300px;
}
 
.restaurant img {
  max-width: 700px;
  max-height: 300px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
}
 
/* Mise en page professionnelle et attrayante */
body {
  max-width: 1000px;
  margin: 0 auto;
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
}
 
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #fff;
}
 
.logo {
  font-size: 30px;
  font-weight: bold;
  color: #f15a29;
  text-shadow: 2px 2px 3px rgba(0,0,0,0.1);
}
 
.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-right: 20px;
}
 
.nav a {
  margin-left: 10px;
  text-decoration: none;
  color: #333;
  font-size: 20px;
  font-weight: bold;
  border: 1px solid #f15a29;
  padding: 5px 10px;
  border-radius: 20px;
  transition: all 0.2s ease-in-out;
}
 
.nav a:hover {
  background-color: #f15a29;
  color: #fff;
}
 
.content {
  margin-top: 20px;
  padding: 20px;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 5px 10px rgba(0,0,0,0.1);
}
 
.title {
  font-size: 30px;
  font-weight: bold;
  color: #f15a29;
  text-shadow: 2px 2px 3px rgba(0,0,0,0.1);
}
 
.description {
  margin-top: 10px;
  font-size: 18px;
  color: #666;
  line-height: 1.5;
}
 
.footer {
  border-top: 1px solid #ddd;
  padding: 10px;
  text-align: center;
  font-size: 14px;
  color: #666;
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0 5px 10px rgba(0,0,0,0.1);
}
