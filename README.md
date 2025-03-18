# restaurant-project
HTML CODE::::::------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home" class="hero">
        <h1>Welcome to Our Restaurant</h1>
        <p>Delicious food, cozy ambiance, and great service!</p>
    </section>
    
    <section id="menu">
        <h2 style="text-align: center; background-color: black;
         color: white; margin-left: 100px; margin-right: 100px;">Our Menu</h2>
        
        
        <div class="menu-grid">
            <div class="menu-item">
                <img src="maindish1.jpg" alt="Food Item">
                <h3>Special Thali</h3>
                <p>$10.99</p>
            </div>
            <div class="menu-item">
                <img src="butterchicken.jpg" alt="Food Item">
                <h3>Butter Chicken</h3>
                <p>$12.99</p>
            </div>
        </div>
    </section>
    
    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-grid">
            <img src="dish1.jpg" alt="Gallery Image">
            <img src="dish2.jpg" alt="Gallery Image">
            <img src="dish3.jpg" alt="Gallery Image">
            <img src="dish2.jpg" alt="Gallery Image">
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
       Address:xyz  <br>
        Email: <a href="#" style="text-decoration: none;">shivampokhriyal@gmail.com</a>
    </section>
    
    <footer>
        <p>&copy; 2025 Techy court. All rights reserved.</p>
    </footer>
</body>
</html>


CSS CODE::::----
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
#home{
    background-color: black;
    background-image: url(food.jpg);
    background-size: cover;
    font-size: 20px;
}
header {
    background: #333;
    color: white;
    padding: 15px 0;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;

}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

.hero {

    color: white;
    text-align: center;
    padding: 100px 20px;
}

.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px;
    text-align: center;
}

.menu-item img {
    width: 100%;
    border-radius: 10px;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 10px;
    padding: 20px;
}

.gallery-grid img {
    width: 100%;
    border-radius: 5px;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
#contact{
    text-align: center;
}
