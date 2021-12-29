# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :

```

HOME PAGE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ABC Laptops and Services</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.jfif" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ABC Laptops and Services.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/about us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/icon2.jfif" alt="Building" />
          <div class="contenttext">
            A laptop, laptop computer, or notebook computer is a small, portable personal computer (PC) with a screen and alphanumeric keyboard. These typically have a clam shell form factor with the screen mounted on the inside of the upper lid and the keyboard on the inside of the lower lid, although 2-in-1 PCs with a detachable keyboard are often marketed as laptops or as having a laptop mode. Laptops are folded shut for transportation, and thus are suitable for mobile use.[1] Its name comes from lap, as it was deemed practical to be placed on a person's lap when being used. Today, laptops are used in a variety of settings, such as at work, in education, for playing games, web browsing, for personal multimedia, and general home computer use.
            <ul>
              <li>2 Years Warranty for Laptops,</li>
              <li>Branch all over India,</li>
              <li>Low Price.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 ABC Laptops and Services, Developed by Bharath.
      </div>
    </div>
  </body>
</html>

PRODUCT PAGE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ABC laptop and services.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.jpg" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">ABC laptop and services</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>OUR FIRST CLASS PRODUCTS</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/mac.jfif" alt="product image">
                  </div>
                  <div class="itemname">mac
                  </div>                
                  <div class="itemprice">price:2500000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/gaming laptop.jfif"  alt="product image">
                  </div>
                  <div class="itemname">gaming laptop
                  </div>
                  <div class="itemprice">price:1500000</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/hp laptop.jfif"  alt="product image">
                </div>
                <div class="itemname">hp laptop
                </div>
                <div class="itemprice">price:900000</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/acer laptop.jpg"  alt="product image">
              </div>
              <div class="itemname">acer laptop
              </div>
              <div class="itemprice">price:70000</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/cpu.jfif"  alt="product image">
            </div>
            <div class="itemname">cpu
            </div>
            <div class="itemprice">price:25000</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/monitor.jfif"  alt="product image">
          </div>
          <div class="itemname">monitor
          </div>
          <div class="itemprice">price:7000</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/joy stick.jfif"  alt="product image">
        </div>
        <div class="itemname">joystick
        </div>
        <div class="itemprice">price:1900</div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/keyboard.jfif"  alt="product image">
      </div>
      <div class="itemname">keyboard
      </div>
      <div class="itemprice">price:1500</div>
    </div> 
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/harddisk.jfif"  alt="product image">
      </div>
      <div class="itemname">harddrive
      </div>
      <div class="itemprice">price:3300</div>
    </div> 
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/charger.jpg"  alt="product image">
      </div>
      <div class="itemname">charger
      </div>
      <div class="itemprice">price:1500</div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/mousepad.jfif"  alt="product image">
      </div>
      <div class="itemname">Mouse pad
      </div>
      <div class="itemprice">price:500</div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/mouse.jpg"  alt="product image">
      </div>
      <div class="itemname">mouse
      </div>
      <div class="itemprice">price:700</div>
    </div>   
            </div>
          </div>
          </div> 
          <div class="footer">
            Copyright &#169; 2021 ABC laptops and services, Developed by V.BHARATH  
          </div>    
    </div>
    
  </body>
</html>

PEOPLE PAGE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ABC Laptops and Services</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.jfif" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ABC Laptops and Services.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/about us.html">Contact Us</a></div>
      </div>
      <div class="content">
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/one.jfif"  alt="product image">
      </div>
         <div class="itemname">Navnit Nakra</div>
         <div class="itemname">Manager</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/two.jfif"  alt="product image">
      </div>
         <div class="itemname">Jim Lanzone</div>
         <div class="itemname">Manager</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/three.jfif"  alt="product image">
      </div>
        <div class="itemname">Benedetto vigna</div>
        <div class="itemname">HR</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/four.jfif"  alt="product image">
      </div>
        <div class="itemname">Marc Llistosella</div>
        <div class="itemname">Employee</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/five.jfif"  alt="product image">
      </div>
        <div class="itemname">Sundar Pichai</div>
        <div class="itemname">Employee</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/six.jfif"  alt="product image">
      </div>
        <div class="itemname">Satya nadella</div>
        <div class="itemname">Employee</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 ABC laptop and services, Developed by V.BHARATH
      </div>
    </div>
  </body>
</html>

CONTACT US PAGE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ABC Laptops and Services</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.jfif" type="image/x-icon" />
  </head>
  
  <body>
    <div class="container">
      <div class="banner">ABC Laptops and Services.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/about us.html">Contact Us</a></div>
      </div>
      <img src=./img/loc.jfif alt="Building" />
      <img src=./img/qr.png alt="Building" />
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Address: 13, Shanthi nagar, annanagar, Chennai - 6000101
           <br>Phone:7037648951
           <br>Email-address:ABClap123@gmail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 ABC laptop and services, Developed by V.BHARATH
</div>
</div>
</body>
</html

css page:

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #d8ce47;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px rgb(230, 223, 223);
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/back.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #2d40e6;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #458eb0;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}

```
## OUTPUT:

### Home Page:

![output](images/homepages.png)

### PRODUCTS PAGE:

![label](images/product.png)

### PEOPLE PAGE:

![label](images/people.png)

### CONTACT US PAGE :

![label](images/contact.png)


### 

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
