# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>MAHI RESTAURANT</h1>
    <nav>
      <a href="about.html">About Us</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Team</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section id="logo-details">
    <div class="logo-container">
      <img src="index.png" alt="Restaurant Logo" class="restaurant-logo" height="150px" width="150px">
    </div>
    
    <div class="restaurant-details">
      <h2>Welcome to Mahi  Restaurant</h2>
      <p>Located in the heart of Chennai, Mahi Restaurant offers a memorable dining experience with a focus on high-quality food and exceptional service. Our mission is to provide a wide variety of delicious dishes made from fresh, locally sourced ingredients in a warm and inviting atmosphere. Whether it's a casual meal or a special occasion, we have something for everyone!</p>
    </div>
  </section>

  <main>
    <section id="about">
        <h2>About Us</h2>
        <p>Learn more about our restaurant and the experience we offer to our customers. Click on the "About Us" link in the navigation to explore more.</p>
    </section>

  </main>

  <footer>
    <p>&copy; 2024 Mahi</p>
  </footer>
</body>
</html>

administration.htnml

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Team - MAHI Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Team</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="about.html">About Us</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <main>
    <section>
      <h2>Meet Our Team</h2>
      <div class="team">
        <div class="member">
          <img src="mahi.jpeg" alt="Mahi - Manager">
          <p>Mahi - Manager</p>
        </div>
        <div class="member">
          <img src="aishu.jpeg" alt="Aishu - Chef">
          <p>Aishu - Chef</p>
        </div>
        <div class="member">
          <img src="aishu2.jpeg" alt="Sam Lee - Waiter">
          <p>Sam Lee - Waiter</p>
        </div>
      </div>
    </section>
  </main>
  <footer>
    <p>&copy; 2024 Mahi</p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Mahi Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="about.html">About Us</a>
      <a href="administration.html">Our Team</a>
    </nav>
  </header>
  <main>
    <section>
      <h2>Get in Touch</h2>
      <img src="contactaishu.jpeg" alt="Contact Banner" class="contact-banner" height="20px" width="20px">
      <p>Address: 123 Food Street, Chennai, India</p>
      <p>Phone: +91 9876543210</p>
      <p>Email: contact@restaurant.com</p>
    </section>
  </main>
  <footer>
    <p>&copy; 2024 Mahi</p>
  </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">About Me</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <main>

    <h2>Delicious Dishes</h2>
    <div class="menu-grid">
      <div class="menu-item" onclick="showDetails('cake', 'images/ca.jpg')">
        <img src="cake.jpeg" alt="cake">
        <p>cake</p>
      </div>
      <div class="menu-item" onclick="showDetails('cheese cake', 'images/d1.jpg')">
        <img src="cheese cake.jpeg" alt="cheese cake">
        <p>cheese cake</p>
      </div>
      <div class="menu-item" onclick="showDetails('apple pie', 'images/d3.jpg')">
        <img src="apple.jpeg" alt="apple pie">
        <p>apple pie</p>
      </div>
      <div class="menu-item" onclick="showDetails('tiramisu', 'images/d4.jpg')">
        <img src="tiramisu.jpeg" alt="tiramisu">
        <p>tiramisu</p>
      </div>
    </div>
    <div id="food-details" class="food-details">
      <!-- Food details will display dynamically here -->
    </div>
  </main>
  <footer>
    <p>&copy; 2024 Mahi</p>
  </footer>
  <script>
    function showDetails(name, imgSrc) {
      const details = document.getElementById('food-details');
      details.innerHTML = `
        <h3>${name}</h3>
        <img src="${imgSrc}" alt="${name}" style="width:300px; height:auto; margin-top:10px;">
      `;
    }
  </script>
</body>
</html>



about .html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mahi Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Mahi Restaurant</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Our Team</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <main>
    <section>
      <h2>Welcome to Mahi Restaurant</h2>
      <img src="abo.jpeg" alt="Restaurant Image" class="about-image" height="20px" width="20px">  
      <p>Located in the heart of Chennai, Mahi Restaurant offers a memorable dining experience with a focus on high-quality food and exceptional service. Our mission is to provide a wide variety of delicious dishes made from fresh, locally sourced ingredients in a warm and inviting atmosphere.</p>
      <p>Whether it's a casual meal or a special occasion, we have something for everyone!</p>
    </section>
  </main>
  <footer>
    <p>&copy; 2024 Mahi</p>
  </footer>
</body>
</html>

style.css

#logo-details {
    text-align: center;
    padding: 40px 20px;
    background-color: #fff;
  }
  
  .logo-container {
    margin-bottom: 20px;
  }
  
  .restaurant-logo {
    width: 200px; /* Adjust size as needed */
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  .restaurant-details h2 {
    font-size: 28px;
    margin-top: 20px;
    color: #333;
  }
  
  .restaurant-details p {
    font-size: 18px;
    color: #666;
    line-height: 1.6;
    max-width: 800px;
    margin: 10px auto;
  }
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #f9f9f9;
    color: #333;
  }
  
  header {
    background: #333;
    color: #fff;
    padding: 10px 20px;
    text-align: center;
  }
  
  nav a {
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
  }
  
  nav a:hover {
    text-decoration: underline;
  }
  
  main {
    padding: 20px;
  }
  
  section {
    margin-bottom: 40px;
  }
  
  .about p {
    font-size: 18px;
    margin: 20px 0;
  }
  
  .about-image, .menu-banner, .contact-banner {
    display: block;
    margin: 0 auto 20px;
    width: 80%;
    height: auto;
  }
  
  .menu-list {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    justify-items: center;
  }
  
  .menu-item {
    text-align: center;
    background-color: #fff;
    border-radius: 10px;
    padding: 10px;
    border: 1px solid #ccc;
  }
  
  .menu-item-image {
    width: 100%;
    height: auto;
    border-radius: 10px;
  }
  
  .menu-item p {
    margin-top: 10px;
    font-size: 18px;
    font-weight: bold;
  }
  
  .team {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }
  
  .member {
    text-align: center;
    border: 1px solid #ccc;
    border-radius: 10px;
    padding: 10px;
    width: 200px;
    background-color: #fff;
  }
  
  .member img {
    width: 100%;
    height: auto;
    border-radius: 10px;
  }
  
  .member p {
    margin-top: 10px;
    font-size: 16px;
    font-weight: bold;
  }
  
  footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: #fff;
    margin-top: 20px;
  }
  
  @media (max-width: 768px) {
    header h1 {
      font-size: 20px;
    }
    nav {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .menu-item p {
      font-size: 16px;
    }
    .menu-list {
      grid-template-columns: 1fr 1fr;
    }
    .team {
      flex-direction: column;
      align-items: center;
    }
    .member {
      width: 100%;
      max-width: 300px;
    }
  }
```
# OUTPUT:
![alt text](<aishu/resapp/static/Screenshot 2024-12-17 180505.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-17 181115.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-17 183737.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-17 184346.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-17 184657.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
