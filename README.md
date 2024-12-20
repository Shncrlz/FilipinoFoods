<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Filipino Foods</title>
  <link rel="stylesheet" href="food.css">
</head>
<body>
  <header>
    <h1>Filipino Foods</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#popular">Popular Dishes</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about" class="section">
    <h2>About Filipino Cuisine</h2>
    <p>Filipino cuisine is a mix of rich flavors influenced by Spanish, Chinese, and native traditions. It’s known for its vibrant dishes, diverse ingredients, and bold flavors.</p>
  </section>

  <section id="popular" class="section">
  <h2>Popular Filipino Dishes</h2>
  <div class="food-gallery">
    <div class="food-card">
      <img src="../IMAGEFOODS/adobos.png" alt="Chicken Adobo">
      <h3>Chicken Adobo</h3>
      <p>A savory and tangy dish made with soy sauce, vinegar, and garlic.</p>
      <ul>
        <li>Chicken</li>
        <li>Soy sauce</li>
        <li>Vinegar</li>
        <li>Garlic</li>
        <li>Bay leaves</li>
        <li>Black pepper</li>
      </ul>
    </div>
    
    <div class="food-card">
      <img src="../IMAGEFOODS/sinigangs.png" alt="Sinigang">
      <h3>Sinigang</h3>
      <p>A sour soup flavored with tamarind, vegetables, and meat or seafood.</p>
      <ul>
        <li>Tamarind</li>
        <li>Pork or shrimp</li>
        <li>Water spinach (Kangkong)</li>
        <li>Radish</li>
        <li>Tomatoes</li>
        <li>Green chili</li>
      </ul>
    </div>
    
    <div class="food-card">
      <img src="../IMAGEFOODS/lechons.png" alt="Lechon">
      <h3>Lechon</h3>
      <p>Whole roasted pig, a centerpiece for Filipino celebrations.</p>
      <ul>
        <li>Whole pig</li>
        <li>Salt</li>
        <li>Black pepper</li>
        <li>Garlic</li>
        <li>Lemongrass</li>
        <li>Vinegar (for marination)</li>
      </ul>
    </div>
    
    <div class="food-card">
      <img src="../IMAGEFOODS/sisigs.png" alt="Sisig">
      <h3>Sisig</h3>
      <p>A sizzling dish made of pork, liver, and spices, served with calamansi.</p>
      <ul>
        <li>Pork cheeks</li>
        <li>Pork liver</li>
        <li>Onion</li>
        <li>Garlic</li>
        <li>Calamansi or lime</li>
        <li>Egg (optional, for topping)</li>
      </ul>
    </div>
  </div>
</section>


  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="4" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

    <footer>
  <p> Address: PHILIPPINES, MANILA, MALABON, LONGOS</p>
  <div class="fbinstatweet">
    <a href="https://www.facebook.com" target="_blank" aria-label="Facebook">
      <img src="../image/Fb.webp" alt="Facebook">
    </a>
    <a href="https://www.instagram.com" target="_blank" aria-label="Instagram">
      <img src="../image/insta.webp" alt="Instagram">
    </a>
    <a href="https://www.twitter.com" target="_blank" aria-label="Twitter">
      <img src="../image/twitter.webp" alt="Twitter">
    </a>
  </div>
</footer>

</body>
</html>


body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  color: #eaeaea;
  background-color: #121212;
}

header {
  background-color: #1f1f1f;
  color: #f39c12;
  padding: 1rem 0;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
}


header nav {
  background-color: #333;
  padding: 10px 0;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
}

header nav ul {
  list-style: none;
  padding: 10px 20px;
  margin: 0 auto;
  display: flex; 
  gap: 10px; 
}

header nav ul li {
  display: inline-block;
  padding: 10px 20px; 
  background-color: #444; 
  border-radius: 15px; 
  color: #fff; 
  text-align: center;
  transition: background-color 0.3s ease; 
}

header nav ul li:nth-child(1) {
  background-color: #f39c12;
}

header nav ul li:nth-child(2) {
  background-color: #f39c12; 
}

header nav ul li:nth-child(3) {
  background-color: #f39c12; 
}


header nav ul li a {
  text-decoration: none;
  color: #fff; 
  font-size: 1.1rem;
  display: inline-block;
}

header nav ul li:hover {
  background-color: #555;
}


.section {
  padding: 2rem;
  text-align: center;
  background-color: #1e1e1e;
  margin: 1rem 0;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
}


.food-gallery {
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap;
}

.food-card {
  border: 1px solid #333;
  border-radius: 5px;
  overflow: hidden;
  max-width: 300px;
  text-align: left;
  background-color: #222; 
  color: #eaeaea;
}

.food-card ul {
  margin: 10px 0 0;
  padding: 0 20px;
  list-style-type: disc;
  color: #eaeaea;
}

.food-card ul li {
  margin-bottom: 5px;
}


.food-card img {
  width: 100%;
  height: auto;
}

.food-card h3 {
  background-color: #f39c12;
  color: #121212;
  margin: 0;
  padding: 0.5rem;
}


form {
  max-width: 500px;
  margin: 0 auto;
  text-align: left;
}

form label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border: 1px solid #555;
  border-radius: 4px;
  background-color: #2c2c2c; 
  color: #eaeaea;
}

form input::placeholder, form textarea::placeholder {
  color: #777;
}

form button {
  background-color: #f39c12;
  color: #121212;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
  border-radius: 4px;
}

form button:hover {
  background-color: #e67e22;
}


footer {
  background-color: #1f1f1f;
  color: #eaeaea;
  text-align: center;
  padding: 1rem 0;
  margin-top: 2rem;
}


.fbinstatweet {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-top: 10px;
}

.fbinstatweet a {
  display: inline-block;
  width: 40px;
  height: 40px;
  background-color: #333;
  border-radius: 50%;
  text-align: center;
  line-height: 40px;
  transition: background-color 0.3s ease;
}

.fbinstatweet a:hover {
  background-color: #f39c12;
}

.fbinstatweet img {
  width: 20px;
  height: 20px;
  vertical-align: middle;
}
