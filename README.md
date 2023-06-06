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

### Home Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GET3D Private Limited</title>
    <link rel="stylesheet" href="layout.css" />
    <link rel="icon" href="logo.jpeg" type="image/x-icon" />
  </head>

  <body>
    
    <div class="container">
      
      
      <div class="banner">GET3D Private Limited</div>
    
      <div class="menu">
        <div class="menuitemselected"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="products.html">Product</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1><b>About Us<b></h1>
          
          <div class="contenttext">
           Welcome to GET3D Private Limited!<br><br>
           At GET3D Private Limited, we bring your ideas to life with cutting-edge technology and unparalleled precision.
           <br>As a leading provider of 3D printing services, we specialize in transforming your concepts into tangible, high-quality objects
           that push the boundaries of innovation.
            <br /><br><br>
           Services We Offer:
            <ul>
              <li><b>Prototyping:<b> Transform your designs into physical prototypes quickly and cost-effectively.</li>
              <li><br><b>Custom Manufacturing:<b> we offer custom manufacturing services work closely with you to understand your requirements</li>
              <li><br><b>Design Assistance:<b> Our team of skilled designers and engineers is ready to assist you in optimizing your 3D designs for printing.</li>
              <li><br><b>Artistic Creations:<b> Unleash your creativity with our artistic 3D printing services.</li>
              <li><br>Whether you're a sculptor, jewelry designer, or architect, we can help you bring your intricate and unique creations to life with stunning detail and precision. </li>  
            </ul>
                      </div>
        </div>
      </div>
      <div class="footer">
        Copyrights @ 2023 GET3D Private Limited  , Developed by SATHISH R
      </div>
    </div>
  </body>
</html>
```
### Product Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GET3D Private Limited</title>
    <link rel="stylesheet" href="layout.css" />
    <link rel="icon" href="logo.jpeg" type="image/x-icon" />
  </head>

  <body align="center">
    <div class="container">
      <div class="banner">GET YOUR DESIRED 3D MODELS</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitemselected"><a href="product.html">Products</a></div>  
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Top Selling Products</h1>
          <div class="productitems">

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="bird.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Bird Statue Model</div>
                  <div class="itemprice">Price:Rs.999</div>
                  <button>Buy now</button>
                  <button>Add to Cart</button>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="dollar.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Pedant_Butterfly_dollar</div>
                  <div class="itemprice">Price:Rs.1999</div>
                  <button >Buy now</button>
                  <button>Add to Cart</button>
                  

              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="eagle.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Eagle Statue</div>
                  <div class="itemprice">Price: Rs.1199</div>
                  <button>Buy now</button>
                  <button>Add to Cart</button>
              
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="ring2.jpeg"  alt="product image">
                </div>
                <div class="itemname">Engagement Ring Women</div>
                <div class="itemprice">Price: Rs.1299 </div>
                <button>Buy now</button>
                <button>Add to Cart</button>
            </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="gold.jpeg"  alt="product image">
              </div>
              <div class="itemname">Gold Printed Coin</div>
              <div class="itemprice">Price: Rs.699</div>
              <button>Buy now</button>
              <button>Add to Cart</button>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="vase.jpeg"  alt="product image">
            </div>
            <div class="itemname">Hand Vase</div>
            <div class="itemprice">Price: Rs.1799 </div>
            <button>Buy now</button>
            <button>Add to Cart</button>
        </div>

        <div class="productitem"> 
          <div class="itemimage">
          <img src="horse.jpeg"  alt="product image">
          </div>
          <div class="itemname">Horse Statue</div>
          <div class="itemprice">Price: Rs.1999</div>
          <button>Buy now</button>
          <button>Add to Cart</button>
      </div>

      <div class="productitem"> 
        <div class="itemimage">
        <img src="house1.jpeg"  alt="product image">
        </div>
        <div class="itemname">Constructed_House Design</div>
        <div class="itemprice">Price: Rs.5999 </div>
        <button>Buy now</button>
        <button>Add to Cart</button>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="lion.jpeg"  alt="product image">
      </div>
      <div class="itemname">Lion with Crown</div>
      <div class="itemprice">Price: Rs.2,990</div>
      <button>Buy now</button>
      <button>Add to Cart</button>
    </div>

    <div class="productitem"> 
       <div class="itemimage">
       <img src="mhouse.jpeg"  alt="product image">
       </div>
       <div class="itemname">Medieval House</div>
       <div class="itemprice">Price: Rs.3199 </div>
       <button>Buy now</button>
       <button>Add to Cart</button>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="ring.jpeg"  alt="product image">
    </div>
       <div class="itemname">Proposal Ring Women</div>
       <div class="itemprice">Price: Rs.1500</div>
       <button>Buy now</button>
       <button>Add to Cart</button>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="ring1.jpeg"  alt="product image">
     </div>
        <div class="itemname">Wedding Ring Women</div>
        <div class="itemprice">Price: Rs.2199 </div>
        <button>Buy now</button>
        <button>Add to Cart</button>
      </div>
    </div>
  </div>        
  </div>
    <div class="footer">
      Copyright @ 2023 GET3D Private Limited, Developed by SATHISH R
    </div>
  </div>
 </body>
</html>
```
### People Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GET3D Private Limited</title>
    <link rel="stylesheet" href="layout1.css"/>
    <link rel="icon" href="logo.jpeg" type="image/x-icon" />
  </head>

  <body >
    <div class="container">
      <div class="banner">OUR GLOBAL  PARTNERS</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="products.html">Product</a></div>  
        <div class="menuitemselected"><a href ="people.html"></a>People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div style="background-color:#afbae0"  class="peopleitem"> 
        <div class="peopleimage">
        <img src="Kristin-Mulherin.jpg"  alt="people image">
      </div>
         <div class="peoplename"><b>Kristin Mulherin President of Women in 3D Printing
           <br>
           President of Women in 3D Printing
         </div>
      </div>
      <div style="background-color:#afbae0;" class="peopleitem"> 
        <div  class="peopleimage">
        <img src="Blake_Essentium.jpg"  alt="people image">
      </div>
         <div  class="peoplename">Blake Teipel 
           <br>
           CEO and Co-founder of Essentium
         </div>
      </div>
      <div style="background-color:#afbae0" class="peopleitem"> 
        <div class="peopleimage">
        <img src="EastonLaChappelle.jpg"  alt="people image">
      </div>
         <div  class="peoplename">Easton LaChappelle<br>CEO of Unlimited Tomorrow </div>
      </div>
      <div style="background-color:#afbae0;" class="peopleitem"> 
        <div class="peopleimage">
        <img src="RedefineMeatCEO.jpg"  alt="peopleimage">
      </div>
         <div class="peoplename">Eshchar Ben-Shitrit<br> CEO and Co-Founder of Redefine Meat </div>
      </div>
      <div style="background-color:#afbae0;" class="peopleitem"> 
        <div class="peopleimage">
        <img src="shai_terem.jpg"  alt="people image">
      </div>
         <div class="peoplename">Shai Terem  <br>CEO of Markforged</div>
      </div>
      <div style="background-color:#afbae0;" class="peopleitem"> 
        <div class="peopleimage">
        <img src="Sherri-Monroe.jpg"  alt="people image">
      </div>
         <div class="peoplename">Sherri Monroe
            <br> Executive Director Of AMGTA </b></div>
      </div>
      <div class="footer">
        Copyrights @ 2023 GET3D Private Limited, Developed by SATHISH R
      </div>
    </div>
  </body>
</html>
```
### Contact Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GET3D PRIVATE LIMITED</title>
    <link rel="stylesheet" href="layout.css" />
    <link rel="icon" href="logo.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Feel Free to Contact Us</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="products.html">Product</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content" align="center">
        <b>Ready to turn your ideas into reality? Contact us today to discuss your project or request a quote.<br>
        Our team of experts is eager to assist you and provide tailored solutions that will elevate your designs to the next level.<br>
          Join the 3D printing revolution with GET3D Private Limited and experience the power of limitless possibilities!</b>

          <ul align="left" >
            
             
              <br>
              <li><b>Contact us through</b><br>
                <br>
              <b>Phone:</b>8778079453;7010716063<br></li>
                <br>
                <b>Telephone </b>: (345)222-1212<br>
                <br>
                <b>E-mail</b>:get3dprivate@gmail.com
              <br>
              <br>
              <br>
              <li>
                <b>Address:</b><br><br>

                Near Fortune towers<br>
                Kovilambakkam<br>
                CHENNAI<br>
            </li>

              <br>VERIFIED*
          </ul>    
        </div>
        <div class="footer">
          Copyrights @ 2023 GET3D Private Limited , BY SATHISH R
        </div>
    </div>
    </div>
    </div>
    
    </div>
  </body>
</html> 
```
### CSS LAYOUT
```
* {
  box-sizing: border-box;
  font-family:'Times New Roman', Times, serif;
}
body {
  background-color: #fefeff;
  color: #070707;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px #afbae0;
}

.banner {
  display: block;
  width: 100%;
  height: 500px;
  text-align: center;
  font-size: 65px;
  background-image: url("img.jpeg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 230px;
  color: aqua;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #afbae0;
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
  color: #080808;
}

.menuitem a {
  text-decoration: none;
  color: #080808;
}

.content {
  display: block;
  width: 100%;
  background-color: #afbae0;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: #afbae0;
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
  width: 24%;
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
  background-color: #afbae0;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #000000;
}
```
## OUTPUT:

### Home Page:
![output](home.png)

### Product Page:
![output](product.png)

### People Page:
![output](people.png)

### Contact Page:
![output](contact.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
