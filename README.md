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

home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">DailyObjects Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 DailyObjects Private Limited, Developed by Nijeesh NJ.
      </div>
    </div>
  </body>
</html>
```


product.html

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>DailyObjects</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>DailyObjects LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitem"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/battlecreek-coffee-roasters-rsnzc-8dVacs0-unsplash.jpg"  alt="product image">
                </div>
                <div class="itemname">Coffee powder</div>
                <div class="itemprice">Price: Rs.200</div>
            </div>
              <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/charlesdeluvio-1-nx1QR5dTE-unsplash.jpg"  alt="product image">
              </div>
              <div class="itemname">Rounded SunGlasses</div>
              <div class="itemprice">Price: Rs.1,500</div>
              </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/daniel-korpai-hbTKIbuMmBI-unsplash.jpg"  alt="product image">
            </div>
            <div class="itemname">Smart Watch</div>
            <div class="itemprice">Price: Rs.2,500</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/jakob-owens-O_bhy3TnSYU-unsplash.jpg"  alt="product image">
            </div>
            <div class="itemname">Travel Bag</div>
            <div class="itemprice">Price: Rs.2,000</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/joan-tran-reEySFadyJQ-unsplash.jpg"  alt="product image">
            </div>
            <div class="itemname">Thermo bottle</div>
            <div class="itemprice">Price: Rs.700</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/kiran-ck-LSNJ-pltdu8-unsplash.jpg"  alt="product image">
            </div>
            <div class="itemname">ANC HeadPhones</div>
            <div class="itemprice">Price: Rs.2,700</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/kuiye-chen-NuOGFo4PudE-unsplash.jpg"  alt="product image">
            </div>
            <div class="itemname">Earpodes</div>
            <div class="itemprice">Price: Rs.1,700</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/ruslan-bardash-4kTbAMRAHtQ-unsplash.jpg"  alt="product image">
            </div>
            <div class="itemname">Table Chair</div>
            <div class="itemprice">Price: Rs.1,245</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/mike-meyers-v8XaVfyo41Q-unsplash.jpg"  alt="product image">
            </div>
            <div class="itemname">Retro GameStation</div>
            <div class="itemprice">Price: Rs.3,500</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/oscar-ivan-esquivel-arteaga-ZtxED1cpB1E-unsplash.jpg"  alt="product image">
            </div>
            <div class="itemname">Keyboard Wireless Mouse</div>
            <div class="itemprice">Price: Rs.800</div>
          </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 DailyObjects Private Limited, Developed by Nijeesh NJ.
      </div>
    </div>
  </body>
</html>
```

people.html

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>DailyObjects</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>DailyObjects LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitem"><a href="/static/products.html"><b>Products</b></a></div>
        <div class="menuitemselected"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitem"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/pexels-andrea-piacquadio-733872.jpg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Emma (Chairman)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/pexels-andrea-piacquadio-774909.jpg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Charoline(Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/pexels-daniel-xavier-1239291.jpg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Sophia (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/pexels-hannah-nelson-1065084.jpg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Juliet(Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/pexels-justin-shaifer-1222271.jpg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Maddy Nelson (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/pexels-pixabay-220453.jpg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Max Mysterio (Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2021 DailyObjects Private Limited, Developed by Nijeesh NJ.
      </div>
    </div>
  </body>
</html>
```

contact.html


```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>DailyObjects Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>DailyObjects LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitem"><a href="/static/products.html"><b>Products</b></a></div>
        <div class="menuitem"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitemselected"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <body>
          <div class="content">
          <h1>&ensp;Contact Information</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:98, king street, Flyer Town, Texas, United States
                    </p>
                    <ul>
                        <br>
                        <li><b>&emsp;Phone:</b>&emsp;2387459648</li>
                        <br>
                        <li><b>&emsp;Shop owner no</b>:&emsp;9586456745</li>
                        <br>
                        <li><b>&emsp;Shop Manager Number:</b> 8975455185</li>
                        <br>
                        <li><b>&emsp;Email Id:</b>&emsp;royalreader74@gmail.com</li>
                        <br>
                        <li><b>&emsp;Alternate Email Id:</b>&emsp;royalreader89@gmail.com</li>
                        <br>
                    </ul>
                </div>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 DailyObjects Private Limited, Developed by Nijeesh NJ.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![Alt text](image-3.png)

### Product Page:

![Alt text](image-1.png)

![Alt text](image-2.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
