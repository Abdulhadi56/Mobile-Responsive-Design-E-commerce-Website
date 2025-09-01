# Mobile-Responsive-Design-E-commerce-Website
I just added one more file to it, which is mobileResponsive.css, it's code is available below, last file of code, and also available in ZIP Folder

//index.html page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>eCommerce Homepage</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link rel="stylesheet" href="myStyle.css">
  
</head>
<body>
  <!-- Main Navigation -->
  <div class="navbar">
    <div class="brand">
      <i class="fa-solid fa-bag-shopping"></i>
      <span>Brand</span>
    </div>
    <div class="search-bar">
      <input type="text" placeholder="Search">
      <select>
        <option>All category</option>
        <option>Electronics</option>
        <option>Fashion</option>
        <option>Mobiles</option>
      </select>
      <button>Search</button>
    </div>
    <div class="nav-icons">
      <div class="icon"><i class="fa-solid fa-user"></i><span>Profile</span></div>
      <div class="icon"><i class="fa-solid fa-message"></i><span>Message</span></div>
      <div class="icon"><i class="fa-solid fa-heart"></i><span>Orders</span></div>
      <div class="icon"><i class="fa-solid fa-cart-shopping"></i><span>My cart</span></div>
    </div>
  </div>

  <!-- Top Navigation -->
  <div class="top-navbar">
    <div class="top-left">
      <i class="fa-solid fa-bars"></i>
      <span>All category</span>
      <a href="#">Hot offers</a>
      <a href="#">Gift boxes</a>
      <a href="#">Projects</a>
      <a href="#">Menu item</a>
      <a href="#">Help <i class="fa-solid fa-chevron-down small-icon"></i></a>
    </div>
    <div class="top-right">
      <span>English, USD <i class="fa-solid fa-chevron-down small-icon"></i></span>
      <div class="flag-dropdown">
        <span id="selected-flag">
          Ship to <img src="https://flagcdn.com/w40/de.png" alt="Germany Flag" class="flag-icon">
          <i class="fa-solid fa-chevron-down small-icon"></i>
        </span>
        <div class="flag-options" id="flag-options">
          <div data-src="https://flagcdn.com/w40/de.png">Germany</div>
          <div data-src="https://flagcdn.com/w40/pk.png">Pakistan</div>
          <div data-src="https://flagcdn.com/w40/us.png">USA</div>
          <div data-src="https://flagcdn.com/w40/in.png">India</div>
          <div data-src="https://flagcdn.com/w40/gb.png">UK</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Promo Section -->
  <div class="promo-section">
    <div class="promo-categories">
      <ul>
        <li class="active">Automobiles</li>
        <li>Clothes and wear</li>
        <li>Home interiors</li>
        <li>Computer and tech</li>
        <li>Tools, equipments</li>
        <li>Sports and outdoor</li>
        <li>Animal and pets</li>
        <li>Machinery tools</li>
        <li>More category</li>
      </ul>
    </div>

    <div class="promo-banner" style="background-image: url('WhatsApp\ Image\ 2025-08-07\ at\ 7.14.25\ PM.jpeg');">
      <h2>Latest trending<br><strong>Electronic items</strong></h2>
      <button>Learn more</button>
    </div>

    <div class="promo-right">
      <div class="login-box">
        <div class="user-info">
          <i class="fa-solid fa-user-circle"></i>
          <div>
            <p>Hi, user</p>
            <p>let's get started</p>
          </div>
        </div>
        <button class="join-btn">Join now</button>
        <button class="login-btn">Log in</button>
      </div>

      <div class="orange-box">Get US $10 off<br>with a new supplier</div>
      <div class="blue-box">Send quotes with<br>supplier preferences</div>
    </div>
  </div>

  <!-- Deals and Offers Section -->
  <div class="deals-section">
    <div class="deals-left">
      <h3>Deals and offers</h3>
      <p>Hygiene equipments</p>
      <div class="timer">
      </div>
    </div>
    <div class="deals-content">
      <div class="deals-grid">
        <div class="deal-item">
          <div class="deal-image">
            <img src="watch5.jpeg" alt="Smart watches">
          </div>
          <h4>Smart watches</h4>
          <div class="discount">-25%</div>
        </div>
        <div class="deal-item">
          <div class="deal-image">
            <img src="mobilePhone5.png" alt="Laptops">
          </div>
          <h4>Laptops</h4>
          <div class="discount">-15%</div>
        </div>
        <div class="deal-item">
          <div class="deal-image">
            <img src="camera1.png" alt="GoPro cameras">
          </div>
          <h4>GoPro cameras</h4>
          <div class="discount">-40%</div>
        </div>
        <div class="deal-item">
          <div class="deal-image">
            <img src="gamingSet1.png" alt="Headphones">
          </div>
          <h4>Headphones</h4>
          <div class="discount">-25%</div>
        </div>
        <div class="deal-item">
          <div class="deal-image">
            <img src="mobilePhone2.png" alt="Canon cameras">
          </div>
          <h4>Canon cameras</h4>
          <div class="discount">-25%</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Home and Outdoor Section -->
  <div class="product-section">
    <div class="section-left">
      <div class="section-header">
        <h3>Home and outdoor</h3>
        <button class="source-btn">Source now</button>
      </div>
      <div class="section-image">
        <img src="HomeMaterials.webp" alt="HomeMaterials" width="100px" height="100px">
      </div>
    </div>
    <div class="section-content">
      <div class="product-grid">
        <div class="product-card">
          <div class="product-image">
            <img src="chair1.png" alt="Soft chairs">
          </div>
          <div class="product-info">
            <h4>Soft chairs</h4>
            <p>From<br>USD 19</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="stylishBaglamp1.png" alt="Sofa & chair">
          </div>
          <div class="product-info">
            <h4>Sofa & chair</h4>
            <p>From<br>USD 19</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="bed1.png" alt="Kitchen dishes">
          </div>
          <div class="product-info">
            <h4>Kitchen dishes</h4>
            <p>From<br>USD 19</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="pot1.png" alt="Smart watches">
          </div>
          <div class="product-info">
            <h4>Smart watches</h4>
            <p>From<br>USD 19</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="kitchenUtensils1.png" alt="Kitchen mixer">
          </div>
          <div class="product-info">
            <h4>Kitchen mixer</h4>
            <p>From<br>USD 100</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="kitchenUtensils2.png" alt="Blenders">
          </div>
          <div class="product-info">
            <h4>Blenders</h4>
            <p>From<br>USD 39</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="Bag1.png" alt="Home appliance">
          </div>
          <div class="product-info">
            <h4>Home appliance</h4>
            <p>From<br>USD 19</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="bed2.png" alt="Coffee maker">
          </div>
          <div class="product-info">
            <h4>Coffee maker</h4>
            <p>From<br>USD 10</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Consumer Electronics Section -->
  <div class="product-section">
    <div class="section-left">
      <div class="section-header">
        <h3>Consumer electronics and gadgets</h3>
        <button class="source-btn">Source now</button>
      </div>
      <div class="section-image electronics-bg">
        <img src="electronicGadgets.avif" alt="electronicGadgets" width="100px" height="100px">
      </div>
    </div>
    <div class="section-content">
      <div class="product-grid">
        <div class="product-card">
          <div class="product-image">
            <img src="watch5.jpeg" alt="Smart watches">
          </div>
          <div class="product-info">
            <h4>Smart watches</h4>
            <p>From<br>USD 19</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="camera1.png" alt="Cameras">
          </div>
          <div class="product-info">
            <h4>Cameras</h4>
            <p>From<br>USD 89</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="headphones4.jpeg" alt="Headphones">
          </div>
          <div class="product-info">
            <h4>Headphones</h4>
            <p>From<br>USD 10</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="jug1.png" alt="Smart watches">
          </div>
          <div class="product-info">
            <h4>Smart watches</h4>
            <p>From<br>USD 90</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="gamingSet1.png" alt="Gaming set">
          </div>
          <div class="product-info">
            <h4>Gaming set</h4>
            <p>From<br>USD 35</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="mobilePhone5.png" alt="Laptops & PC">
          </div>
          <div class="product-info">
            <h4>Laptops & PC</h4>
            <p>From<br>USD 340</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="mobilePhone3.png" alt="Smartphones">
          </div>
          <div class="product-info">
            <h4>Smartphones</h4>
            <p>From<br>USD 19</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-image">
            <img src="mobilePhone1.png" alt="Electric kettle">
          </div>
          <div class="product-info">
            <h4>Electric kettle</h4>
            <p>From<br>USD 240</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Quote Section -->
  <div class="quote-section">
    <div class="quote-left">
      <h3>An easy way to send requests to all suppliers</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
    </div>
    <div class="quote-form-container">
      <div class="quote-form">
        <input type="text" placeholder="What item you need?" class="form-input">
        <textarea placeholder="Type more details" class="form-textarea"></textarea>
        <div class="form-row">
          <input type="number" placeholder="Quantity" class="form-input-small">
          <select class="form-select">
            <option>Pcs</option>
            <option>Kg</option>
            <option>Tons</option>
          </select>
        </div>
        <button type="submit" class="send-btn">Send inquiry</button>
      </div>
    </div>
  </div>

 <!-- Recommended Items Section -->
  <div class="recommended-section">
    <div class="recommended-header">
   
    </div>
    <div class="recommended-grid">
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="shirt1.png" alt="T-shirts with multiple colors, for men">
        </div>
        <div class="recommended-info">
          <h4>T-shirts with multiple colors, for men</h4>
          <p class="price">$10.30</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="stylishShirt3.png" alt="Jeans shorts for men blue color">
        </div>
        <div class="recommended-info">
          <h4>Jeans shorts for men blue color</h4>
          <p class="price">$10.30</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="stylishShirt4.png" alt="Brown winter coat medium size">
        </div>
        <div class="recommended-info">
          <h4>Brown winter coat medium size</h4>
          <p class="price">$12.50</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="Bag2.png" alt="Jeans bag for travel for men">
        </div>
        <div class="recommended-info">
          <h4>Jeans bag for travel for men</h4>
          <p class="price">$34.00</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="stylishBag1.png" alt="Leather backpack">
        </div>
        <div class="recommended-info">
          <h4>Leather backpack</h4>
          <p class="price">$99.00</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="pant2.png" alt="Canon camera black, 100x zoom">
        </div>
        <div class="recommended-info">
          <h4>Canon camera black, 100x zoom</h4>
          <p class="price">$9.99</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="headphones4.jpeg" alt="Headset for gaming with mic">
        </div>
        <div class="recommended-info">
          <h4>Headset for gaming with mic</h4>
          <p class="price">$8.99</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="stylishBag1.png" alt="Smartwatch silver color modern">
        </div>
        <div class="recommended-info">
          <h4>Smartwatch silver color modern</h4>
          <p class="price">$10.30</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="pot1.png" alt="Blue wallet for men leather material">
        </div>
        <div class="recommended-info">
          <h4>Blue wallet for men leather material</h4>
          <p class="price">$10.30</p>
        </div>
      </div>
      <div class="recommended-card">
        <div class="recommended-image">
          <img src="jug1.png" alt="Coffee maker premium">
        </div>
        <div class="recommended-info">
          <h4>Coffee maker premium</h4>
          <p class="price">$80.95</p>
        </div>
      </div>
    </div>
  </div>

 <!-- Our Extra Services Section -->
  <div class="services-section">
    <div class="services-header">
      <h3>Our extra services</h3>
    </div>
    <div class="services-grid">
      <div class="service-card">
        <div class="service-image">
          <img src="design1.png" alt="" width="50px" height="50px">
        </div>
        <div class="service-content">
          <h4>Source from Industry Hubs</h4>
        </div>
      </div>
      <div class="service-card">
        <div class="service-image">
          <img src="design2.png" alt="" width="50px" height="50px">
        </div>
        <div class="service-content">
          <h4>Customize Your Products</h4>
        </div>
      </div>
      <div class="service-card">
        <div class="service-image">
          <img src="design3.png" alt="" width="50px" height="50px">
        </div>
        <div class="service-content">
          <h4>Fast, reliable shipping by ocean or air</h4>
        </div>
      </div>
      <div class="service-card">
        <div class="service-image">
          <img src="design4.png" alt="" width="50px" height="50px">
        </div>
        <div class="service-content">
          <h4>Product monitoring and inspection</h4>
        </div>
      </div>
    </div>
  </div>

  <!-- Suppliers by Region Section -->
  <div class="suppliers-section">
    <div class="suppliers-header">
      <h3>Suppliers by region</h3>
    </div>
    <div class="suppliers-grid">
      <div class="supplier-row">
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/ae.png" alt="UAE Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">Arabic Emirates</span>
            <span class="domain">shopname.ae</span>
          </div>
        </div>
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/au.png" alt="Australia Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">Australia</span>
            <span class="domain">shopname.ae</span>
          </div>
        </div>
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/us.png" alt="USA Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">United States</span>
            <span class="domain">shopname.ae</span>
          </div>
        </div>
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/ru.png" alt="Russia Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">Russia</span>
            <span class="domain">shopname.ru</span>
          </div>
        </div>
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/it.png" alt="Italy Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">Italy</span>
            <span class="domain">shopname.it</span>
          </div>
        </div>
      </div>
      <div class="supplier-row">
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/dk.png" alt="Denmark Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">Denmark</span>
            <span class="domain">denmark.com.dk</span>
          </div>
        </div>
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/fr.png" alt="France Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">France</span>
            <span class="domain">shopname.com.fr</span>
          </div>
        </div>
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/ae.png" alt="UAE Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">Arabic Emirates</span>
            <span class="domain">shopname.ae</span>
          </div>
        </div>
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/cn.png" alt="China Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">China</span>
            <span class="domain">shopname.ae</span>
          </div>
        </div>
        <div class="supplier-item">
          <img src="https://flagcdn.com/w40/gb.png" alt="Great Britain Flag" class="supplier-flag">
          <div class="supplier-info">
            <span class="country">Great Britain</span>
            <span class="domain">shopname.co.uk</span>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Newsletter Section -->
  <div class="newsletter-section">
    <div class="newsletter-content">
      <h3>Subscribe on our newsletter</h3>
      <p>Get daily news on upcoming offers from many suppliers all over the world</p>
      <div class="newsletter-form">
        <div class="email-input-wrapper">
          <i class="fa-solid fa-envelope"></i>
          <input type="email" placeholder="Email" class="newsletter-email">
        </div>
        <button class="newsletter-btn">Subscribe</button>
      </div>
    </div>
  </div>

  <!-- Footer Section -->
  <div class="footer-section">
    <div class="footer-content">
      <div class="footer-left">
        <div class="footer-brand">
          <i class="fa-solid fa-bag-shopping"></i>
          <span>Brand</span>
        </div>
        <p>Best information about the company gies here but now lorem ipsum is</p>
        <div class="social-icons">
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-linkedin"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-youtube"></i>
        </div>
      </div>
      
      <div class="footer-columns">
        <div class="footer-column">
          <h4>About</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Partnership</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Information</h4>
          <ul>
            <li><a href="#">Help Center</a></li>
            <li><a href="#">Money Refund</a></li>
            <li><a href="#">Shipping</a></li>
            <li><a href="#">Contact us</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>For users</h4>
          <ul>
            <li><a href="#">Login</a></li>
            <li><a href="#">Register</a></li>
            <li><a href="#">Settings</a></li>
            <li><a href="#">My Orders</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Get app</h4>
          <div class="app-buttons">
            <div class="app-button">
              <i class="fa-brands fa-apple"></i>
              <div class="app-text">
                <span class="small">Download on the</span>
                <span class="large">App Store</span>
              </div>
            </div>
            <div class="app-button">
              <i class="fa-brands fa-google-play"></i>
              <div class="app-text">
                <span class="small">Get it on</span>
                <span class="large">Google Play</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <div class="footer-bottom">
      <span>© 2023 Ecommerce.</span>
      <div class="language-selector">
        <img src="https://flagcdn.com/w20/us.png" alt="English Flag" class="lang-flag">
        <span>English</span>
        <i class="fa-solid fa-chevron-down"></i>
      </div>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>


//myWeb2.html page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Product Details | Brand</title>
  <link rel="stylesheet" href="myStyle.css">
  <link rel="stylesheet" href="mobileResponsive.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>

<!-- ===== Header ===== -->
<header class="top-header">
  <div class="logo">Brand</div>
  <div class="search-section">
    <select>
      <option>All category</option>
    </select>
    <input type="text" placeholder="Search" />
    <button>Search</button>
  </div>
  <div class="nav-icons">
    <span><i class="fa-solid fa-user"></i><br>Profile</span>
    <span><i class="fa-solid fa-message"></i><br>Message</span>
    <span><i class="fa-solid fa-heart"></i><br>Orders</span>
    <span><i class="fa-solid fa-cart-shopping"></i><br>My cart</span>
  </div>
</header>

<div class="nav-icons2">
  <p><i class="fa-solid fa-bars"></i> All Category</p>
  <p>Hot Offers</p>
  <p>Gift Boxes</p>
  <p>Projects</p>
  <p>Menu Items</p>
  <p>Help <select></select></p>
  <div class="nav-bar2">
    <select style="border: none; background-color: #f4f4f4;"><option>English, USD</option></select>
    <span>Ship to</span>
    <span><img src="germanyFlag.webp" alt="flag" height="25px" width="20px"></span>
  </div>
</div>

<!-- ===== Navigation Path ===== -->
<nav class="breadcrumb">Home > Clothing > Men’s wear > Summer clothing</nav>

<!-- ===== Product Section ===== -->
<section class="main-section">
  <div class="left-column">
    <img src="shirt1.jpeg" class="main-image" alt="Product" />
    <div class="thumbs">
      <img src="shirt2.jpeg" />
      <img src="shirt3.jpeg" />
      <img src="shirt4.jpeg" />
      <img src="shirt5.jpeg" />
      <img src="shirt6.jpeg" />
      <img src="shirt7.jpeg" />
    </div>
  </div>

  <div class="middle-column">
    <h2>Mens Long Sleeve T-shirt Cotton Base Layer Slim Muscle</h2>
    <div class="rating">⭐ 9.3 <span>(32 reviews)</span> <span>154 sold</span></div>
    <div class="price-box">
      <div>$98.00 <span>50–100 pcs</span></div>
      <div>$90.00 <span>100–700 pcs</span></div>
      <div>$78.00 <span>700+ pcs</span></div>
    </div>
    <div class="product-info">
      <p><strong>Price:</strong> Negotiable</p>
      <p><strong>Type:</strong> Classic shoes</p>
      <p><strong>Material:</strong> Plastic material</p>
      <p><strong>Design:</strong> Modern nice</p>
      <p><strong>Customization:</strong> Customized logo and design custom packages</p>
      <p><strong>Protection:</strong> Refund Policy</p>
      <p><strong>Warranty:</strong> 2 years full warranty</p>
    </div>
  </div>

  <div class="right-column">
    <div class="supplier-box">
      <p><strong>Supplier</strong></p>
      <p>Guangli Trading LLC</p>
      <p><img src="germanyFlag.webp" alt="flag" height="30px" width="20px"> Germany, Berlin</p>
      <p>✅ Verified Seller</p>
      <p>🌐 Worldwide shipping</p>
      <button>Send inquiry</button>
      <button style="background: white; color: #293b89; border: 1px solid black;">Seller's Profile</button>
    </div>
    <br><br>
    <a href="#" style="color: rgb(18, 84, 169); text-decoration: none; display: flex; justify-content: center;">💙 Save for later</a>
  </div>
</section>

<!-- ===== Tabs Section ===== -->
<section class="tabs-section">
  <div class="tabs">
    <span class="active">Description</span>
    <span>Reviews</span>
    <span>Shipping</span>
    <span>About seller</span>
  </div>

  <!-- 👇 Flex container combining content and image section -->
  <div class="tabs-flex-container">
  <div class="tab-content">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.... Lorem ipsum dolor sit, amet consectetur adipisicing<br>
    elit. Magnam, necessitatibus omnis facilis quisquam aspernatur fuga, quibusdam quas veniam inventore blanditiis<br>
    cum iure maxime pariatur asperiores laudantium rem eos accusamus sed... Lorem ipsum dolor sit, amet <br>
    Dolore dolorum assumenda a, ex corporis, doloremque  Dolore dolorum assumenda a, ex corporis, doloremque  <br>
    distinctio aspernatur! Optio consequuntur consectetur cumque <br>
    provident. distinctio aspernatur! Optio consequuntur consectetur cumque fugit distinctio fugitctio fugit <br> 
    distinctio aspernatur! Optio consequuntur consectetur cumque</p>

    <br><br>
    <table>
      <tr><td style = "background-color: rgb(118, 171, 194);">Model:</td><td>#8786867</td></tr>
      <tr><td style = "background-color: rgb(118, 171, 194);">Style:</td><td>Classic style</td></tr>
      <tr><td style = "background-color: rgb(118, 171, 194);">Certificate:</td><td>ISO-898921212</td></tr>
      <tr><td style = "background-color: rgb(118, 171, 194);">Size:</td><td>34mm x 450mm x 19mm</td></tr>
      <tr><td style = "background-color: rgb(118, 171, 194);">Memory:</td><td>36GB RAM</td></tr>
    </table>

    <br><br>
      <i class="fa-solid fa-check"></i> Some great feature name here<br><br>
      <i class="fa-solid fa-check"></i> Lorem ipsum dolor sit amet<br><br>
      <i class="fa-solid fa-check"></i> Duis aute irure dolor in reprehenderit<br><br>
      <i class="fa-solid fa-check"></i> Some great feature name here<br>
    
  </div>

  <!-- Updated product suggestions with names and prices -->
  <section class="tab-section2">
  <h3>You may like this</h3>

  <div class="product-item">
    <img src="stylishShirt4.png" alt="SS1">
    <div class="product-details">
      <span class="product-name">Men Blazer Set <br>Elegent Formal</span>
      <span class="product-price">$7.00 - $99.50</span>
    </div>
  </div>

  <div class="product-item">
    <img src="stylishShirt1.png" alt="SS2">
    <div class="product-details">
      <span class="product-name">Men Shirt Sleeve <br>Polo Contrast</span>
      <span class="product-price">$7.00 - $99.50</span>
    </div>
  </div>

  <div class="product-item">
    <img src="stylishShirt3.png" alt="SS3">
    <div class="product-details">
      <span class="product-name">Apple Watch Series <br>Space Gray</span>
      <span class="product-price">$7.00 - $99.50</span>
    </div>
  </div>

  <div class="product-item">
    <img src="stylishShirt2.png" alt="SS4">
    <div class="product-details">
      <span class="product-name">BasketBall Crew <br>Socks Long Stuff</span>
      <span class="product-price">$7.00 - $99.50</span>
    </div>
  </div>

  <div class="product-item">
    <img src="stylishBag1.png" alt="SS5">
    <div class="product-details">
      <span class="product-name">New Summer Men's <br>castrol T-shirts</span>
      <span class="product-price">$7.00 - $99.50</span>
    </div>
  </div>
</section>
</div>
</section>

<!-- ===== Related Products ===== -->
<section class="related-products">
  <h3>Related products</h3>
  <div class="product-cards">
    <div class="card"><img src="Bag1.png"><p>Product Name<br>$32.00–$40.00</p></div>
    <div class="card"><img src="watch5.jpeg"><p>Product Name<br>$32.00–$40.00</p></div>
    <div class="card"><img src="headphones4.jpeg"><p>Product Name<br>$32.00–$40.00</p></div>
    <div class="card"><img src="pant2.png"><p>Product Name<br>$32.00–$40.00</p></div>
    <div class="card"><img src="jug6.jpeg"><p>Product Name<br>$32.00–$40.00</p></div>
    <div class="card"><img src="bag2.png"><p>Product Name<br>$32.00–$40.00</p></div>
  </div>
  <br><br>

  <div style="background-color: rgb(59, 59, 200); height: 100px; width: 100%; padding-left: 40px;">
    <div style="color: white; display: flex; align-items:center; font-size: 1.65rem;">
      <p style="padding-top: 20px;">Super Discount on more than 100 USD</p>
      <button style="border: none; border-radius: 7px; height: 50px; width: 150px; 
      margin-top: 20px; margin-left: 650px; background-color: rgb(234, 177, 8); 
      color: rgb(255, 255, 255); font-size: 1.05rem;">Shop Now</button>
    </div>
    <p style="margin-bottom: 10px; color: rgb(192, 203, 203);">Have you ever finally just dummy info</p>
  </div>
</section>

<!-- Footer Section -->
  <div class="footer-section">
    <div class="footer-content">
      <div class="footer-left">
        <div class="footer-brand">
          <i class="fa-solid fa-bag-shopping"></i>
          <span>Brand</span>
        </div>
        <p>Best information about the company gies here but now lorem ipsum is</p>
        <div class="social-icons">
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-linkedin"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-youtube"></i>
        </div>
      </div>
      
      <div class="footer-columns">
        <div class="footer-column">
          <h4>About</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Partnership</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Information</h4>
          <ul>
            <li><a href="#">Help Center</a></li>
            <li><a href="#">Money Refund</a></li>
            <li><a href="#">Shipping</a></li>
            <li><a href="#">Contact us</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>For users</h4>
          <ul>
            <li><a href="#">Login</a></li>
            <li><a href="#">Register</a></li>
            <li><a href="#">Settings</a></li>
            <li><a href="#">My Orders</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Get app</h4>
          <div class="app-buttons">
            <div class="app-button">
              <i class="fa-brands fa-apple"></i>
              <div class="app-text">
                <span class="small">Download on the</span>
                <span class="large">App Store</span>
              </div>
            </div>
            <div class="app-button">
              <i class="fa-brands fa-google-play"></i>
              <div class="app-text">
                <span class="small">Get it on</span>
                <span class="large">Google Play</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <div class="footer-bottom">
      <span>© 2023 Ecommerce.</span>
      <div class="language-selector">
        <img src="https://flagcdn.com/w20/us.png" alt="English Flag" class="lang-flag">
        <span>English</span>
        <i class="fa-solid fa-chevron-down"></i>
      </div>
    </div>
  </div>
</body>
</html>


//myWeb3.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Product Listing | Brand</title>
  <link rel="stylesheet" href="myStyle.css" />
  <link rel="stylesheet" href="mobileResponsive.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>

<!-- Header -->
<header class="top-header">
  <div class="logo">Brand</div>
  <div class="search-box">
    <select>
      <option>All category</option>
    </select>
    <input type="text" placeholder="Search">
    <button>Search</button>
  </div>
  <div class="header-icons">
    <span><i class="fa-solid fa-user"></i> Profile</span>
    <span><i class="fa-solid fa-message"></i> Message</span>
    <span><i class="fa-solid fa-heart"></i> Orders</span>
    <span><i class="fa-solid fa-cart-shopping"></i> My cart</span>
  </div>
</header>

<!-- Sub Nav -->
<div class="sub-nav">
  <ul>
    <li>All category</li>
    <li>Hot offers</li>
    <li>Gift boxes</li>
    <li>Projects</li>
    <li>Menu Item</li>
    <li>Help</li>
  </ul>
  <div class="lang-ship">
    <span>English, USD ▼</span>
    <span>Ship to ▼</span>
  </div>
</div>

<!-- Breadcrumb -->
<div class="breadcrumb">Home > Clothings > Men's wear > Summer clothing</div>

<!-- Main Content -->
<main class="container">
  <!-- Sidebar -->
  <aside class="sidebar">
    <h3>Category</h3>
    <ul>
      <li>Mobile accessory</li>
      <li>Electronics</li>
      <li>Smartphones</li>
      <li>Modern tech</li>
    </ul>
    <h3>Brands</h3>
    <label><input type="checkbox" checked> Samsung</label>
    <label><input type="checkbox" checked> Apple</label>
    <label><input type="checkbox"> Huawei</label>
    <label><input type="checkbox"> Poco</label>
    <h3>Features</h3>
    <label><input type="checkbox" checked> Metallic</label>
    <label><input type="checkbox"> Plastic Cover</label>
    <label><input type="checkbox"> 8GB Ram</label>
    <label><input type="checkbox"> Super power</label>
    <label><input type="checkbox"> Large Memory</label>
  </aside>

  <!-- Product Section -->
  <section class="product-area">
    <div class="filters-bar">
      <div>12,911 items in <strong>Mobile accessory</strong></div>
      <div class="filters-actions">
        <label><input type="checkbox"> Verified only</label>
        <select>
          <option>Featured</option>
          <option>Price Low to High</option>
          <option>Price High to Low</option>
        </select>
        <div class="view-toggle">
          <i class="fa-solid fa-grip active"></i>
          <i class="fa-solid fa-list"></i>
        </div>
      </div>
    </div>

    <!-- Filters Tags -->
    <div class="filter-tags">
      <span>Samsung</span>
      <span>Apple</span>
      <span>Poco</span>
      <span>Metallic</span>
      <span>4 star</span>
      <span>3 star</span>
      <a href="#" class="clear-filter">Clear all filter</a>
    </div>

    <!-- Product Grid -->
    <div class="product-grid">
      <!-- Example Product (Repeat this block for more products) -->
      <div class="product-card">
        <img src="mobilePhone1.png" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>

      <div class="product-card">
        <img src="smartPhone1.png" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>

      <div class="product-card">
        <img src="mobilePhone2.png" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>
      <!-- Add more .product-card here to fill grid -->
    </div>

    <!-- Product Grid -->
    <div class="product-grid">
      <!-- Example Product (Repeat this block for more products) -->
      <div class="product-card">
        <img src="mobilePhone3.png" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>

      <div class="product-card">
        <img src="camera1.png" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>

      <div class="product-card">
        <img src="smartPhone1.png" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>
      <!-- Add more .product-card here to fill grid -->
    </div>

    <!-- Product Grid -->
    <div class="product-grid">
      <!-- Example Product (Repeat this block for more products) -->
      <div class="product-card">
        <img src="mobilePhone5.png" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>

      <div class="product-card">
        <img src="watch5.jpeg" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>

      <div class="product-card">
        <img src="mobilePhone1.png" alt="Product">
        <h4>$99.50 <span class="old-price">$1128.00</span></h4>
        <div class="stars">⭐⭐⭐⭐⭐ 75</div>
        <p>GoPro HERO6 4K Action Camera - Black</p>
      </div>
      <!-- Add more .product-card here to fill grid -->
    </div>

    <!-- Pagination -->
    <div class="pagination">
      <button>1</button>
      <button>2</button>
      <button>3</button>
    </div>
  </section>
</main>

  <!-- Newsletter Section -->
  <div class="newsletter">
    <h3>Subscribe on our newsletter</h3><br>
    <p>Get daily news on upcoming offers from many suppliers all over the world</p><br>
    <input type="email" placeholder="Email"><br>
    
    <button>Subscribe</button>
  </div>

 <!-- Footer Section -->
  <div class="footer-section">
    <div class="footer-content">
      <div class="footer-left">
        <div class="footer-brand">
          <i class="fa-solid fa-bag-shopping"></i>
          <span>Brand</span>
        </div>
        <p>Best information about the company gies here but now lorem ipsum is</p>
        <div class="social-icons">
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-linkedin"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-youtube"></i>
        </div>
      </div>
      
      <div class="footer-columns">
        <div class="footer-column">
          <h4>About</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Partnership</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Information</h4>
          <ul>
            <li><a href="#">Help Center</a></li>
            <li><a href="#">Money Refund</a></li>
            <li><a href="#">Shipping</a></li>
            <li><a href="#">Contact us</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>For users</h4>
          <ul>
            <li><a href="#">Login</a></li>
            <li><a href="#">Register</a></li>
            <li><a href="#">Settings</a></li>
            <li><a href="#">My Orders</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Get app</h4>
          <div class="app-buttons">
            <div class="app-button">
              <i class="fa-brands fa-apple"></i>
              <div class="app-text">
                <span class="small">Download on the</span>
                <span class="large">App Store</span>
              </div>
            </div>
            <div class="app-button">
              <i class="fa-brands fa-google-play"></i>
              <div class="app-text">
                <span class="small">Get it on</span>
                <span class="large">Google Play</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <div class="footer-bottom">
      <span>© 2023 Ecommerce.</span>
      <div class="language-selector">
        <img src="https://flagcdn.com/w20/us.png" alt="English Flag" class="lang-flag">
        <span>English</span>
        <i class="fa-solid fa-chevron-down"></i>
      </div>
    </div>
  </div>

</body>
</html>


//myWeb4.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Product List | Brand</title>
  <link rel="stylesheet" href="myStyle.css">
  <link rel="stylesheet" href="mobileResponsive.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>
  <!-- Header -->
<header class="top-header">
  <div class="logo">Brand</div>
  <div class="search-box">
    <select>
      <option>All category</option>
    </select>
    <input type="text" placeholder="Search">
    <button>Search</button>
  </div>
  <div class="header-icons">
    <span><i class="fa-solid fa-user"></i> Profile</span>
    <span><i class="fa-solid fa-message"></i> Message</span>
    <span><i class="fa-solid fa-heart"></i> Orders</span>
    <span><i class="fa-solid fa-cart-shopping"></i> My cart</span>
  </div>
</header>

  <!-- Navigation Bar -->
    <nav class="navigation-bar">
      
      <div style="display: flex; justify-content: space-evenly; padding-right: 830px;">
          <a href="#"><i class="fas fa-bars"></i> All category</a>
          <a href="#">Hot offers</a>
          <a href="#">Gift boxes</a>
          <a href="#">Projects</a>
          <a href="#">Menu Item</a>
          <a href="#">Help ▼</a>
      </div>
        
        <div style="display: flex; justify-content: space-evenly; padding-left: 1100px;">
            <div class="language" style="display: flex;">
                English, USD ▼
            </div>
            <div class="ship-to" style="display: flex; justify-content: space-evenly;">
                <span>Ship to</span>
                <img src="germanyFlag.webp" alt="Germany" style="display: flex;">
            </div>
        </div>
    </nav>

    <!-- Breadcrumb -->
    <div class="breadcrumb">
        Home > Clothing > Men's wear > Summer clothing
    </div>

  <main class="container">
    <aside class="sidebar">
  <h3>Category</h3>
  <ul>
    <li>Mobile accessory</li>
    <li>Electronics</li>
    <li>Smartphones</li>
    <li>Modern tech</li>
    <li style="color:#007bff; cursor:pointer;">See all</li>
  </ul>

  <h3>Brands</h3>
  <label><input type="checkbox"> Samsung</label>
  <label><input type="checkbox"> Apple</label>
  <label><input type="checkbox"> Huawei</label>
  <label><input type="checkbox"> Poco</label>
  <label style="color:#007bff; cursor:pointer;">See all</label>

  <h3>Features</h3>
  <label><input type="checkbox"> Metallic</label>
  <label><input type="checkbox"> Plastic cover</label>
  <label><input type="checkbox"> 8GB Ram</label>
  <label><input type="checkbox"> Super power</label>
  <label><input type="checkbox"> Large Memory</label>
  <label style="color:#007bff; cursor:pointer;">See all</label>

  <h3>Price range</h3>
  <div class="price-range">
    <input type="number" placeholder="Min" />
    <input type="number" placeholder="Max" />
    <button class="apply-btn">Apply</button>
  </div>

  <h3>Condition</h3>
  <label><input type="radio" name="condition" checked> Any</label>
  <label><input type="radio" name="condition"> Refurbished</label>
  <label><input type="radio" name="condition"> Brand new</label>
  <label><input type="radio" name="condition"> Old items</label>

  <h3>Ratings</h3>
  <div class="ratings">
    <label><input type="checkbox"> ⭐⭐⭐⭐⭐</label>
    <label><input type="checkbox"> ⭐⭐⭐⭐</label>
    <label><input type="checkbox"> ⭐⭐⭐</label>
    <label><input type="checkbox"> ⭐⭐</label>
  </div>
</aside>

    <section class="product-area">
      <div class="filters-bar">
        <div style="padding-left: 10px;">12,911 items in <strong>Mobile accessory</strong></div>
        <div style="padding-right: 10px;">
          <label><input type="checkbox"> Verified only</label>
          <select style="font-size: 1.05rem;">
            <option>Featured</option>
            <option>Price low to high</option>
            <option>Price high to low</option>
          </select>
        </div>
      </div>

      <div class="product-list">
        <!-- Repeat for each product -->
        <div class="product-list-item">
          <img src="mobilePhone1.png" alt="Product" />
          <div class="product-info">
            <h4>Canon Camera EOS 2000, Black 10x zoom</h4>
            <p class="price">$998.00 <span class="old-price">$1128.00</span></p>
            <div class="stars">⭐ 7.5 — 154 orders — <span class="green">Free Shipping</span></div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            <a href="#" class="details-link">View details</a>
          </div>
        </div>

        <div class="product-list-item">
          <img src="mobilePhone2.png" alt="Product" />
          <div class="product-info">
            <h4>Canon Camera EOS 2000, Black 10x zoom</h4>
            <p class="price">$998.00 <span class="old-price">$1128.00</span></p>
            <div class="stars">⭐ 7.5 — 154 orders — <span class="green">Free Shipping</span></div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            <a href="#" class="details-link">View details</a>
          </div>
        </div>

        <div class="product-list-item">
          <img src="mobilePhone3.png" alt="Product" />
          <div class="product-info">
            <h4>Canon Camera EOS 2000, Black 10x zoom</h4>
            <p class="price">$998.00 <span class="old-price">$1128.00</span></p>
            <div class="stars">⭐ 7.5 — 154 orders — <span class="green">Free Shipping</span></div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            <a href="#" class="details-link">View details</a>
          </div>
        </div>

        <div class="product-list-item">
          <img src="mobilePhone5.png" alt="Product" />
          <div class="product-info">
            <h4>Canon Camera EOS 2000, Black 10x zoom</h4>
            <p class="price">$998.00 <span class="old-price">$1128.00</span></p>
            <div class="stars">⭐ 7.5 — 154 orders — <span class="green">Free Shipping</span></div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            <a href="#" class="details-link">View details</a>
          </div>
        </div>

        <div class="product-list-item">
          <img src="watch5.jpeg" alt="Product" />
          <div class="product-info">
            <h4>Canon Camera EOS 2000, Black 10x zoom</h4>
            <p class="price">$998.00 <span class="old-price">$1128.00</span></p>
            <div class="stars">⭐ 7.5 — 154 orders — <span class="green">Free Shipping</span></div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            <a href="#" class="details-link">View details</a>
          </div>
        </div>

        <div class="product-list-item">
          <img src="mobilePhone6.png" alt="Product" />
          <div class="product-info">
            <h4>Canon Camera EOS 2000, Black 10x zoom</h4>
            <p class="price">$998.00 <span class="old-price">$1128.00</span></p>
            <div class="stars">⭐ 7.5 — 154 orders — <span class="green">Free Shipping</span></div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            <a href="#" class="details-link">View details</a>
          </div>
        </div>
        <!-- Repeat for other products -->
      </div>

      <!-- Newsletter Subscription Section -->
    <div class="newsletter-banner">
        <h3>Subscribe on our newsletter</h3>
        <p>Get daily news or upcoming offers from many suppliers all over the world</p>
        <div class="newsletter-input">
            <input type="email" placeholder="Email" />
            <button>Subscribe</button>
        </div>
    </div>
  </main>

 <!-- Footer Section -->
  <div class="footer-section">
    <div class="footer-content">
      <div class="footer-left">
        <div class="footer-brand">
          <i class="fa-solid fa-bag-shopping"></i>
          <span>Brand</span>
        </div>
        <p>Best information about the company gies here but now lorem ipsum is</p>
        <div class="social-icons">
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-linkedin"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-youtube"></i>
        </div>
      </div>
      
      <div class="footer-columns">
        <div class="footer-column">
          <h4>About</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Partnership</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Information</h4>
          <ul>
            <li><a href="#">Help Center</a></li>
            <li><a href="#">Money Refund</a></li>
            <li><a href="#">Shipping</a></li>
            <li><a href="#">Contact us</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>For users</h4>
          <ul>
            <li><a href="#">Login</a></li>
            <li><a href="#">Register</a></li>
            <li><a href="#">Settings</a></li>
            <li><a href="#">My Orders</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Get app</h4>
          <div class="app-buttons">
            <div class="app-button">
              <i class="fa-brands fa-apple"></i>
              <div class="app-text">
                <span class="small">Download on the</span>
                <span class="large">App Store</span>
              </div>
            </div>
            <div class="app-button">
              <i class="fa-brands fa-google-play"></i>
              <div class="app-text">
                <span class="small">Get it on</span>
                <span class="large">Google Play</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <div class="footer-bottom">
      <span>© 2023 Ecommerce.</span>
      <div class="language-selector">
        <img src="https://flagcdn.com/w20/us.png" alt="English Flag" class="lang-flag">
        <span>English</span>
        <i class="fa-solid fa-chevron-down"></i>
      </div>
    </div>
  </div>
</body>

    <script>
        document.querySelectorAll('.sidebar h3').forEach(header => {
            header.addEventListener('click', () => {
            const next = header.nextElementSibling;
            if (next && (next.tagName === 'UL' || next.tagName === 'DIV' || next.tagName === 'LABEL')) {
                next.classList.toggle('collapsed');
                header.classList.toggle('collapsed');
            }
            });
        });
    </script>
</html>


//myWeb5.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Cart | Brand</title>
  <link rel="stylesheet" href="myStyle.css">
  <link rel="stylesheet" href="mobileResponsive.css">
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>
  <!-- Header -->
<header class="top-header">
  <div class="logo">Brand</div>
  <div class="search-box">
    <select>
      <option>All category</option>
    </select>
    <input type="text" placeholder="Search">
    <button>Search</button>
  </div>
  <div class="header-icons">
    <span><i class="fa-solid fa-user"></i> Profile</span>
    <span><i class="fa-solid fa-message"></i> Message</span>
    <span><i class="fa-solid fa-heart"></i> Orders</span>
    <span><i class="fa-solid fa-cart-shopping"></i> My cart</span>
  </div>
</header>

  <main class="container cart-page">
    <section class="cart-items">
      <h2>My Cart (3)</h2>
      <div class="cart-item">
        <img src="stylishShirt1.png" alt="shirt" width="100px" height="100px">
        <div>
          T-shirts with multiple colors, for men and lady<br/>
          Size: Medium, Color: Blue, Material: Plastic<br/>
          Seller: Artel Market
        </div>
        <div>
          $78.99 — Qty: 9<br/>
          <button class="remove-btn">Remove</button>
          <button class="save-btn">Save for later</button>
        </div>
      </div>
      <!-- Repeat for other items -->

      <div class="cart-item">
        <img src="stylishBag1.png" alt="shirt" width="100px" height="100px">
        <div>
          T-shirts with multiple colors, for men and lady<br/>
          Size: Medium, Color: Blue, Material: Plastic<br/>
          Seller: Artel Market
        </div>
        <div>
          $78.99 - Qty: 9<br/>
        <button class="remove-btn">Remove</button>
        <button class="save-btn">Save for later</button>
        </div>
      </div>

      <div class="cart-item">
        <img src="stylishBaglamp1.png" alt="shirt" width="100px" height="100px">
        <div>
          T-shirts with multiple colors, for men and lady<br/>
          Size: Medium, Color: Blue, Material: Plastic<br/>
          Seller: Artel Market
        </div>
        <div>
          $78.99 — Qty: 9<br/>
          <button class="remove-btn">Remove</button>
          <button class="save-btn">Save for later</button>
        </div>
      </div>
    </section>

    <aside class="cart-summary">
      <h3>Have a coupon?</h3>
      <input type="text" placeholder="Add coupon" />
      <button>Apply</button>
      <div class="summary-details">
        <p>Subtotal: $1403.97</p>
        <p>Discount: -$60.00</p>
        <p>Tax: +$14.00</p>
        <h3>Total: $1357.97</h3>
        <button class="checkout-btn">Checkout</button>
      </div>
    </aside>
  </main>

  <section class="saved-items">
    <h3>Saved for Later</h3>
    <div class="saved-products">
      <div class="saved-item">GoPro HERO6 4K Action Camera - $99.50</div>
      <div class="saved-item">Apple Watch - $99.50</div>
      <!-- Add more items -->
    </div>
  </section>

  <!-- ===== Related Products ===== -->
<section class="related-products">
  <h3>Saved For Later</h3>
  <div class="product-cards">
    <div class="card"><img src="mobilePhone3.png"><p>Product Name<br>$32.00–$40.00</p></div>
    <div class="card"><img src="smartPhone1.png"><p>Product Name<br>$32.00–$40.00</p></div>
    <div class="card"><img src="watch5.jpeg"><p>Product Name<br>$32.00–$40.00</p></div>
    <div class="card"><img src="mobilePhone5.png"><p>Product Name<br>$32.00–$40.00</p></div>
  </div>
  <br><br>

  <div style="background-color: rgb(59, 59, 200); height: 100px; width: 100%; padding-left: 40px;">
    <div style="color: white; display: flex; align-items:center; font-size: 1.65rem;">
      <p style="padding-top: 20px;">Super Discount on more than 100 USD</p>
      <button style="border: none; border-radius: 7px; height: 50px; width: 150px; 
      margin-top: 20px; margin-left: 650px; background-color: rgb(234, 177, 8); 
      color: rgb(255, 255, 255); font-size: 1.05rem;">Shop Now</button>
    </div>
    <p style="margin-bottom: 10px; color: rgb(192, 203, 203);">Have you ever finally just dummy info</p>
  </div>
</section>


   <!-- Footer Section -->
  <div class="footer-section">
    <div class="footer-content">
      <div class="footer-left">
        <div class="footer-brand">
          <i class="fa-solid fa-bag-shopping"></i>
          <span>Brand</span>
        </div>
        <p>Best information about the company gies here but now lorem ipsum is</p>
        <div class="social-icons">
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-linkedin"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-youtube"></i>
        </div>
      </div>
      
      <div class="footer-columns">
        <div class="footer-column">
          <h4>About</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Partnership</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Find store</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Blogs</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Information</h4>
          <ul>
            <li><a href="#">Help Center</a></li>
            <li><a href="#">Money Refund</a></li>
            <li><a href="#">Shipping</a></li>
            <li><a href="#">Contact us</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>For users</h4>
          <ul>
            <li><a href="#">Login</a></li>
            <li><a href="#">Register</a></li>
            <li><a href="#">Settings</a></li>
            <li><a href="#">My Orders</a></li>
          </ul>
        </div>
        
        <div class="footer-column">
          <h4>Get app</h4>
          <div class="app-buttons">
            <div class="app-button">
              <i class="fa-brands fa-apple"></i>
              <div class="app-text">
                <span class="small">Download on the</span>
                <span class="large">App Store</span>
              </div>
            </div>
            <div class="app-button">
              <i class="fa-brands fa-google-play"></i>
              <div class="app-text">
                <span class="small">Get it on</span>
                <span class="large">Google Play</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <div class="footer-bottom">
      <span>© 2023 Ecommerce.</span>
      <div class="language-selector">
        <img src="https://flagcdn.com/w20/us.png" alt="English Flag" class="lang-flag">
        <span>English</span>
        <i class="fa-solid fa-chevron-down"></i>
      </div>
    </div>
  </div>
</body>
</html>


//myStyle.css file

/* index.html CSS Code with Media Queries */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
}

/* Main Navbar */
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 12px 40px;
  background-color: white;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

/* Brand */
.brand {
  display: flex;
  align-items: center;
  font-size: 24px;
  font-weight: bold;
  color: #80b3ff;
}

.brand i {
  font-size: 28px;
  margin-right: 8px;
  background-color: #3399ff;
  padding: 10px;
  border-radius: 12px;
  color: white;
}

/* Search bar */
.search-bar {
  display: flex;
  flex: 1;
  max-width: 600px;
  margin: 0 30px;
}

.search-bar input {
  flex: 1;
  padding: 10px;
  border: 1px solid #3399ff;
  border-right: none;
  border-radius: 6px 0 0 6px;
  outline: none;
}

.search-bar select {
  padding: 10px;
  border: 1px solid #3399ff;
  border-left: none;
  border-right: none;
  outline: none;
  background: #f0f0f0;
}

.search-bar button {
  padding: 10px 20px;
  background-color: #3399ff;
  color: white;
  border: none;
  border-radius: 0 6px 6px 0;
  cursor: pointer;
}

/* Icons */
.nav-icons {
  display: flex;
  align-items: center;
  gap: 30px;
}

.nav-icons .icon {
  text-align: center;
  color: gray;
  font-size: 14px;
  cursor: pointer;
}

.nav-icons .icon i {
  display: block;
  font-size: 18px;
  margin-bottom: 4px;
}

/* Top Navbar */
.top-navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 40px;
  font-size: 14px;
  background-color: white;
  border-bottom: 1px solid #eee;
}

.top-navbar .top-left,
.top-navbar .top-right {
  display: flex;
  align-items: center;
  gap: 20px;
}

.top-left i {
  margin-right: 6px;
}

.top-left a {
  text-decoration: none;
  color: black;
}

.top-right span {
  color: black;
}

.small-icon {
  font-size: 10px;
  margin-left: 4px;
}

.flag-icon {
  height: 14px;
  width: auto;
  margin: 0 4px;
  vertical-align: middle;
}

.flag-dropdown {
  position: relative;
  cursor: pointer;
}

.flag-options {
  display: none;
  position: absolute;
  top: 100%;
  right: 0;
  background: white;
  border: 1px solid #ccc;
  border-radius: 4px;
  z-index: 10;
  width: 150px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.flag-options div {
  padding: 8px 12px;
  cursor: pointer;
  font-size: 14px;
}

.flag-options div:hover {
  background-color: #f0f0f0;
}

/* Promo Section */
.promo-section {
  display: flex;
  gap: 20px;
  padding: 30px 40px;
  background-color: #f9f9f9;
}

.promo-categories {
  width: 200px;
}

.promo-categories ul {
  list-style: none;
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  background-color: white;
}

.promo-categories li {
  padding: 12px 16px;
  font-size: 14px;
  cursor: pointer;
  border-bottom: 1px solid #eee;
}

.promo-categories li:last-child {
  border-bottom: none;
}

.promo-categories li.active {
  background-color: #e9f0ff;
  font-weight: bold;
  color: #333;
}

.promo-banner {
  flex: 1;
  background: url(./Banner-board.png) no-repeat center right;
  background-size: cover;
  padding: 40px;
  border-radius: 8px;
  color: #222;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.promo-banner h2 {
  font-size: 28px;
  margin-bottom: 16px;
  line-height: 1.3;
}

.promo-banner button {
  padding: 10px 20px;
  background-color: white;
  border: none;
  border-radius: 6px;
  font-weight: bold;
  cursor: pointer;
  width: fit-content;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.promo-right {
  width: 200px;
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.login-box {
  background-color: white;
  border-radius: 8px;
  padding: 16px;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.user-info {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 12px;
  justify-content: center;
}

.user-info i {
  font-size: 28px;
  color: #ccc;
}

.user-info p {
  margin: 0;
  font-size: 14px;
  color: #333;
}

.join-btn {
  width: 100%;
  background-color: #007bff;
  color: white;
  padding: 8px;
  border: none;
  border-radius: 4px;
  margin-bottom: 8px;
  cursor: pointer;
}

.login-btn {
  width: 100%;
  background-color: #f0f0f0;
  color: #333;
  padding: 8px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.orange-box,
.blue-box {
  padding: 14px;
  border-radius: 8px;
  color: white;
  font-size: 14px;
  line-height: 1.4;
  font-weight: 500;
}

.orange-box {
  background-color: #f6931e;
}

.blue-box {
  background-color: #5bb7d2;
}

/* Deals and Offers Section */
.deals-section {
  display: flex;
  margin: 20px 40px;
  background-color: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.deals-left {
  width: 200px;
  background-color: #f8f9fa;
  padding: 30px 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.deals-left h3 {
  font-size: 20px;
  margin-bottom: 8px;
  color: #333;
  font-weight: bold;
}

.deals-left p {
  font-size: 14px;
  color: #666;
  margin-bottom: 20px;
}

.timer {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
}

.time-box {
  background-color: #2c3e50;
  color: white;
  padding: 8px 6px;
  border-radius: 4px;
  text-align: center;
  min-width: 35px;
}

.time-number {
  display: block;
  font-size: 16px;
  font-weight: bold;
  line-height: 1;
}

.time-label {
  display: block;
  font-size: 10px;
  margin-top: 2px;
  opacity: 0.8;
}

.deals-content {
  flex: 1;
  padding: 20px;
}

.deals-grid {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 15px;
}

.deal-item {
  text-align: center;
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s;
  padding: 15px 10px;
  border-radius: 8px;
}

.deal-item:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.deal-image {
  width: 100%;
  height: 100px;
  margin-bottom: 12px;
  border-radius: 8px;
  overflow: hidden;
  background-color: #f5f5f5;
  display: flex;
  align-items: center;
  justify-content: center;
}

.deal-image img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.deal-item h4 {
  font-size: 14px;
  margin-bottom: 8px;
  color: #333;
  font-weight: normal;
  line-height: 1.3;
}

.discount {
  background-color: #ff4757;
  color: white;
  padding: 4px 8px;
  border-radius: 12px;
  font-size: 12px;
  font-weight: bold;
  display: inline-block;
}

/* Product Sections */
.product-section {
  display: flex;
  margin: 20px 40px;
  background-color: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.section-left {
  width: 200px;
  background-color: #f8f9fa;
  padding: 30px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.section-header h3 {
  font-size: 18px;
  margin-bottom: 15px;
  color: #333;
  line-height: 1.3;
}

.source-btn {
  background-color: white;
  border: 1px solid #ddd;
  padding: 8px 16px;
  border-radius: 4px;
  font-size: 14px;
  cursor: pointer;
  margin-bottom: 20px;
}

.section-image {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 80px;
}

.electronics-bg {
  background: linear-gradient(135deg, #ffe0e6, #ffb3d1);
  border-radius: 8px;
  width: 100px;
}

.section-content {
  flex: 1;
  padding: 20px;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 15px;
}

.product-card {
  display: flex;
  align-items: center;
  padding: 15px;
  border: 1px solid #eee;
  border-radius: 8px;
  gap: 12px;
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s;
}

.product-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.product-image {
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f8f9fa;
  border-radius: 8px;
  overflow: hidden;
}

.product-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 6px;
}

.product-info h4 {
  font-size: 14px;
  margin-bottom: 4px;
  font-weight: normal;
  color: #333;
}

.product-info p {
  font-size: 12px;
  color: #888;
  line-height: 1.3;
}

/* Recommended Items Section */
.recommended-section {
  margin: 20px 40px;
  background-color: white;
  border-radius: 8px;
  padding: 30px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.recommended-header {
  text-align: center;
  margin-bottom: 30px;
}

.recommended-header h3 {
  font-size: 24px;
  color: #333;
  font-weight: bold;
  margin: 0;
}

.recommended-grid {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 20px;
}

.recommended-card {
  border: 1px solid #eee;
  border-radius: 8px;
  padding: 15px;
  text-align: center;
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s;
  background-color: white;
}

.recommended-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.recommended-image {
  width: 100%;
  height: 140px;
  margin-bottom: 12px;
  border-radius: 8px;
  overflow: hidden;
  background-color: #f8f9fa;
  display: flex;
  align-items: center;
  justify-content: center;
}

.recommended-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.recommended-info h4 {
  font-size: 14px;
  margin-bottom: 8px;
  font-weight: normal;
  color: #333;
  line-height: 1.3;
  text-align: left;
}

.recommended-info .price {
  font-size: 16px;
  font-weight: bold;
  color: #333;
  text-align: left;
  margin: 0;
}

/* Quote Section */
.quote-section {
  margin: 20px 40px;
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  border-radius: 8px;
  padding: 40px;
  display: flex;
  align-items: center;
  gap: 40px;
}

.quote-left {
  flex: 1;
  color: white;
}

.quote-left h3 {
  font-size: 24px;
  margin-bottom: 12px;
  font-weight: bold;
}

.quote-left p {
  font-size: 16px;
  opacity: 0.9;
  line-height: 1.4;
}

.quote-form-container {
  background-color: white;
  padding: 30px;
  border-radius: 8px;
  min-width: 400px;
}

.quote-form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.form-input,
.form-textarea {
  padding: 12px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 14px;
  outline: none;
}

.form-textarea {
  min-height: 80px;
  resize: vertical;
}

.form-row {
  display: flex;
  gap: 10px;
}

.form-input-small {
  flex: 2;
  padding: 12px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 14px;
  outline: none;
}

.form-select {
  flex: 1;
  padding: 12px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 14px;
  outline: none;
  background-color: white;
}

.send-btn {
  background-color: #007bff;
  color: white;
  padding: 12px 24px;
  border: none;
  border-radius: 4px;
  font-size: 14px;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.2s;
}

.send-btn:hover {
  background-color: #0056b3;
}

/* Our Extra Services Section */
.services-section {
  margin: 20px 40px;
  background-color: white;
  border-radius: 8px;
  padding: 30px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.services-header {
  text-align: left;
  margin-bottom: 30px;
}

.services-header h3 {
  font-size: 20px;
  color: #333;
  font-weight: bold;
  margin: 0;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}

.service-card {
  display: flex;
  align-items: center;
  padding: 20px;
  border: 1px solid #eee;
  border-radius: 8px;
  gap: 15px;
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s;
  background-color: #f8f9fa;
}

.service-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.service-image {
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: white;
  border-radius: 8px;
}

.service-content h4 {
  font-size: 14px;
  font-weight: normal;
  color: #333;
  margin: 0;
  line-height: 1.4;
}

/* Suppliers by Region Section */
.suppliers-section {
  margin: 20px 40px;
  background-color: white;
  border-radius: 8px;
  padding: 30px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.suppliers-header {
  text-align: left;
  margin-bottom: 30px;
}

.suppliers-header h3 {
  font-size: 20px;
  color: #333;
  font-weight: bold;
  margin: 0;
}

.suppliers-grid {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.supplier-row {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 20px;
}

.supplier-item {
  display: flex;
  align-items: center;
  gap: 10px;
  cursor: pointer;
  transition: transform 0.2s;
}

.supplier-item:hover {
  transform: translateX(3px);
}

.supplier-flag {
  width: 20px;
  height: auto;
  border-radius: 2px;
}

.supplier-info {
  display: flex;
  flex-direction: column;
}

.supplier-info .country {
  font-size: 14px;
  font-weight: 500;
  color: #333;
  margin-bottom: 2px;
}

.supplier-info .domain {
  font-size: 12px;
  color: #888;
}

/* Newsletter Section */
.newsletter-section {
  margin: 20px 40px;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  border-radius: 8px;
  padding: 40px;
  text-align: center;
}

.newsletter-content h3 {
  font-size: 24px;
  color: #333;
  font-weight: bold;
  margin-bottom: 10px;
}

.newsletter-content p {
  font-size: 16px;
  color: #666;
  margin-bottom: 30px;
}

.newsletter-form {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
  max-width: 400px;
  margin: 0 auto;
}

.email-input-wrapper {
  position: relative;
  flex: 1;
}

.email-input-wrapper i {
  position: absolute;
  left: 12px;
  top: 50%;
  transform: translateY(-50%);
  color: #888;
  font-size: 14px;
}

.newsletter-email {
  width: 100%;
  padding: 12px 12px 12px 35px;
  border: 1px solid #ddd;
  border-radius: 6px;
  font-size: 14px;
  outline: none;
}

.newsletter-btn {
  background-color: #007bff;
  color: white;
  padding: 12px 24px;
  border: none;
  border-radius: 6px;
  font-size: 14px;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.2s;
}

.newsletter-btn:hover {
  background-color: #0056b3;
}

/* Footer Section */
.footer-section {
  margin: 20px 40px;
  background-color: white;
  border-radius: 8px;
  padding: 40px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.footer-content {
  display: flex;
  gap: 40px;
  margin-bottom: 30px;
}

.footer-left {
  flex: 1;
  max-width: 300px;
}

.footer-brand {
  display: flex;
  align-items: center;
  font-size: 20px;
  font-weight: bold;
  color: #80b3ff;
  margin-bottom: 15px;
}

.footer-brand i {
  font-size: 24px;
  margin-right: 8px;
  background-color: #3399ff;
  padding: 8px;
  border-radius: 8px;
  color: white;
}

.footer-left p {
  font-size: 14px;
  color: #666;
  line-height: 1.5;
  margin-bottom: 20px;
}

.social-icons {
  display: flex;
  gap: 15px;
}

.social-icons i {
  width: 35px;
  height: 35px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f0f0f0;
  border-radius: 50%;
  color: #666;
  font-size: 16px;
  cursor: pointer;
  transition: all 0.2s;
}

.social-icons i:hover {
  background-color: #007bff;
  color: white;
  transform: translateY(-2px);
}

.footer-columns {
  display: flex;
  flex: 2;
  gap: 40px;
}

.footer-column {
  flex: 1;
}

.footer-column h4 {
  font-size: 16px;
  font-weight: bold;
  color: #333;
  margin-bottom: 15px;
}

.footer-column ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.footer-column li {
  margin-bottom: 8px;
}

.footer-column a {
  text-decoration: none;
  color: #666;
  font-size: 14px;
  transition: color 0.2s;
}

.footer-column a:hover {
  color: #007bff;
}

.app-buttons {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.app-button {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 8px 12px;
  border: 1px solid #ddd;
  border-radius: 6px;
  cursor: pointer;
  transition: all 0.2s;
  background-color: #f8f9fa;
}

.app-button:hover {
  background-color: #e9ecef;
  transform: translateY(-1px);
}

.app-button i {
  font-size: 20px;
  color: #333;
}

.app-text {
  display: flex;
  flex-direction: column;
}

.app-text .small {
  font-size: 10px;
  color: #666;
  line-height: 1;
}

.app-text .large {
  font-size: 12px;
  font-weight: bold;
  color: #333;
  line-height: 1;
}

.footer-bottom {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 20px;
  border-top: 1px solid #eee;
  font-size: 14px;
  color: #666;
}

.language-selector {
  display: flex;
  align-items: center;
  gap: 8px;
  cursor: pointer;
}

.lang-flag {
  width: 16px;
  height: auto;
}

.language-selector i {
  font-size: 12px;
}


/*myWeb2.html CSS Code*/

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background: #f4f4f4;
  color: #333;
}

.top-header, .nav-icons2, .breadcrumb, .main-section, .tabs-section, .related-products, .footer, .bottom-bar {
  width: 100%;
}

.top-header {
  display: flex;
  justify-content: space-between;
  padding: 10px 20px;
  background: #fff;
  border-bottom: 1px solid #ccc;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: #007bff;
}

.search-section {
  display: flex;
  gap: 10px;
  flex: 1;
  margin: 0 20px;
}

.search-section input, .search-section select {
  padding: 8px;
  border: 1px solid #ccc;
}

.search-section button {
  background: #007bff;
  color: white;
  padding: 8px 12px;
  border: none;
}

.nav-icons {
  display: flex;
  gap: 12px;
  font-size: 14px;
}

.nav-icons2 {
  display: flex;
  gap: 10px;
  background: #ededed;
  padding: 10px 20px;
  align-items: center;
  font-weight: 500;
}

.nav-bar2 {
  margin-left: auto;
  display: flex;
  align-items: center;
  gap: 10px;
}

.breadcrumb {
  padding: 10px 20px;
  background: #f8f8f8;
  font-size: 14px;
}

.main-section {
  display: flex;
  padding: 20px;
  background: #fff;
  flex-wrap: wrap;
}

.left-column, .middle-column, .right-column {
  padding: 10px;
}

.left-column {
  flex: 1;
  min-width: 300px;
}

.main-image {
  width: 100%;
  max-width: 400px;
}

.thumbs {
  display: flex;
  gap: 10px;
  margin-top: 10px;
}

.thumbs img {
  width: 60px;
  border: 1px solid #ccc;
  cursor: pointer;
}

.middle-column {
  flex: 2;
  min-width: 300px;
}

.middle-column h2 {
  margin-bottom: 10px;
}

.rating {
  margin-bottom: 10px;
}

.price-box {
  display: flex;
  gap: 15px;
  background: #fff6ef;
  padding: 10px;
  border-left: 5px solid orange;
  margin-bottom: 10px;
}

.price-box div {
  color: #e67e22;
  font-weight: bold;
}

.price-box span {
  font-size: 12px;
  color: #555;
}

.product-info p {
  margin: 5px 0;
}

.right-column {
  flex: 1;
  max-width: 300px;
}

.supplier-box {
  border: 1px solid #ccc;
  padding: 15px;
  background: #fff;
}

.supplier-box button {
  background: #007bff;
  color: white;
  padding: 8px;
  border: none;
  margin-top: 10px;
  width: 100%;
}

.tabs-section {
  background: #fff;
  padding: 20px;
  margin: 20px auto;
  max-width: 1200px;
}

.tabs {
  display: flex;
  gap: 20px;
  margin-bottom: 15px;
  font-weight: bold;
}

.tabs span.active {
  color: #007bff;
  border-bottom: 2px solid #007bff;
}

.tabs-flex-container {
  display: flex;
  gap: 30px;
  flex-wrap: wrap;
  position: relative;
}

.tab-content {
  flex: 1;
  min-width: 500px;
  padding-right: 20px;
  border-right: 2px solid #ddd;
}

.tab-section2 {
  width: 300px;
  padding-left: 20px;
  display: flex;
  flex-direction: column;
  gap: 20px;
  background-color: #fff;
}

.tab-section2 h3 {
  font-size: 16px;
  margin-bottom: 10px;
  color: #444;
  text-align: center;
}

.product-item {
  display: flex;
  align-items: center;
  gap: 15px;
  border-bottom: 1px solid #eee;
  padding-bottom: 10px;
}

.product-item img {
  width: 80px;
  height: 80px;
  object-fit: cover;
  border: 1px solid #ccc;
  background: #fafafa;
  padding: 3px;
  border-radius: 5px;
}

.product-details {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.product-name {
  font-size: 14px;
  font-weight: 600;
  color: #222;
}

.product-price {
  font-size: 13px;
  color: #596470;
}

.tab-section2 img {
  width: 75px;
  height: 75px;
  object-fit: cover;
  border: 1px solid #ddd;
  background: #fafafa;
  padding: 5px;
}

.related-products {
  background: white;
  padding: 20px;
}

.product-cards {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  justify-content: space-evenly;
}

.card {
  background: white;
  border: 1px solid #ddd;
  padding: 10px;
  text-align: center;
  width: 200px;
}

.card img {
  width: 100%;
  height: auto;
}

/*.footer {
  display: flex;
  justify-content: space-evenly;
  background: #f8f8f8;
  padding: 20px;
  flex-wrap: wrap;
}

.footer-section {
  margin: 10px;
  font-size: 14px;
  color: #555;
}*/

.bottom-bar {
  display: flex;
  justify-content: space-between;
  background: #ededed;
  padding: 10px 20px;
}

.tab-content table{
    width: 520px;
    height: 200px;
    border: 1px solid black;
}

tr{
    border: 1px solid black;
}

td{
    border: 1px solid black;
}


/*myWeb3.html CSS Code*/

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background: #f5f7fa;
}

.top-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  background: #fff;
  border-bottom: 1px solid #ddd;
}

.logo {
  font-size: 22px;
  font-weight: bold;
  color: #007bff;
}

.search-box {
  display: flex;
  flex: 1;
  margin: 0 20px;
}

.search-box select, .search-box input {
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.search-box button {
  background: #007bff;
  color: white;
  border: none;
  padding: 8px 16px;
  margin-left: 10px;
  border-radius: 4px;
}

.header-icons {
  display: flex;
  gap: 15px;
  font-size: 14px;
}

.sub-nav {
  display: flex;
  justify-content: space-between;
  padding: 10px 20px;
  background: #fff;
  font-size: 14px;
  border-bottom: 1px solid #ddd;
}

.sub-nav ul {
  display: flex;
  list-style: none;
  gap: 15px;
}

.breadcrumb {
  padding: 10px 20px;
  font-size: 13px;
  color: gray;
}

.container {
  display: flex;
  padding: 20px;
}

.sidebar {
  width: 220px;
  background: #fff;
  padding: 20px;
  border-radius: 5px;
  border: 1px solid #ddd;
  font-size: 14px;
}

.sidebar h3 {
  margin: 15px 0 10px;
  font-size: 14px;
}

.sidebar ul {
  list-style: none;
}

.sidebar ul li {
  margin: 5px 0;
  color: #007bff;
  cursor: pointer;
}

.sidebar label {
  display: block;
  margin: 6px 0;
}

.product-area {
  flex: 1;
  margin-left: 20px;
}

.filters-bar {
  display: flex;
  justify-content: space-between;
  background: #fff;
  padding: 15px 20px;
  border-radius: 5px;
  margin-bottom: 10px;
}

.filters-actions {
  display: flex;
  align-items: center;
  gap: 15px;
}

.filter-tags {
  background: #fff;
  padding: 10px 20px;
  margin-bottom: 20px;
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.filter-tags span {
  background: #e5e7eb;
  padding: 5px 10px;
  border-radius: 5px;
  font-size: 12px;
}

.clear-filter {
  margin-left: auto;
  color: #007bff;
  font-size: 13px;
}

.product-grid {
  display: flex;
  grid-template-columns: repeat(3, 1fr);
  gap: 40px;
  margin-top: 5px;
}

.product-card {
  background: #fff;
  padding: 15px;
  text-align: center;
  border: 1px solid #ddd;
  border-radius: 5px;
}

.product-card img {
  width: 180px;
  height: 180px;
  object-fit: cover;
  margin-bottom: 10px;
}

.product-card .old-price {
  text-decoration: line-through;
  color: gray;
  font-size: 12px;
  margin-left: 5px;
}

.stars {
  margin: 5px 0;
  color: orange;
  font-size: 13px;
}

.pagination {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin-top: 20px;
}

.pagination button {
  padding: 5px 10px;
  border: 1px solid #ccc;
  background: white;
  cursor: pointer;
}

.newsletter {
  text-align: center;
  background: #fff;
  padding: 30px 20px;
  margin-top: 40px;
}

.newsletter input {
  padding: 10px;
  width: 250px;
  border: 1px solid #ccc;
  border-radius: 3px;
  margin-right: 10px;
}

.newsletter button {
  padding: 10px 20px;
  background: #007bff;
  color: white;
  border: none;
  border-radius: 3px;
}

footer {
  background: #fff;
  padding: 40px 20px;
  border-top: 1px solid #ddd;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.footer-brand {
  width: 25%;
}

.footer-columns {
  display: flex;
  gap: 30px;
}

.footer-columns div a {
  display: block;
  margin-bottom: 5px;
  color: #007bff;
  text-decoration: none;
}

.footer-bottom {
  display: flex;
  justify-content: space-between;
  padding-top: 20px;
  border-top: 1px solid #ddd;
  margin-top: 20px;
  font-size: 13px;
}

.language-selector img {
  width: 20px;
  height: 14px;
  margin-right: 5px;
}

/*myWeb4.html CSS Code*/
.filters-bar{
    background-color: #fff;
    width: 1100px;
    height: 40px;
    display: flex;
    text-align: center;
    align-items: center;
    border-radius: 3px;
}
.main-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 20px;
  border-bottom: 1px solid #ddd;
  background-color: #fff;
}

.left-section {
  display: flex;
  align-items: center;
  gap: 20px;
}

.logo {
  font-size: 20px;
  font-weight: bold;
}

.search-area {
  display: flex;
  align-items: center;
  gap: 10px;
}

.search-area input {
  width: 250px;
  padding: 8px 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.search-area select {
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.search-area button {
  padding: 8px 15px;
  background: #007bff;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.right-section {
  display: flex;
  align-items: center;
  gap: 20px;
  font-size: 14px;
}

.right-section a {
  color: #555;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 5px;
}

.right-section .language,
.right-section .ship-to {
  display: flex;
  align-items: center;
  gap: 5px;
  cursor: pointer;
}

.ship-to img {
  width: 20px;
  height: 14px;
}

.navigation-bar {
  /*gap: 20px;*/
  height: fit-content;
  padding: 10px 20px;
  background: #f7f7f7;
  border-bottom: 1px solid #ddd;
  font-size: 14px;
}

.navigation-bar a {
  text-decoration: none;
  color: #555;
  display: flex;
  align-items: center;
  gap: 5px;
}

.breadcrumb {
  padding: 10px 20px;
  font-size: 14px;
  color: #777;
}

.sidebar {
  width: 250px;
  height: 1108px;
  padding: 20px;
  background: #fff;
  border: 1px solid #ddd;
  border-radius: 5px;
  font-size: 14px;
  margin-top: 60px;
}

.sidebar h3 {
  font-size: 14px;
  font-weight: bold;
  margin-top: 20px;
  margin-bottom: 10px;
  cursor: pointer;
  position: relative;
}

.sidebar h3::after {
  content: "▼";
  position: absolute;
  right: 0;
  font-size: 10px;
  transform: rotate(0deg);
  transition: transform 0.3s ease;
}

.sidebar ul {
  list-style: none;
  margin-left: 0;
}

.sidebar ul li {
  margin-bottom: 8px;
  padding-left: 10px;
  color: #555;
  cursor: pointer;
}

.sidebar label {
  display: flex;
  align-items: center;
  margin-bottom: 8px;
  color: #555;
  padding-left: 10px;
}

.sidebar input[type="checkbox"], 
.sidebar input[type="radio"] {
  margin-right: 8px;
}

.price-range {
  margin-top: 15px;
  padding-left: 10px;
}

.price-range input {
  width: 80px;
  margin-right: 10px;
  padding: 5px;
}

.apply-btn {
  padding: 5px 10px;
  background: #007bff;
  color: #fff;
  border: none;
  border-radius: 3px;
  cursor: pointer;
}

.sidebar .ratings {
  display: flex;
  flex-direction: column;
  padding-left: 10px;
}

.sidebar .ratings label {
  margin-bottom: 5px;
}

/* Optional: Collapse Effect JS controlled */
.collapsed::after {
  transform: rotate(-90deg);
}

.product-list {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.product-list-item {
  display: flex;
  background: white;
  padding: 15px;
  border: 1px solid #ddd;
  border-radius: 5px;
}

.product-list-item img {
  width: 120px;
  height: 120px;
  object-fit: cover;
  margin-right: 20px;
}

.product-info h4 {
  margin-bottom: 10px;
}

.product-info .price {
  font-weight: bold;
}

.green {
  color: green;
}

.details-link {
  display: inline-block;
  margin-top: 10px;
  color: #007bff;
  text-decoration: none;
}

.newsletter-banner {
  background: #f7f7f7;
  text-align: center;
  padding: 30px 20px;
  margin-top: 40px;
}

.newsletter-banner h3 {
  font-size: 20px;
  margin-bottom: 10px;
}

.newsletter-banner p {
  color: #555;
  margin-bottom: 20px;
}

.newsletter-input {
  display: flex;
  justify-content: center;
}

.newsletter-input input {
  width: 250px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 3px 0 0 3px;
}

.newsletter-input button {
  padding: 10px 20px;
  background: #007bff;
  color: #fff;
  border: none;
  border-radius: 0 3px 3px 0;
  cursor: pointer;
}

/* Footer Section */
.footer {
  background: #fff;
  border-top: 1px solid #ddd;
  padding: 40px 20px 20px;
}

.footer-content {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 20px;
}

.footer-brand {
  width: 20%;
  min-width: 200px;
}

.footer-brand .logo {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 10px;
}

.footer-brand p {
  font-size: 14px;
  color: #555;
  margin-bottom: 15px;
}

.social-icons i {
  margin-right: 10px;
  color: #555;
  cursor: pointer;
}

.footer-columns {
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
  width: 75%;
}

.footer-columns div {
  min-width: 120px;
}

.footer-columns h4 {
  font-size: 14px;
  margin-bottom: 10px;
}

.footer-columns a {
  display: block;
  margin-bottom: 6px;
  color: #007bff;
  text-decoration: none;
}

.app-link {
  width: 120px;
  margin-bottom: 10px;
}

/* Bottom Footer */
.footer-bottom {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 1px solid #ddd;
  padding-top: 20px;
  margin-top: 20px;
  font-size: 14px;
  color: #777;
}

.language-selector {
  display: flex;
  align-items: center;
  cursor: pointer;
}

.language-selector img {
  width: 20px;
  height: 14px;
  margin-right: 8px;
}

/*myWeb5.html CSS Code*/

.cart-page {
  display: flex;
  justify-content: space-between;
}

.cart-items {
  width: 65%;
}

.cart-item {
  background: white;
  padding: 15px;
  margin-bottom: 15px;
  border: 1px solid #ddd;
  border-radius: 5px;
  display: flex;
  justify-content: space-between;
}

.remove-btn, .save-btn {
  margin-top: 5px;
  padding: 5px 10px;
  background: #f0f0f0;
  border: none;
  cursor: pointer;
}

.cart-summary {
  width: 30%;
  background: white;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 5px;
}

.summary-details p {
  margin: 10px 0;
}

.checkout-btn {
  width: 100%;
  padding: 10px;
  background: green;
  color: white;
  border: none;
  cursor: pointer;
}

.saved-items {
  margin: 40px 20px;
}

.saved-products {
  display: flex;
  gap: 15px;
}

.saved-item {
  background: white;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
}


//mobileResponsive.css file

/* ========== MEDIA QUERIES ========== */

/* Tablets and small laptops (1024px and below) */

@media (max-width: 1024px) {
  .deals-grid {
    grid-template-columns: repeat(3, 1fr);
  }
  
  .product-grid {
    grid-template-columns: repeat(3, 1fr);
  }
  
  .recommended-grid {
    grid-template-columns: repeat(4, 1fr);
  }
  
  .services-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .supplier-row {
    grid-template-columns: repeat(3, 1fr);
  }
}

/* Larger phones and small tablets (768px and below) */
@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
    gap: 15px;
    padding: 15px;
  }
  
  .search-bar {
    width: 100%;
    margin: 10px 0;
  }
  
  .nav-icons {
    width: 100%;
    justify-content: space-between;
  }
  
  .top-navbar {
    flex-direction: column;
    gap: 10px;
    padding: 10px 20px;
  }
  
  .promo-section {
    flex-direction: column;
    padding: 20px;
  }
  
  .promo-categories,
  .promo-banner,
  .promo-right {
    width: 100%;
  }
  
  .promo-banner {
    background-position: center;
    padding: 30px 20px;
    margin-bottom: 20px;
  }
  
  .promo-banner h2 {
    font-size: 22px;
  }
  
  .deals-section {
    flex-direction: column;
    margin: 20px;
  }
  
  .deals-left {
    width: 100%;
    text-align: center;
    padding: 20px;
  }
  
  .timer {
    justify-content: center;
  }
  
  .deals-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .product-section {
    flex-direction: column;
    margin: 20px;
  }
  
  .section-left {
    width: 100%;
    padding: 20px;
  }
  
  .product-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .recommended-section {
    margin: 20px;
    padding: 20px;
  }
  
  .recommended-grid {
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
  }
  
  .quote-section {
    flex-direction: column;
    margin: 20px;
    padding: 30px 20px;
    gap: 20px;
  }
  
  .quote-form-container {
    min-width: unset;
    width: 100%;
    padding: 20px;
  }
  
  .services-section,
  .suppliers-section,
  .newsletter-section,
  .footer-section {
    margin: 20px;
    padding: 20px;
  }
  
  .services-grid {
    grid-template-columns: 1fr;
    gap: 15px;
  }
  
  .supplier-row {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .newsletter-form {
    flex-direction: column;
    gap: 15px;
  }
  
  .footer-content {
    flex-direction: column;
    gap: 30px;
  }
  
  .footer-columns {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
  }
  
  .footer-bottom {
    flex-direction: column;
    gap: 15px;
    text-align: center;
  }
}

/* Mobile phones (480px and below) */
@media (max-width: 480px) {
  .brand {
    font-size: 20px;
  }
  
  .search-bar {
    flex-direction: column;
  }
  
  .search-bar input,
  .search-bar select,
  .search-bar button {
    border-radius: 4px;
    margin-bottom: 5px;
    width: 100%;
  }
  
  .top-navbar .top-left,
  .top-navbar .top-right {
    flex-direction: column;
    gap: 10px;
    align-items: flex-start;
  }
  
  .deals-grid {
    grid-template-columns: 1fr;
  }
  
  .product-grid {
    grid-template-columns: 1fr;
  }
  
  .product-card {
    flex-direction: column;
    text-align: center;
    gap: 8px;
  }
  
  .recommended-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .recommended-info h4,
  .recommended-info .price {
    text-align: center;
  }
  
  .form-row {
    flex-direction: column;
    gap: 10px;
  }
  
  .supplier-row {
    grid-template-columns: 1fr;
  }
  
  .footer-columns {
    grid-template-columns: 1fr;
  }
  
  .footer-bottom {
    text-align: center;
  }
}


/* ========== RESPONSIVE FOR OTHER PAGES ========== */

/* myWeb2.html Responsive Styles */
@media (max-width: 768px) {
  .main-section {
    flex-direction: column;
  }
  
  .left-column, .middle-column, .right-column {
    width: 100%;
    max-width: 100%;
  }
  
  .thumbs {
    justify-content: center;
  }
  
  .tabs-flex-container {
    flex-direction: column;
  }
  
  .tab-content {
    min-width: 100%;
    border-right: none;
    padding-right: 0;
    margin-bottom: 20px;
  }
  
  .tab-section2 {
    width: 100%;
    padding-left: 0;
  }
  
  .product-cards {
    justify-content: center;
  }
  
  .card {
    width: 45%;
    margin-bottom: 15px;
  }
}

@media (max-width: 480px) {
  .top-header, .nav-icons2 {
    flex-direction: column;
    gap: 10px;
    align-items: flex-start;
  }
  
  .nav-bar2 {
    margin-left: 0;
    width: 100%;
    justify-content: space-between;
  }
  
  .card {
    width: 100%;
  }
  
  .footer {
    flex-direction: column;
    gap: 20px;
  }
}


/* myWeb3.html Responsive Styles */
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
  
  .sidebar {
    width: 100%;
    margin-bottom: 20px;
  }
  
  .product-area {
    margin-left: 0;
  }
  
  .filters-bar {
    flex-direction: column;
    gap: 15px;
  }
  
  .product-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .footer-content {
    flex-direction: column;
    gap: 30px;
  }
  
  .footer-brand {
    width: 100%;
  }
}

@media (max-width: 480px) {
  .top-header {
    flex-direction: column;
    gap: 15px;
  }
  
  .search-box {
    flex-direction: column;
    gap: 10px;
    margin: 0;
  }
  
  .search-box select, 
  .search-box input, 
  .search-box button {
    width: 100%;
    margin-left: 0;
  }
  
  .sub-nav ul {
    flex-wrap: wrap;
    gap: 10px;
  }
  
  .product-grid {
    grid-template-columns: 1fr;
  }
  
  .footer-columns {
    flex-direction: column;
    gap: 20px;
  }
}

/* myWeb4.html Responsive Styles */
@media (max-width: 768px) {
  .main-header {
    flex-direction: column;
    gap: 15px;
  }
  
  .left-section, .right-section {
    width: 100%;
    justify-content: center;
  }
  
  .search-area {
    width: 100%;
  }
  
  .search-area input {
    width: 100%;
  }
  
  .container {
    flex-direction: column;
  }
  
  .sidebar {
    width: 100%;
    height: auto;
    margin-top: 20px;
  }
  
  .product-list-item {
    flex-direction: column;
    text-align: center;
  }
  
  .product-list-item img {
    margin-right: 0;
    margin-bottom: 15px;
  }
  
  .filters-bar {
    width: 100%;
  }
  
  .footer-content {
    flex-direction: column;
    gap: 30px;
  }
  
  .footer-brand {
    width: 100%;
  }
  
  .footer-columns {
    width: 100%;
  }
}

@media (max-width: 480px) {
  .navigation-bar {
    flex-direction: column;
    gap: 10px;
  }
  
  .newsletter-input {
    flex-direction: column;
  }
  
  .newsletter-input input {
    width: 100%;
    border-radius: 3px;
    margin-bottom: 10px;
  }
  
  .newsletter-input button {
    width: 100%;
    border-radius: 3px;
  }
  
  .footer-bottom {
    flex-direction: column;
    gap: 15px;
    text-align: center;
  }
}

/* myWeb5.html Responsive Styles */
@media (max-width: 768px) {
  .cart-page {
    flex-direction: column;
  }
  
  .cart-items {
    width: 100%;
    margin-bottom: 20px;
  }
  
  .cart-summary {
    width: 100%;
  }
  
  .cart-item {
    flex-direction: column;
    gap: 15px;
  }
  
  .saved-products {
    flex-direction: column;
  }
}

@media (max-width: 480px) {
  .cart-item {
    padding: 10px;
  }
  
  .saved-item {
    width: 100%;
  }
}


