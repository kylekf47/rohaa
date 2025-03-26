<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roha Burger, Pizza & Juice Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        section {
            padding: 20px;
            background-color: white;
            margin: 10px 0;
        }
        .card-container {
            display: grid;
            grid-template-columns: repeat(1, 1fr); /* Default for mobile: single column */
            gap: 20px;
            justify-items: center;
        }
        .card {
            background-color: #fff;
            width: 250px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 15px;
        }
        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
        }
        .card h3 {
            font-size: 20px;
            margin-top: 10px;
        }
        .card p {
            font-size: 16px;
            color: #555;
        }
        .card .price {
            font-size: 18px;
            color: #333;
            font-weight: bold;
            margin-top: 10px;
        }
        .back-to-top {
            text-align: center;
            margin-top: 20px;
        }

        /* Media query for larger screens (tablet, desktop, etc.) */
        @media (min-width: 600px) {
            .card-container {
                grid-template-columns: repeat(2, 1fr); /* 2 columns for tablets */
            }
        }
        @media (min-width: 900px) {
            .card-container {
                grid-template-columns: repeat(3, 1fr); /* 3 columns for desktop */
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Roha Burger, Pizza & Juice Menu</h1>
</header>

<nav>
    <a href="#burgers">🍔 Burgers</a> | 
    <a href="#pizzas">🍕 Pizzas</a> | 
    <a href="#juices">🥤 Juices & Drinks</a> | 
    <a href="#fastfood">🍟 Fast Food</a> |
    <a href="#hotdrinks">☕ Hot Drinks</a> |
    <a href="#softdrinks">🥤 Soft Drinks</a> | 
    <a href="#contact">📍 Visit Us</a>
</nav>

<section id="burgers">
    <h2>🍔 BURGERS</h2>
    <div class="card-container">
        <div class="card">
            <img src="burger_image1.jpg" alt="Classic Beef Burger">
            <h3>Classic Beef Burger</h3>
            <p>A juicy beef patty with fresh lettuce, tomatoes, and our special sauce.</p>
            <p class="price">$5.99</p>
        </div>
        <div class="card">
            <img src="burger_image2.jpg" alt="Cheese Burger">
            <h3>Cheese Burger</h3>
            <p>Delicious beef patty topped with melted cheese, lettuce, and pickles.</p>
            <p class="price">$6.99</p>
        </div>
        <div class="card">
            <img src="burger_image3.jpg" alt="Roha Special Burger">
            <h3>Roha Special Burger</h3>
            <p>A signature burger with a unique blend of spices and premium toppings.</p>
            <p class="price">$7.99</p>
        </div>
    </div>
</section>

<section id="pizzas">
    <h2>🍕 PIZZAS</h2>
    <div class="card-container">
        <div class="card">
            <img src="pizza_image1.jpg" alt="Margherita Pizza">
            <h3>Margherita Pizza</h3>
            <p>A classic pizza topped with fresh tomatoes, mozzarella, and basil.</p>
            <p class="price">$9.99</p>
        </div>
        <div class="card">
            <img src="pizza_image2.jpg" alt="Pepperoni Pizza">
            <h3>Pepperoni Pizza</h3>
            <p>Loaded with pepperoni and melted cheese on a fresh tomato base.</p>
            <p class="price">$10.99</p>
        </div>
        <div class="card">
            <img src="pizza_image3.jpg" alt="BBQ Chicken Pizza">
            <h3>BBQ Chicken Pizza</h3>
            <p>Tender BBQ chicken, onions, and a smoky sauce for an amazing flavor.</p>
            <p class="price">$11.99</p>
        </div>
    </div>
</section>

<section id="juices">
    <h2>🥤 JUICES & DRINKS</h2>
    <div class="card-container">
        <div class="card">
            <img src="juice_image1.jpg" alt="Fresh Orange Juice">
            <h3>Fresh Orange Juice</h3>
            <p>Freshly squeezed oranges, served chilled for a refreshing taste.</p>
            <p class="price">$3.99</p>
        </div>
        <div class="card">
            <img src="juice_image2.jpg" alt="Mango Juice">
            <h3>Mango Juice</h3>
            <p>Sweet and tropical mango juice, perfect for hot days.</p>
            <p class="price">$4.49</p>
        </div>
        <div class="card">
            <img src="juice_image3.jpg" alt="Avocado Juice">
            <h3>Avocado Juice</h3>
            <p>A creamy blend of fresh avocados and a touch of sweetness.</p>
            <p class="price">$4.99</p>
        </div>
    </div>
</section>

<!-- Fast Food Section -->
<section id="fastfood">
    <h2>🍟 FAST FOOD</h2>
    <div class="card-container">
        <div class="card">
            <img src="fastfood_image1.jpg" alt="French Fries">
            <h3>French Fries</h3>
            <p>Crispy golden fries, served with a side of ketchup or your favorite dip.</p>
            <p class="price">$2.99</p>
        </div>
        <div class="card">
            <img src="fastfood_image2.jpg" alt="Chicken Nuggets">
            <h3>Chicken Nuggets</h3>
            <p>Juicy, tender chicken nuggets served with your choice of dipping sauce.</p>
            <p class="price">$4.49</p>
        </div>
        <div class="card">
            <img src="fastfood_image3.jpg" alt="Onion Rings">
            <h3>Onion Rings</h3>
            <p>Crispy, golden onion rings served with a tangy dipping sauce.</p>
            <p class="price">$3.99</p>
        </div>
    </div>
</section>

<!-- Hot Drinks Section -->
<section id="hotdrinks">
    <h2>☕ HOT DRINKS</h2>
    <div class="card-container">
        <div class="card">
            <img src="hotdrink_image1.jpg" alt="Coffee">
            <h3>Coffee</h3>
            <p>Freshly brewed coffee, served hot to give you the perfect start to your day.</p>
            <p class="price">$2.49</p>
        </div>
        <div class="card">
            <img src="hotdrink_image2.jpg" alt="Hot Chocolate">
            <h3>Hot Chocolate</h3>
            <p>A rich, creamy hot chocolate with a dash of vanilla and whipped cream.</p>
            <p class="price">$3.49</p>
        </div>
        <div class="card">
            <img src="hotdrink_image3.jpg" alt="Tea">
            <h3>Tea</h3>
            <p>Relaxing hot tea, available in various flavors like green, black, and herbal.</p>
            <p class="price">$1.99</p>
        </div>
    </div>
</section>

<!-- Soft Drinks Section -->
<section id="softdrinks">
    <h2>🥤 SOFT DRINKS</h2>
    <div class="card-container">
        <div class="card">
            <img src="softdrink_image1.jpg" alt="Coca-Cola">
            <h3>Coca-Cola</h3>
            <p>Refreshing Coca-Cola, served ice-cold for the perfect refreshment.</p>
            <p class="price">$1.99</p>
        </div>
        <div class="card">
            <img src="softdrink_image2.jpg" alt="Sprite">
            <h3>Sprite</h3>
            <p>Crisp and refreshing lemon-lime soda, served ice-cold.</p>
            <p class="price">$1.99</p>
        </div>
        <div class="card">
            <img src="softdrink_image3.jpg" alt="Fanta">
            <h3>Fanta</h3>
            <p>Fruity and refreshing Fanta, available in various flavors like orange and grape.</p>
            <p class="price">$1.99</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>📍 Visit Us</h2>
    <p>Come visit us at our convenient location!</p>
</section>

</body>
</html>
