# Ex.07 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
table.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>java foods</title>
    <style>
        body {
            background-color: cornsilk;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color:grey;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color:chocolate;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color:grey;
        }
        .hero {
             background-color:navajowhite;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3rem;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .menu-item {
            border: 1px solid:silver;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color:grey;
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Java foods</h1>
    </header>
    <nav>
        <a href="home.html">home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="hero">
        <h1>Welcome to Our Restaurant</h1>
    </div>
    <section id="about">
        <h2>About Us</h2>
        <p>We are passionate about serving delicious food made with fresh ingredients. Join us for an unforgettable dining experience!</p>
    </section>
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu">
            <div class="menu-item">
                <img src=c:\Users\admin\OneDrive\Desktop\pran.png>
                <h3>prawn 65</h3>
                <p>Prawn 65 is a flavorful and spicy Indian appetizer made with prawns marinated in a mix of aromatic spices, coated with a batter, and deep-fried to crispy perfection. It’s often garnished with curry leaves, green chilies, and served with a tangy dipping sauce or lemon wedges.</p>
            </div>
            <div class="menu-item">
                <img src=c:\Users\admin\OneDrive\Desktop\panner.png>
                <h3>panneer butter masala</h3>
                <p>Paneer Butter Masala is a rich and creamy North Indian curry made with soft paneer cubes simmered in a luscious tomato-based gravy, flavored with butter, aromatic spices, and a hint of cream. It’s a popular dish often served with naan or rice.</p>
            </div>
            <div class="menu-item">
                <img src="c:\Users\admin\OneDrive\Desktop\pasta.png">
                <h3>Italian pasta</h3>
                <p>
                    Italian pasta is a versatile and beloved dish made from durum wheat and water, shaped into various forms like spaghetti, penne, or fusilli. It is typically cooked al dente and served with a variety of sauces, such as tomato-based marinara, creamy Alfredo, or rich pesto, reflecting the diverse flavors of Italian cuisine</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Phone:986532144</p>
        <p>Email:javafoods@gmail.com</p>
        <p>Address: 123 Food Street, uptown Town,chennai</p>
    </section>
    <footer>
        <p>&copy; Java foods. All Rights Reserved.</p>
    </footer>
</body>
</html>


menu.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Java Foods</title>
    <style>
        body {
            background-color: cornsilk;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: grey;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: chocolate;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: grey;
        }
        section {
            padding: 20px;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
        }
        .menu-item {
            border: 1px solid silver;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: grey;
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Explore Our Dishes</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="menu-1.jpg" alt="Prawn 65">
                <h3>Prawn 65</h3>
                <p>A flavorful and spicy Indian appetizer made with marinated prawns, deep-fried to crispy perfection.</p>
            </div>
            <div class="menu-item">
                <img src="download.jpg" alt="Paneer Butter Masala">
                <h3>Paneer Butter Masala</h3>
                <p>A rich and creamy North Indian curry with soft paneer cubes in a buttery tomato-based gravy.</p>
            </div>
            <div class="menu-item">
                <img src="download (1).jpg" alt="Italian Pasta">
                <h3>Italian Pasta</h3>
                <p>Delicious pasta served with a variety of sauces, cooked to perfection for an authentic Italian experience.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; Java Foods. All Rights Reserved.</p>
        <p> designed and developed by:SAMEER SHARIFF M(212224220085)</p>
    </footer>
</body>
</html>

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Java Foods</title>
    <style>
        body {
            background-color: cornsilk;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: grey;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: chocolate;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: grey;
        }
        .welcome {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 50px;
        }
        .welcome h1 {
            font-size: 2.5rem;
        }
        .welcome p {
            font-size: 1.2rem;
            margin: 20px 0;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
            text-align: center;
        }
        .feature {
            margin: 10px;
            padding: 20px;
            border: 1px solid silver;
            border-radius: 5px;
            width: 300px;
        }
        footer {
            background-color: grey;
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Java Foods</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="welcome">
        <h1>Your Destination for Exquisite Cuisine</h1>
        <p>Java Foods offers a wide range of delicious dishes made from the freshest ingredients. Experience the taste of perfection with every bite!</p>
    </div>
    <section class="features">
        <div class="feature">
            <h3>Fresh Ingredients</h3>
            <p>We use only the freshest and highest-quality ingredients to prepare our dishes.</p>
        </div>
        <div class="feature">
            <h3>Family-Friendly</h3>
            <p>Enjoy a welcoming and comfortable atmosphere perfect for family gatherings.</p>
        </div>
        <div class="feature">
            <h3>Exceptional Service</h3>
            <p>Our friendly staff is here to make your dining experience unforgettable.</p>
        </div>
    </section>
    <footer>
        <p>&copy; Java Foods. All Rights Reserved.</p>
        <p> designed and developed by:SAMEER SHARIFF M(212224220085)</p>
    </footer>
</body>
</html>

contact.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Java Foods</title>
    <style>
        body {
            background-color: cornsilk;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: grey;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: chocolate;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: grey;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .contact-info {
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background-color: grey;
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Get in Touch</h2>
        <div class="contact-info">
            <p><strong>Phone:</strong> 986532144</p>
            <p><strong>Email:</strong> javafoods@gmail.com</p>
            <p><strong>Address:</strong> 123 Food Street, Uptown Town, Chennai</p>
            <p>We'd love to hear from you! Whether you have questions, feedback, or just want to say hi, feel free to reach out to us through any of the above channels.</p>
        </div>
    </section>
    <footer>
        <p>&copy; Java Foods. All Rights Reserved.</p>
        <p> designed and developed by:SAMEER SHARIFF M(212224220085)</p>
    </footer>
</body>
</html>

about.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Java Foods</title>
    <style>
        body {
            background-color: cornsilk;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: grey;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: chocolate;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: grey;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
            text-align: justify;
        }
        footer {
            background-color: grey;
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>About Java Foods</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Our Story</h2>
        <div class="content">
            <p>Welcome to Java Foods, where we bring together a love for fresh, delicious meals and a passion for hospitality. Established with the goal of creating memorable dining experiences, Java Foods is your go-to destination for a delightful culinary journey.</p>
            <p>Our team is committed to using the finest ingredients to prepare dishes that reflect authenticity and innovation. Whether you're here for a hearty meal, a light snack, or a sweet treat, our menu is designed to cater to every craving.</p>
            <p>We take pride in our warm and inviting atmosphere, perfect for family gatherings, friendly get-togethers, or a quiet meal on your own. At Java Foods, we believe food is more than just sustenance—it's an experience, and we are thrilled to share it with you.</p>
        </div>
    </section>
    <footer>
        <p>&copy; Java Foods. All Rights Reserved.</p>
        <p> designed and developed by: SAMEER SHARIFF M(212224220085)</p>
    </footer>
</body>
</html>


## OUTPUT:
![Screenshot 2025-05-15 094402](https://github.com/user-attachments/assets/df5ec6b2-e41f-48cd-9b65-30f54bed69cc)
![Screenshot 2025-05-15 094415](https://github.com/user-attachments/assets/de8f7d19-5763-460d-81cc-67ff07338f27)
![Screenshot 2025-05-15 094434](https://github.com/user-attachments/assets/9f76bdfb-6c51-4393-8e45-7cf1a486d6a9)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
