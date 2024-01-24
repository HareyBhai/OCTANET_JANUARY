# OCTANET_JANUARY
**HTML**
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Delivery Service</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Food Delivery Service</h1>
        <p>Delicious meals delivered to your doorstep!</p>
    </header>

    <section class="menu">
        <h2>Menu</h2>
        <div class="dish">
            <img src="pizza.jpg" alt="Pizza" width="400" 
            height="500">
            <h3>Pizza</h3>
            <p>Classic Margherita with fresh tomatoes and mozzarella.</p>
            <span class="price">400 Rs</span>
        </div>
        <div class="dish">
            <img src="burger.jpg" alt="Burger" width="400" 
            height="500">
            <h3>Burger</h3>
            <p>Juicy beef patty with lettuce, tomato, and special sauce.</p>
            <span class="price">210 Rs</span>
        </div>
        <!-- Add more dishes as needed -->
    </section>

    <section class="order">
        <h2>Place Your Order</h2>
        <form>
            <label for="dish">Select Dish:</label>
            <select id="dish" name="dish">
                <option value="pizza">Pizza - 400 Rs</option>
                <option value="burger">Burger - 210 Rs</option>
                <!-- Add more options as needed -->
            </select>

            <label for="quantity">Quantity:</label>
            <input type="number" id="quantity" name="quantity" min="1" value="1">

            <button type="submit">Order Now</button>
        </form>
    </section>
</body>
</html>

**CSS**
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1 {
    margin: 0;
}

.menu {
    padding: 20px;
    text-align: center;
}

.dish {
    margin: 20px;
}

img {
    max-width: 100%;
    height: auto;
}

.price {
    display: block;
    color: #3498db;
    margin-top: 5px;
}

.order {
    background-color: #fff;
    padding: 20px;
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: 0 auto;
}

label {
    margin-bottom: 5px;
}

input, select {
    margin-bottom: 10px;
    padding: 10px;
}

button {
    background-color: #3498db;
    color: #fff;
    padding: 10px;
    cursor: pointer;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

