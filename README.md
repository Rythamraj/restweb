# Ex.06 Restaurant Website
## Date: 26/12/2025

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
'''
restaurant.html

<html>
    <head>
        <title> FRESH & FLAVOUR</title>
         <link href="style.css" rel="stylesheet">
    </head> 

    <body>
            <h2 class = "name"> FRESH & FLAVOUR</h2>

        <div class="logo">
            <img src="logo.png">
        </div>
        <hr>

       <div class="items">
          <a href="restaurant.html">HOME -</a>
           <a href="menu.html">MENU -</a>
          <a href="admin.html">ADMINISTRATION -</a>
          <a href="contact.html">CONTACT</a>
       </div> 
        </body>
        <footer>
            <p>&copy;Rytham Raj(25012528)</p>
        </footer>
 
</html>

style.css

body{
    background-image:url(bg_res1.jpg);
    position: absolute;
    background-size: cover;
    background-repeat: no-repeat;
    bottom: 80px;
}

.logo img
{
    width: 330px;
    height: auto;
    position: absolute;
    top: -370px;
    left: 1620px;
}

h1{
    font-size: 50px;
    font-weight: bolder;
    position: absolute;
    top: -500px;
    left: 450px;
}

h2{
    font-size:160px;
    font-weight: bold;
    position: relative;
    top: -300px;
    left: 12px;
    text-shadow: 3px 3px 0px goldenrod;
    font-style: italic;
    letter-spacing: 3px;
    border-bottom: 20px ;
}

p{
    font-size: 35px;
    font-weight: lighter;
    position: relative;
    left: 12px;
}
hr{
    color: maroon;
    position: relative;
    bottom: 380px;
   
}
.items{
        font-weight: bold;
    font-size: 35px;
    position: relative;
    left: 440px;
    top: -350px;
    letter-spacing: 3px;
    word-spacing: 6px;
    border-bottom: 100px;
    background-color: rgb(224, 224, 172);
    display: inline;    
}
.items a{
    text-decoration: none;
    color: black;
}
footer p{
    text-align: center;
    color: brown;
    background: gainsboro;
    margin-bottom: 1%;
    top: 40px;
    width:1950px;
}

menu.html

<html>
    <head>
        <title>Menu</title>
        <link href="menu.css" rel="stylesheet">
    </head>

            
    <body>

      <h2 class = "name">MENU</h2>
        
        <div class="items">
          <a href="restaurant.html">HOME -</a>
           <a href="menu.html">MENU -</a>
          <a href="admin.html">ADMINISTRATION -</a>
          <a href="contact.html">CONTACT</a>
       </div> 

       <div class="menuf">
        <div class="food">
            <img src="Briyani.jpg">
                <h3>Chicken Briyani</h3>
                <h4>Price=$35</h4>
            </div>
            <div class="food">
                <img src="kothuparotta.jpg">
                <h3>Kothu Parotta</h3>
                <h4> Price=$28</h4>
            </div>
            <div class="food">
                <img src="Whole Tandoori Chicken.jpg">
                <h3>Tandoori Chicken</h3>
                <h4> Price=$48</h4>
            </div>
            <div class="food">
                <img src="Leaf.jpg">
                <h3>Chicken Leaf Parotta</h3>
                <h4> Price=$30</h4>
            </div>
            <div class="food">
                <img src="Dragon Chicken.jpg">
                <h3>Dragon Chicken</h3>
                <h4> Price=$39</h4>
            </div>
            <div class="food">
                <img src="parotta.jpg">
                <h3>Parotta</h3>
                <h4>Price=$10</h4>
            </div>
       </div>

    </body>
    <footer>
            <p>&copy;Rytham Raj(25012528)</p>
        </footer>
</html>

menu.css

body{
    background-image:url(bg_res1.jpg);
    position: absolute;
    background-size: cover;
    background-repeat: no-repeat;
    bottom: 80px;
    
}
h2
{
    
    font-weight: bold;
    font-size: 130px;
    position: relative;
    left: 200px;
    top: 160px;
    letter-spacing: 10px;
    text-shadow: 3px 3px 0px goldenrod;

}

.items{
        font-weight: bold;
    font-size: 35px;
    position: relative;
    left: 980px;
    top: -90px;
    letter-spacing: 3px;
    word-spacing: 6px;
    background-color: rgb(224, 224, 172);
}
.items a{
    text-decoration: none;
    color: black;
}

.menuf {
    display: flex;
    gap: 35px;
    width: 150%;
    margin: 100px;
}

.food {
    background-color:rgb(224, 224, 172);
    padding: 36px;
    text-align: center;
    border-radius: 8px;
    
}
.food img {
    width: 202px;
    height: 240px;
    object-fit: cover;
}

footer p{
    text-align: center;
    color: brown;
    background: gainsboro;
    margin-bottom: 1%;
    top: 40px;
    width:1950px;
    font-size: 30px;
}

admin.html

<html>
    <head>
        <title>Menu</title>
        <link href="admin.css" rel="stylesheet">
    </head>

            
    <body>

      <h2 class = "name">ADMINISTRATION TEAM</h2>
        
        <div class="items">
          <a href="restaurant.html">HOME -</a>
           <a href="menu.html">MENU -</a>
          <a href="admin.html">ADMINISTRATION -</a>
          <a href="contact.html">CONTACT</a>
       </div> 

       <div class="Admin">
        <div class="Position">
            <img src="ryth.jpeg"restweb>
                <h3>RYTHAM RAJ</h3>
                <h4>CEO</h4>
            </div>
            <div class="Position">
                <img src="Mrunal.jpg">
                <h3>MURNAL THAKUR</h3>
                <h4>CHAIR PERSON</h4>
            </div>
            <div class="Position">
                <img src="dq.jpg">
                <h3>DULQUAR SALMAN</h3>
                <h4>OPERATION MANAGER</h4>
            </div>
            <div class="Position">
                <img src="RASSHI.jpg">
                <h3>RAASHI KHANNA</h3>
                <h4>HR MANAGER</h4>
            </div>
            <div class="Position">
                <img src="sandy.jpg">
                <h3>SANTHANAM</h3>
                <h4>EXECUTIVE CHEF</h4>
            </div>
            <div class="Position">
                <img src="sam.jpg">
                <h3>SAMANTHA</h3>
                <h4>CUSTOMER SERVICE MANAGER</h4>
            </div>
       </div>

    </body>
    <footer>
            <p>&copy;Rytham Raj(25012528)</p>
        </footer>
</html>

admin.css

body{
    background-image:url(bg_res1.jpg);
    position: absolute;
    background-size: cover;
    background-repeat: no-repeat;
    bottom: 80px;
    
}
h2
{
    
    font-weight: bold;
    font-size: 120px;
    position: relative;
    left: 100px;
    top: 200px;
    letter-spacing: 10px;
    text-shadow: 3px 3px 0px goldenrod;

}

.items{
        font-weight: bold;
    font-size: 35px;
    position: relative;
    left: 980px;
    top: -80px;
    letter-spacing: 3px;
    word-spacing: 6px;
    background-color: rgb(224, 224, 172);
    display: inline;
}
.items a{
    text-decoration: none;
    color: black;
}

.Admin {
    display: flex;
    gap: 35px;
    width: 150%;
    margin: 100px;
}

.Position {
    background-color:rgb(232, 232, 161);
    padding: 15px;
    text-align: center;
    border-radius: 8px;
}
.Position img {
    width: 230px;
    height: 300px;
    object-fit: cover;
}
footer p{
    text-align: center;
    color: brown;
    background: gainsboro;
    margin-bottom: 1%;
    top: 40px;
    width:1950px;
    font-size: 30px;
}

contact.html

<html>
    <head>
        <title>CONTACT</title>
        <link href="contact.css" rel="stylesheet">
    </head>
    <body>
    <h1>CONTACT</h1>
      <div class="items">
          <a href="restaurant.html">HOME -</a>
           <a href="menu.html">MENU -</a>
          <a href="admin.html">ADMINISTRATION -</a>
          <a href="contact.html">CONTACT</a>
       </div> 
 
    <h2><b>Visit us at:</b></h2> 
    <p>Place, Park Lane, London W1J 7DR</p>
    <h2><b>Phone:</b></h2>
    <p>+44 (0)20 7499 0888</p>
    <h2><b>Email:</b></h2>
    <p>freshflavour1826@gmail.com</p>
    </body>
    <footer>
            <p>&copy;Rytham Raj(25012528)</p>
        </footer>


</html>

contact.css

body{
    background-image:url(bg.jpg);
    position: absolute;
    background-size: cover;
    background-repeat: no-repeat;
    bottom: 80px;
    
}
h1
{
    
    font-weight: bold;
    font-size: 120px;
    position: relative;
    left: 100px;
    top: 130px;
    letter-spacing: 10px;
    text-shadow: 3px 3px 0px goldenrod;

}

.items{
        font-weight: bold;
    font-size: 35px;
    position: relative;
    left: 980px;
    top: -150px;
    letter-spacing: 3px;
    word-spacing: 6px;
    background-color: rgb(224, 224, 172);;
}
.items a{
    text-decoration: none;
    color: black;
}

h2{
    text-align: left;
    font-style: oblique;
    font-size: 50px;
    color: rgb(51, 115, 145);
    position: relative;
    text-shadow: 3px 3px 0px lightblue;

}
p{
    text-align: left;
    font-family: 'Times New Roman', Times, serif;
    color: rgb(95, 43, 87);
    font-size: 30px;
    display: inline;
    text-shadow: 2px 1px 0px rgb(177, 96, 165);
    position:relative;
    bottom: 40px;


}
footer p{
    text-align: center;
    color: brown;
    background: gainsboro;
    margin-bottom: 1%;
    top: 40px;
    width:1950px;
    display: block;
}

```

## OUTPUT:

restweb/home.png
restweb/menu.png
restweb/admin.png
restweb/contact.png


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
