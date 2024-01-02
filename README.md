# Event Registration Web Application

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
create a html file and add the requirements to get the login.html


### Step 2:
and create a login.css page to view the page contents


### Step 3:
And also add the register.html to fill the firstname,lastname and further details.

### Step 4:
Add the background image, email and password

### Step 5:
Add the link in the code to the  web images  

### Step 6:

Validate the HTML and CSS code.

### Step 7:

Publish the website in the given URL.

## DESIGN:

## PROGRAM :
```
h.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <div class="navbar">
        <a href="h.html"><img src="https://www.ebid.net/images/logo_apr20@2x.png" alt="" id="logoimg" height="100px"></a>
        <div class="search-container">
            <form action="/search" method="get" id="FORUM">
               <input type="text" id="searchInput" placeholder="Search.." name="query">
               <button type="submit" onclick="search()">Search</button>
               <ul id="results"></ul>
            </form>
        </div>
        <a href="login.html"><button>Login</button></a>
        <a href="register.html"><button>Register</button></a>
    </div>
    <div id="section1">
        <p id="daily">Antique's</p>
        
    </div>

   

    <div id="text">
        <p id="one">Have you been seeing on eBid already ?</p>
        <p id="two">To pay your fees or ask questions</p>
        <div id="read">
            <div class="shop-now-box">
                <a href="read.html" class="ReadM">Read →</a>
            </div>
        </div>
    </div>

   
    <p id="PD">Popular Destination</p>

    <div id="devices">
        <div id="laptop">
            <a href="laptop1.html" class="AMZ" ><img src="https://i.ebayimg.com/images/g/kO4AAOSw8~xlPArk/s-l225.webp" alt=""></a>
            <p>$869.99</p>
        </div>
        <div id="intel">
            <a href="intel.html" class="INT"><img src="https://i.ebayimg.com/images/g/fpQAAOSwQRxlFHx5/s-l225.webp" ></a>
            <p>$379.99</p>

        </div>
        <div id="iphone">
            <a href="phone.html" class="Iphone"><img src="https://i.ebayimg.com/images/g/BuwAAOSwqudkb8F8/s-l225.webp"></a>
            <p>$814.99</p>
        </div>
        <div id="laptop2">
            <a href="laptop2.html" class="laptop2" ><img src="https://i.ebayimg.com/images/g/CUUAAOSwbiVlTFPu/s-l225.webp" alt=""></a>
            <p>$749.99</p>
        </div>
        <div id="laptop3">
            <a href="play.html" class="laptop3" ><img src="https://i.ebayimg.com/images/g/0EUAAOSw5hFlTphS/s-l225.jpg" alt=""></a>
            <p>$489.99</p>
        </div>


    </div>
    <div id="template">
        <p class="MC">More color to your</p>
        <p class="MC">cart in eBid Week</p>
        <p class="TA">And it's greener thanks to refurb tech</p>
        <p class="TA">and pre-loved luxury.</p>
         <div id="NT" style="display: flex;">
            <img src="https://i.ebayimg.com/images/g/bPgAAOSwXK5lUf70/s-l960.webp" alt="">
        </div>
        <div class="shop-now-box">
            <a href="#" class="shop-btn">Shop Circular →</a>
        </div>
       

    </div>

    <div id="footer">
        <img src="https://www.ebid.net/images/logo_apr20@2x.png" alt="" height="100px" id="flogo">
        <p class="BS">Buying and Selling Online </p>
        <p class="BS">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Since 1999</p>
    
        <div id="quicklinks">
            <ul id="QC">
                <p id="Quicklinks">Quick Links</p>
                <li><a href="register.html" class="Bla">Register</a></li>
                <li><a href="read.html" class="Bla">About eBid</a></li>
                <li><a href="" class="Bla">Buy on eBid</a></li>
                <li><a href="" class="Bla">Sell on eBid</a></li>
                <li><a href="" class="Bla">eBid Forums</a></li>
                <li><a href="" class="Bla">eBid Privacy and Policy</a></li>
            </ul>
        </div>
        <div id="aboutebid">
            <ul id="AE">
                <p id="ae">About Ebid</p>
                <li><a href="dsv.html" class="about">Company Info</a></li>
                <li><a href="" class="about">News</a></li>
                <li><a href="" class="about">Investors</a></li>
                <li><a href="" class="about">Careers</a></li>
                <li><a href="" class="about">Government Relations</a></li>
                <li><a href="" class="about">Policies</a></li>
                <li><a href="" class="about">Verified Rights Owner (VeRO) Program</a></li>
            </ul>
        </div>
        <div id="HelpContact">
            <ul id="HC">
                <p id="hc">Help & Contact</p>
                <li><a href="" class="Help">Seller Information Center</a></li>
                <li><a href="" class="Help">Contact us</a></li>
                <p id="SC">Stay Connected</p>
                <img src="https://ww2.freelogovectors.net/wp-content/uploads/2023/03/facebook-logo-new-2019-freelogovectors.net_.png" alt="" height="18px" width="25px"><a href="https://www.facebook.com/eBid.net/" class="Help">Facebook</a></a></li>
                <li><img src="https://ww2.freelogovectors.net/wp-content/uploads/2023/04/twitter-logo-01-freelogovectors.net_.png?lossy=1&resize=640%2C478&ssl=1" alt="" height="18px" width="25px"><a href="https://twitter.com/ebid?lang=en" class="Help">Twitter</a></li>
            </ul>
        </div>
        <p id="copyright">&copy; 2023 eBid. All rights reserved.</p>
    </div>
    
</body>
</html>

login.css

* {
	box-sizing: border-box;
	
}

body {
	background: #f3e0e2;
	background-image: url(space.jpg);
	background-repeat: no-repeat;
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	font-family: 'Montserrat', sans-serif;
	border-right: #eee;
	
}

h1 {
	font-weight: bold;
	font-size:40px;
	margin: 0;
}

p {
	font-size: 14px;
	font-weight: 100;
	line-height: 20px;
	letter-spacing: 0.5px;
	margin: 20px 0 30px;
}

span {
	font-size: 12px;
}

a {
	color: #333;
	font-size: 14px;
	text-decoration: none;
	margin: 15px 0;
}

button {
	border-radius: 20px;
	border: 1px solid #FF4B2B;
	background-color: #FF4B2B;
	color: #FFFFFF;
	font-size: 12px;
	font-weight: bold;
	padding: 12px 45px;
	letter-spacing: 1px;
	text-transform: uppercase;
	transition: transform 80ms ease-in;
}

form {
	background-color: #FFFFFF;
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
	padding: 0 50px;
	height: 100%;
	text-align: center;
}

input {
	background-color: #eee;
	border: none;
	padding: 12px 15px;
	margin: 8px 0;
	width: 100%;
}

.container {
	background-color: #fff;
	border-radius: 10px;
  	box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
	position: relative;
	overflow: hidden;
	width: 768px;
	max-width: 100%;
	min-height: 480px;
}

.form-container {
	position: absolute;
	top: 0;
	height: 100%;
}

.log-in-container {
	left: 0;
	width: 50%;
	z-index: 2;
}


.overlay-container {
	position: absolute;
	top: 0;
	left: 50%;
	width: 50%;
	height: 100%;
}


.overlay {
	background-image: url(900_300_3098_cover_evt.jpg);
	background-repeat: no-repeat;
	background-size: cover;
	background-position: 0 0;
	color: #FFFFFF;
	position: relative;
	left: -100%;
	height: 100%;
	width: 200%;
}

.overlay-panel {
	position: absolute;
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
	padding: 0 40px;
	text-align: center;
	top: 0;
	height: 100%;
	width: 50%;
}

.overlay-right {
	right: 0;
}
```


## OUTPUT:
login page:
![image](https://github.com/PYNAMVINODH/event-registration/assets/145742678/395cf0d6-6a35-43cd-a42a-fc53a0565db8)

Register page:
![image](https://github.com/PYNAMVINODH/event-registration/assets/145742678/d341426c-aa31-41ca-a471-ab1c88f71cf9)

Opening page:
![image](https://github.com/PYNAMVINODH/event-registration/assets/145742678/a8fc0fe7-3dce-4d72-a489-409c05c2cabe)






## Result:
Html Page is created succesfully 
