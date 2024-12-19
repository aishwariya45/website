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
<html>
<head>
  <title>Restaurant Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="top-box">biryani</div>
   
  <nav class="nav-bar">
    <ul>
      <li><a href="menu.html" class="nav-link">Menu</a></li>
      <li><a href="gallery.html" class="nav-link">Gallery</a></li>
      <li><a href="contact.html" class="nav-link">Contact Us</a></li>
      <li><a href="administration.html" class="nav-link">Administration</a></li>
    </ul>
  </nav>
      <div class="food-item">
         <img src="chi.jpeg" alt="Kongguksu">
        <h3>30% OFF THIS WEEKEND</h3> 
    
      </div>
      <div class="food-item">
         <img src="pra.jpeg" alt="Kongguksu">
        <h3>CHECK OUT OUR NEW MENU</h3>
  
      </div>
  



</body>
</html>
<style>


body {
  background-color: burlywood;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-image: url("bg2.jpeg");
  
  margin: 0;
}



.top-box{
  background-color: #53504f;
  height:110px ;
  width: 100%;
  font-style: italic;
  font-weight: 300;
  font-size: 100px;
  text-align: center;
  text-shadow: 2px 2px #5c3b1f;
  box-shadow: 0px 0px 10px rgba(223, 27, 27, 0.5);
  color:#dd731b;

  
}
nav {
            background-color: #f1ebeb;
            padding: 10px ;
            text-align: center;
        }

        nav ul { background-color: rgb(16, 17, 17);
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #dd731b;
        }

        /* Menu Section Styles */
        .container {
            padding: 20px;
            text-align: center;
            flex-grow: 1;
        }

        h2 {
            font-size: 32px;
            color: #f7f0f0;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }

</style> 


administration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        nav {
            background-color: #333;
            padding: 10px ;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #dd731b;
        }

        /* Menu Section Styles */
        .container {
            padding: 20px;
            text-align: center;
            flex-grow: 1;
        }

        h2 {
            font-size: 32px;
            color: #333;
        }

        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .food-item {
            background-color: rgb(167, 165, 167);
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 30%;
            max-width: 300px;
            transition: transform 0.3s ease-in-out;
        }

        .food-item img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 10px;
        }

        .food-item h3 {
            font-size: 24px;
            color: #333;
        }

        .food-item p {
            font-size: 16px;
            color: #555;
            line-height: 1.5;
        }

        .food-item:hover {
            transform: scale(1.05);
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
            width: 100%;
            position: relative;
            bottom: 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="nav-bar">
        <ul>
            <li><a href="restaurant.html" class="nav-link">Home</a></li>
            <li><a href="menu.html" class="nav-link">Menu</a></li>
            <li><a href="gallery.html" class="nav-link">Gallery</a></li>
            <li><a href="contact.html" class="nav-link">Contact Us</a></li>
            <li><a href="administration.html" class="nav-link">Administration</a></li>
        </ul>
    </nav>

    <!-- Menu Section -->

<div class="container">
        <h2>Administration</h2>
        <div class="menu-items">
            <div class="food-item">
                <img src="gener.jpeg" alt="general manager">
                <h3>MAHI<br> General Manager</h3>
                
            </div>
            <div class="food-item">
                <img src="sanjeev.jpeg" alt="head chef">
                <h3>SANJEEV KAPOOR <br> Head Chef</h3>
                
            </div>
            <div class="food-item">
                <img src="imi.jpeg" alt="Sous chef">
                <h3>IMTIAZ QURESH <br> Chef</h3>

            </div>
            <div class="food-item">
                <img src="sup.jpeg" alt="Seolleongtang">
                <h3>PRADEEP<br> Restaurant Supervisor</h3>

            </div>
            <div class="food-item">
                <img src="mar.jpeg" alt="Tteokbokki">
                <h3>DavID <br> Marketing Manager</h3>

            </div>
            <div class="food-item">
                <img src="fin.jpeg" alt="Haemul Pajeon">
                <h3>Mobina <br> Finance Manager</h3>
               

        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>MAHIISHU</p>
    </footer>
</body>
</html>


contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .nav-bar {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        .nav-bar ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        .nav-bar ul li {
            display: inline-block;
            margin-right:20px;
        }

        .nav-bar ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        
        nav ul li a:hover {
            background-color: #dd731b;
        }

        h1 {
            text-align: center;
            margin-top: 30px;
            color: #333;
        }
        .info{
            text-align: center;
            font-size: 26px;
            padding: 25px;
            line-height: 2;
            color:#dd731b;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-weight: bold;

        }
        

    </style>
</head>
<body>

    <!-- Top Navigation Bar -->
    <nav class="nav-bar">
        <ul>
            <li><a href="restaurant.html" class="nav-link">Home</a></li>
            <li><a href="menu.html" class="nav-link">Menu</a></li>
            <li><a href="gallery.html" class="nav-link">Gallery</a></li>
            <li><a href="contact.html" class="nav-link">Contact Us</a></li>
            <li><a href="administration.html" class="nav-link">Administration</a></li>
        </ul>
    </nav>

    <!-- Gallery Title -->
    <h1>Contact Us</h1>
    <div class="info">Address: No.6, Mayor Ramanathan Salai (Spur Tank road) Chetpet, Chennai, Tamil Nadu 600031<br>
    Phone: +91 10200 10200<br>
    email:  mahiishu@gmail.com </div>

    

    <!-- Bottom Navigation Bar -->
</body>
</html>


menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .nav-bar {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        .nav-bar ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        .nav-bar ul li {
            display: inline-block;
            margin-right:20px;
        }

        .nav-bar ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        
        nav ul li a:hover {
            background-color: #dd731b;
        }

        h1 {
            text-align: center;
            margin-top: 30px;
            color: #333;
        }
        .info{
            text-align: center;
            font-size: 26px;
            padding: 25px;
            line-height: 2;
            color:#dd731b;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-weight: bold;

        }
        

    </style>
</head>
<body>

    <!-- Top Navigation Bar -->
    <nav class="nav-bar">
        <ul>
            <li><a href="restaurant.html" class="nav-link">Home</a></li>
            <li><a href="menu.html" class="nav-link">Menu</a></li>
            <li><a href="gallery.html" class="nav-link">Gallery</a></li>
            <li><a href="contact.html" class="nav-link">Contact Us</a></li>
            <li><a href="administration.html" class="nav-link">Administration</a></li>
        </ul>
    </nav>

    <!-- Gallery Title -->
    <h1>Contact Us</h1>
    <div class="info">Address: No.6, Mayor Ramanathan Salai (Spur Tank road) Chetpet, Chennai, Tamil Nadu 600031<br>
    Phone: +91 10200 10200<br>
    email:  mahiishu@gmail.com </div>

    

    <!-- Bottom Navigation Bar -->
</body>
</html>


about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Images with Same Size</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .nav-bar {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        .nav-bar ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        .nav-bar ul li {
            display: inline-block;
            margin-right:20px;
        }

        .nav-bar ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: background-color 0.3s;
        }

        
        nav ul li a:hover {
            background-color: #dd731b;
        }

        h1 {
            text-align: center;
            margin-top: 30px;
            color: #333;
        }

        .image-container {
            display: flex;
            justify-content: space-between;
            gap: 10px; /* Space between images */
            padding: 20px;
            flex-wrap: wrap; /* To ensure images wrap if the screen is smaller */
        }

        .image-container img {
            width: 23%; /* Fixed width for each image, allowing for some space between */
            height: auto; /* Maintain aspect ratio */
            border-radius: 8px;
            margin-bottom: 10px;
            object-fit: cover; /* Ensures the image fits the container without stretching */
        }

    </style>
</head>
<body>

    <!-- Top Navigation Bar -->
    <nav class="nav-bar">
        <ul>
            <li><a href="restaurant.html" class="nav-link">Home</a></li>
            <li><a href="menu.html" class="nav-link">Menu</a></li>
            <li><a href="gallery.html" class="nav-link">Gallery</a></li>
            <li><a href="contact.html" class="nav-link">Contact Us</a></li>
            <li><a href="administration.html" class="nav-link">Administration</a></li>
        </ul>
    </nav>

    <!-- Gallery Title -->
    <h1>Gallery</h1>

    <!-- Image Gallery Container -->
    <div class="image-container">
        <img src="g2.jpeg" alt="Image 1">
        <img src="g3.jpeg" alt="Image 2">
        <img src="g5.jpeg" alt="Image 3">
        <img src="g4.jpeg" alt="Image 4">
    </div>

    <!-- Bottom Navigation Bar -->
    
</body>
</html>
```
# OUTPUT:
![alt text](<aishu/resapp/static/Screenshot 2024-12-19 104818.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-19 104855.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-19 104944.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-19 105900.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-19 105032.png>)
![alt text](<aishu/resapp/static/Screenshot 2024-12-19 104957.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
