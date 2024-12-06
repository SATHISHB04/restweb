# Ex.07 Restaurant Website
## Date:06.12.2024

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
```
home.html

home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Lemon</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
    }
    .header {
      background-color: #dfe6e9;
      text-align: center;
      padding: 20px;
    }
    .header img {
      width: 50px;
      vertical-align: middle;
    }
    .header h1 {
      display: inline;
      margin-left: 10px;
    }
    .navbar {
      display: flex;
      justify-content: center;
      background-color: #2d3436;
      padding: 10px;
    }
    .navbar a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background-image: url('Black and White Modern Food New Menu Instagram Post.png'); /* Replace with your image path */
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 50px 20px;
    }
    .hero h2 {
      font-size: 36px;
      margin: 0;
    }
    .hero p {
      margin-top: 10px;
      font-size: 18px;
    }
    .container {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      padding: 20px;
    }
    .card {
      background-color: #ffeaa7;
      width: 250px; /* Adjusted for smaller card size */
      margin: 10px;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
      text-align: center;
    }
    .card img {
      width: 100%;
      max-width: 150px; /* Smaller image size */
      height: auto;
      border-radius: 8px;
    }
    .card h3 {
      margin-top: 10px;
    }
    .card p {
      font-size: 14px;
      margin: 10px 0;
    }
    .card a {
      color: #2d3436;
      text-decoration: none;
      font-weight: bold;
    }
    .card a:hover {
      color: #00cec9;
    }
    .footer {
      background-color: #2d3436;
      color: white;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }
    .footer a {
      color: #00cec9;
      text-decoration: none;
    }
  </style>
</head>
<body>
  

  <div class="navbar">
    <a href="#home">Home</a>
    <a href="#menu">Products</a>
    <a href="#admin">Administration</a>
    <a href="#contact">Contact</a>
  </div>

  <div class="hero">
    <h2>30% Off This Weekend</h2>
    <p>Enjoy exclusive discounts on our delicious menu items this weekend!</p>
  </div>

  <div class="container">
    <div class="card">
      <img src="Black and White Modern Food New Menu Instagram Post.png" alt="Menu Image">
      <h3>Our New Menu</h3>
      <p>Discover our new menu with exciting dishes you'll love. Fresh and flavorful!</p>
      <a href="#menu">See our new menu</a>
    </div>
    <div class="card">
      <img src="Screenshot (58).png" alt="Table Booking">
      <h3>Book a Table</h3>
      <p>Reserve your spot and enjoy a delightful dining experience with us.</p>
      <a href="#booking">Book your table now</a>
    </div>
    <div class="card">
      <img src="Beige Aesthetic Opening Hours Instagram Story.png" alt="Opening Hours">
      <h3>Opening Hours</h3>
      <p>Mon - Fri: 2 PM - 10 PM<br>Sat: 2 PM - 11 PM<br>Sun: 2 PM - 9 PM</p>
    </div>
  </div>

  <div class="footer">
    <p>Designed and Developed by <a href="#">SATHISH.B (24900077)</a></p>
  </div>

</body>
</html>
adminstration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb Members</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }

        /* Add background image */
        body {
            background-image: url('Green Wateroclor Leaf Linktree Background.png'); /* Replace 'background-image.jpg' with the path to your background image */
            background-size: cover; /* Make the background cover the entire screen */
            background-position: center; /* Center the image */
            background-repeat: no-repeat; /* Prevent the image from repeating */
        }

        #nav {
            background-color: rgb(179, 229, 245);
            color: #000000;
            padding: 15px;
            opacity: 0.8; /* Add some transparency to allow background image to be visible */
        }

        li, .heading1, ul {
            display: inline;
        }

        ul {
            margin-left: 45%;
        }

        li {
            color: lightblue;
        }

        li:hover {
            color: #fafafa;
            cursor: pointer;
        }

        input {
            width: 60%;
            padding: 15px;
        }

        a {
            color: teal;
            text-decoration: none;
        }

        a:hover {
            color: #ffffff;
            cursor: pointer;
        }

        .heading2 {
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color: #63b8c0;
        }

        .bottomdiv {
            background-color: aqua;
            color: black;
            text-align: center;
            position: relative;
            display: block;
            margin-top: 0.7px;
        }

        img {
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding: 15px;
        }

        .person {
            margin: 150px;
            text-align: center;
        }

        b, p {
            color: black;
            text-align: center;
        }

        .quote {
            font-style: italic;
            color: #888888;
            text-align: center;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">FOODIE..!</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li3"> 
                        <a href="administration.html" target="_blank">Administration  |</a> <!-- Fixed the link here -->
                    </li>
                    <li class="li4"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
        </nav>
    </div>

    <h1 class="heading2">Members</h1>
    <table class="person">
        <tr>
            <td>
                <img src="Divya Bharathi.jpeg" width="100" height="160">
            </td>
            <td>
                <img src="nazhiriya.jpg" width="100" height="160">
            </td>
            <td>
                <img src="saipalavi.jpg" width="100" height="160">
            </td>
            <td>
                <img src="samantha.jpg" width="100" height="160">
            </td>
            <td>
                <img src="janvi.jpeg" width="100" height="160">
            </td>
            <td>
                <img src="sreeleela.jpg" width="100" height="160">
            </td>
        </tr>
        <tr>
            <td>
                <b>Divya</b>
                <p>Co-Founder</p>
            </td>
            <td>
                <b>Nani</b>
                <p>Asst. Director</p>
            </td>
            <td>
                <b>Sai Pallavi</b>
                <p>Marketing Director</p>
            </td>
            <td>
                <b>Samantha</b>
                <p>Head Chef</p>
            </td>
            <td>
                <b>Janvi</b>
                <p>Founder</p>
            </td>
            <td>
                <b>Sreeleela</b>
                <p>Owner</p>
            </td>
        </tr>
    </table>

    <!-- Quotes section for restaurant -->
    <div class="quote">
        <p>"Good food is good mood."</p>
        <p>"Eating is a necessity, but cooking is an art."</p>
        <p>"There is no sincerer love than the love of food."</p>
    </div>

    <div class="bottomdiv">
        <p>Copyrights @2024 and Developed BY SATHISH.B</p>
    </div>
</body>
</html>
product.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Indian Menu</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }

        body {
            background-image: url('Beige Simple Food Catering Instagram Post.png'); /* Replace with a traditional Indian-themed image */
            background-size: cover;
            background-position: center;
            color: #333;
            padding: 0;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
        }

        #nav {
            background-color: rgb(132, 200, 223);
            color: pink;
            padding: 30px;
            width: 100%;
            box-sizing: border-box;
            position: sticky;
            top: 0;
        }

        #nav h1 {
            display: inline;
            font-size: 40px;
        }

        ul {
            list-style: none;
            padding: 10px;
            text-align: center;
        }

        li {
            display: inline;
            color: wheat;
            margin: 0 20px;
            font-size: 18px;
        }

        li:hover {
            color: white;
            cursor: pointer;
        }

        .heading2 {
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color: black;
            font-size: 32px;
            width: 100%;
        }

        .product {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); /* Automatically adjusts the grid to fit the screen */
            gap: 20px;
            padding: 30px;
            width: 100%;
            box-sizing: border-box;
        }

        .box {
            border: 2px solid wheat;
            background-color: rgb(255, 224, 254);
            cursor: pointer;
            padding: 10px;
            text-align: center;
            border-radius: 15px;
            position: relative;
            overflow: hidden;
        }

        .box::before {
            content: "";
            display: block;
            padding-top: 133.33%; /* 3:4 aspect ratio (3 / 4 = 0.75 = 75% padding-top) */
        }

        .box img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover; /* Ensures the image covers the box without distorting */
            border-radius: 10px;
        }

        a {
            color: #062d41;
            text-decoration: none;
        }

        a:hover {
            color: rgba(228, 76, 76, 0.986);
            cursor: pointer;
        }

        p {
            color: brown;
            text-align: center;
            font-size: 16px;
        }

        h1 {
            color: black;
            text-align: center;
        }

        .bottomdiv {
            background-color: aqua;
            color: black;
            text-align: center;
            padding: 20px;
            position: relative;
            display: block;
            width: 100%;
            box-sizing: border-box;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <div class="header">
        <nav id="nav">
            <h1 class="heading1">SATHISH.B (24900077)</h1>
            <ul>
                <li><a href="home.html" target="_blank">Home</a></li>
                <li><a href="product.html" target="_blank">Product</a></li>
                <li><a href="adminstration.html" target="_blank">administration</a></li>
                <li><a href="contact.html" target="_blank">Contact</a></li>
            </ul>
        </nav>
    </div>

    <h1 class="heading2">People</h1>

    <div class="product">
        <!-- Food Items (Images remain unchanged as per your requirement) -->
        <div class="box">
            <img src="Yellow Food Promotion New Indian Restaurant Menu.png" alt="Biryani">
            <h1>Hyderabadi Biryani</h1>
            <p>A flavorful rice dish made with spiced meat, saffron, and basmati rice, served with raita.</p>
        </div>
        <div class="box">
            <img src="Colourful Black and Yellow Indian Food Promotion Instagram Story.png" alt="Samosa">
            <h1>Samosa</h1>
            <p>Fried pastry pockets filled with spicy potato and peas, served with tamarind chutney.</p>
        </div>
        <div class="box">
            <img src="Yellow And Brown Colourful Gulab Jamun Recipe Instagram Post.png" alt="Gulab Jamun">
            <h1>Gulab Jamun</h1>
            <p>A popular Indian dessert made of deep-fried dough balls soaked in a sugary syrup.</p>
        </div>
        <div class="box">
            <img src="Orange and Yellow Chicken Tikka Masala Weekend Offer Instagram Post.png" alt="Butter Chicken">
            <h1>Butter Chicken</h1>
            <p>Succulent chicken cooked in a rich and creamy tomato-based sauce.</p>
        </div>
        <div class="box">
            <img src="Orange and Black Bold Paneer Tikka Restaurant Instagram Post.png" alt="Paneer Tikka">
            <h1>Paneer Tikka</h1>
            <p>Grilled cottage cheese marinated with spices, served with mint chutney.</p>
        </div>
        <div class="box">
            <img src="black white funny simple restaurant food menu.png" alt="Masala Dosa">
            <h1>Masala Dosa</h1>
            <p>Crispy rice crepes stuffed with spiced potatoes, served with sambar and coconut chutney.</p>
        </div>
        <div class="box">
            <img src="1.png" alt="Chole Bhature">
            <h1>Chole Bhature</h1>
            <p>Fried bread served with spicy chickpea curry, a popular North Indian dish.</p>
        </div>
        <div class="box">
            <img src="Black and Yellow Street Foods of Indian YouTube Thumbnail.png" alt="Pani Puri">
            <h1>Pani Puri</h1>
            <p>Crispy puris filled with spicy tamarind water, potatoes, and chickpeas.</p>
        </div>
        <div class="box">
            <img src="White And Brown Minimalist Roasted Chicken Instagram Post.png" alt="Tandoori Chicken">
            <h1>Tandoori Chicken</h1>
            <p>Spiced chicken cooked in a traditional tandoor oven, served with naan.</p>
        </div>
        <div class="box">
            <img src="Yellow Food Promotion New Indian Restaurant Menu (1).png" alt="Briyani">
            <h1>Briyani</h1>
            <p>A flavorful lamb curry made with aromatic spices and a rich, red sauce.</p>
        </div>
        <div class="box">
            <img src="Orange and White Bold Restaurant Instagram Post.png" alt="Aloo Paratha">
            <h1>Aloo Paratha</h1>
            <p>Flatbread stuffed with spiced mashed potatoes, typically served with yogurt and pickle.</p>
        </div>
        <div class="box">
            <img src="Brown and White Modern Playful Indian Beverage Sale Instagram Story.png" alt="Lassi">
            <h1>Lassi</h1>
            <p>A refreshing yogurt-based drink, often served sweet or salty.</p>
        </div>
    </div>

    <div class="bottomdiv">
        <b>&copy; 2024 Indian Flavors Restaurant | Developed by SATHISH.B (24900077)</b>
    </div>

</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb Contact</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        body {
            background-image: url('restweb.png');
            background-size: cover;
            color: #000;
        }
        #nav {
            background-color: rgba(240, 149, 191, 0.842);
            color: #000000;
            padding: 15px;
            position: sticky;
            top: 0;
            width: 100%;
        }
        ul {
            margin: 0;
            padding: 0;
            text-align: center;
        }
        li {
            display: inline;
            margin: 0 15px;
        }
        li a {
            color: #074565;
            text-decoration: none;
        }
        li a:hover {
            color: white;
        }
        .heading1 {
            font-size: 32px;
            color: #000;
        }
        .heading2 {
            padding-top: 100px;
            text-align: center;
            color: #c00000;
            font-size: 32px;
        }
        .contact, .queries {
            margin: 40px auto;
            width: 60%;
            text-align: center;
        }
        table {
            width: 100%;
            border-spacing: 10px;
            margin: 20px 0;
        }
        .table1 td, .table2 td {
            padding: 10px;
            font-size: 18px;
            text-align: left;
        }
        .table1 {
            background-color: rgba(236, 241, 247, 0.801);
        }
        .table2 {
            background-color: rgb(187, 208, 219);
            border-radius: 5px;
            border-style: dotted;
            border-color: rgb(125, 199, 213);
        }
        input[type="text"], input[type="email"] {
            width: 80%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            background-color: darkcyan;
            color: #000000;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #00a4a2;
        }
        .bottomdiv {
            background-color: aqua;
            color: #000000;
            text-align: center;
            padding: 20px;
            position: relative;
            width: 100%;
            margin-top: 30px;
        }
        .image-container {
            text-align: center;
            margin: 20px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .image-with-text {
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 20px 0;
        }
        .image-with-text img {
            max-width: 40%;
            margin-right: 20px;
        }
        .image-with-text div {
            max-width: 50%;
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">FOODIE..!</h1>
            <ul>
                <li><a href="home.html" target="_blank">Home |</a></li>
                <li><a href="product.html" target="_blank">Products |</a></li>
                <li><a href="adminstration.html" target="_blank">Administration |</a></li>
                <li><a href="contact.html" target="_blank">Contact</a></li>
            </ul>
        </nav>
    </div>

    <!-- Contact Us Section -->
    <h1 class="heading2">CONTACT US</h1>

    <div>
        <h3>Our Location</h3>
        <p>We are located in Chennai, near Tambaram. Visit us to get the best services!</p>
    </div>

    <!-- Contact Information Table -->
    <div class="contact">
        <table cellpadding="15px" cellspacing="15px" class="table1">
            <tr>
                <td>ADDRESS :</td>
                <td>Chennai</td>
            </tr>
            <tr>
                <td>LANDMARK :</td>
                <td>Near Tambaram</td>
            </tr>
            <tr>
                <td>EMAIL :</td>
                <td>sasi@gmail.com</td>
            </tr>
            <tr>
                <td>PHONE :</td>
                <td>8015061628</td>
            </tr>
        </table>
    </div>

    <!-- Queries Section -->
    <h2 class="heading3">QUERIES</h2>
    <div class="queries">
        <table cellpadding="15px" cellspacing="15px" class="table2">
            <tr>
                <td>NAME :</td>
                <td><input type="text" placeholder="Enter your name"></td>
            </tr>
            <tr>
                <td>EMAIL :</td>
                <td><input type="email" placeholder="Enter your E-mail"></td>
            </tr>
            <tr>
                <td>Your Query :</td>
                <td><input type="text" placeholder="Enter your Queries"></td>
            </tr>
            <tr>
                <td colspan="2">
                    <input type="submit" value="Submit">
                </td>
            </tr>
        </table>
    </div>

    <!-- Footer Section -->
    <div class="bottomdiv">
        <p>&copy; 2024 and Developed by Sathish (24900077)</p>
    </div>

</body>
</html>
```



## OUTPUT:
![alt text](<Screenshot (64).png>)
![alt text](<Screenshot (65).png>)
![alt text](<Screenshot (66).png>)
![alt text](<Screenshot (67).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
