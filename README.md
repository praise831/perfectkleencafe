[T.PUMPY CONCEPT.html](https://github.com/user-attachments/files/22176114/T.PUMPY.CONCEPT.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PERFECTKLEEN-HENSHAW</title>

  <!-- Favicon -->
  <link rel="icon" type="image/png" href="https://i.postimg.cc/wBkbyv7j/create-an-image-of-henshaw-s-perfectkleen-cybercafe.jpg">

  <!-- Google Fonts & Icons -->
<link rel="icon" type="image/png" href="https://i.postimg.cc/wBkbyv7j/create-an-image-of-henshaw-s-perfectkleen-cybercafe.jpg">

  <link href="https://fonts.googleapis.com/css?family=Open+Sans:400,600,700&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <meta name="description" content="Cybercafe, Printing, Photocopy, Lamination, Exams in Nigeria.">
  <meta name="keywords" content="cybercafe, printing, photocopy, lamination, CBT, online exams, Nigeria">
  <meta name="author" content="HENSHAW's PERFECTKLEEN">
  <script async src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXXXX-X"></script>
  <style>
/* Spinner animation */
.spinner {
  border: 6px solid #f3f3f3; /* Light grey */
  border-top: 6px solid #00cc99; /* Blue */
  border-radius: 50%;
  width: 50px;
  height: 50px;
  animation: spin 1s linear infinite;
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
     /* Global Styles */
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: #f8f8f8;
      color: #333;
      scroll-behavior: smooth;

    }
    a { text-decoration: none; color: inherit; }

    h2.section-title {
      font-size: 36px;
      text-align: center;
      margin: 30px 0 10px;
      color: #333;
      position: relative;
    }
    h2.section-title::after {
      content: "";
      display: block;
      width: 80px;
      height: 4px;
      background: #00cc99;
      margin: 10px auto;
      border-radius: 2px;
    }

    /* Header */
    #header {
      background: linear-gradient(90deg, #111, #444);
      color: #fff;
      padding: 10px 50px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      height:70px;
      z-index: 1000;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
    #header .logo-container {
      display: flex;
      align-items: center;
      gap: 15px;
    }
    #header img {
      height: 55px;
      width: 55px;
      border-radius: 50%;
      object-fit: cover;
      border: 2px solid #fff;
    }
    #header h1 {
      margin: 0;
      font-size: 40px;
      letter-spacing: 2px;
      font-weight: 700;
      text-shadow:2px 2px 5px #00ffcc;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      margin: 0;
text-shadow:2px 2px 5px #00ffcc;
      padding: 0;
    }
 body.dark-theme {
      background: #333;
      color: #fff;
    }
    
    nav ul li a {
      color: #fff;
      font-weight: 600;
      display: flex;
text-shadow:2px 2px 5px #00ffcc;
      align-items: center;
      gap: 5px;
      padding: 8px 12px;
      border-radius: 5px;
      transition: background 0.3s, color 0.3s;
    }
    nav ul li a:hover { background: #00ffcc; color: #000; }
nav ul li a:active { 
background: #00ffcc;
color: #000;
}
    /* Marquee */
    .marquee-container {
      background: #000;
      color: #fff;
text-shadow:2px 2px 5px #00ffcc;
      font-size: 18px;
      font-weight: bold;
      padding: 8px 0;
      overflow: hidden;
      white-space: nowrap;
    }
    .marquee-text {
      display: inline-block;
      padding-left: 100%;
      animation: scroll-left 12s linear infinite;
    }
    @keyframes scroll-left {
      0% { transform: translateX(0); }
      100% { transform: translateX(-100%); }
    }

    /* Hero Section */
    .hero {
      position: relative;
      text-align: center;
      height: 85vh;
      color: #fff;
text-shadow:2px 2px 5px #00ffcc;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      overflow: hidden;
    }
    .hero-bg {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-size: cover;
      background-position: center;
      opacity: 0;
      transition: opacity 1s ease-in-out;
      z-index: -1;
    }
 body.dark-theme .package-card {
      color: black;
    }
   body.dark-theme #testimonials{
      color: black;
	background:#444;
    }
    body.dark-theme .section-title {
      color: #fff;
    }
    body.dark-theme #faq {
      background: #444;
color:#fff;
    }
     body.dark-theme .testimonial active{
 background:  #00cc99;
}
    body.dark-theme .service-card {
      background: #444;
      color: #fff;
    }
    
    body.dark-theme .rates-table th {
      background: #00cc99;
      color: #fff;
    }
    
    body.dark-theme .rates-table td {
      background:#fff;
      color: #444;
      border-color: #666;
    }
 body.dark-theme #toggleText{
  background:#fff;
      color: #444;
      border-color: #666;
}
    .hero-bg.active { opacity: 1; }
    .hero h2 {
      font-size: 50px;
      background: rgba(0,0,0,0.7);
      padding: 15px 25px;
      border-radius: 10px;
      animation: fadeIn 2s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }


    /* Sections Common */
    section { padding: 50px 20px; }

    /* Services Section */
    #service-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
     margin-top: 30px; 
    }
    #service-card {
      background: #f9f9f9;
      border-radius: 10px;
      padding: 20px;
margin-top:0;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
      text-align: center;
    }
    #service-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }
   
    }
    /* Sections Common */
    section { padding: 50px 20px; }

    /* Services Section */
    .service-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
     margin-top: 50px; 
    }
    .service-card {
      background: #f9f9f9;
      border-radius: 10px;
      padding: 20px;
margin-top:20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
      text-align: center;
    }
    .service-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }
    .service-card i {
      font-size: 40px;
      color: #00cc99;
      margin-bottom: 10px;
    }

    /* Rates */
    .rates-table {
      width: 100%;
      max-width: 600px;
      margin: 20px auto;
      border-collapse: collapse;
      background: #fff;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .rates-table th, .rates-table td {
      border: 1px solid #ddd;
      padding: 12px;
      text-align: center;
    }
    .rates-table th {
      background: #00cc99;
      color: #fff;
    }

    /* Packages */
    .packages-container {
      display: grid;
     margin-top: 40px;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
 
    }
    .package-card {
      background: #e6fff9;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s;
    }
    .package-card:hover { transform: translateY(-5px); }
    .package-card i {
      font-size: 40px;
      color: #00cc99;
      margin-bottom: 10px;
    }

    /* Gallery */
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }
    .gallery-grid img {
      width: 100%;
      border-radius: 10px;
      height: 180px;
      object-fit: cover;
      transition: transform 0.3s;
    }
    .gallery-grid img:hover { transform: scale(1.05); }

    /* Forms */
    form {
      background: linear-gradient(135deg, #ffffff, #e6fffa);
      padding: 30px;
      border-radius: 15px;
      max-width: 600px;
      margin: 20px auto;
      box-shadow: 0 10px 25px rgba(0, 204, 153, 0.2);
      transition: transform 0.3s ease;
      animation: slideFadeIn 0.8s ease-in-out;
    }
    form:hover { transform: scale(1.01); }
    @keyframes slideFadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
}
    
    form input,
    form textarea,
    form select {
      padding: 14px 16px;
      margin-bottom: 15px;
      width: 90%;
      border: 1px solid #00cc99;
      border-radius: 8px;
      font-size: 16px;
      outline: none;
      column; gap: 7px;
      margin: 7px auto;
      padding: 20px;
      display: flex; flex-direction:
      background: #fefefe;
      transition: border-color 0.3s, box-shadow 0.3s;
    }


    form input:focus,
    form textarea:focus,
    form select:focus {
      border-color: #009973;
      box-shadow: 0 0 6px rgba(0, 204, 153, 0.5);
    }
    form textarea { resize: vertical; min-height: 120px; }
    form button {
      background: #00cc99;
      color: #fff;
      padding: 14px 22px;
      font-size: 16px;
width:100%;
margin-top:7px;
      font-weight: bold;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s, transform 0.3s;
    }
    form button:hover {
      background: #009973;
      transform: translateY(-2px);
    }

    /* FAQ */
  /* FAQ Section */
#faq {
  background: #f9f9f9;
  padding: 50px 20px;
  border-radius: 10px;
}

.faq-container {
  max-width: 800px;
  margin: 0 auto;
}

.faq-item {
  margin-bottom: 15px;
  border: 1px solid #ddd;
  border-radius: 8px;
  background: #fff;
  transition: box-shadow 0.3s;
  overflow: hidden;
}

.faq-item:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.faq-question {
  padding: 15px;
  background: #00cc99;
  color: #fff;
  font-weight: bold;
  cursor: pointer;
  position: relative;
  transition: background 0.3s;
}

.faq-question::after {
  content: '+';
  position: absolute;
  right: 20px;
  font-size: 20px;
  transition: transform 0.3s;
}

.faq-item.active .faq-question::after {
  content: '-';
  transform: rotate(180deg);
}

.faq-answer {
  display: none;
  padding: 15px;
  background: #fefefe;
  color: #333;
  font-size: 15px;
  line-height: 1.6;
}

.faq-item.active .faq-answer {
  display: block;
}

    /* Footer */
    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      box-shadow: 0 -2px 6px rgba(0,0,0,0.3);
    }
    footer .social-icons a {
      color: #fff;
      margin: 0 10px;
      font-size: 20px;
      transition: color 0.3s;
    }
td{
font-weight:900;
font-family:'garamond', serif;
font-size:20px;
}
    footer .social-icons a:hover { color: #00cc99; }

    /* Floating Buttons */
    .login-btn, .whatsapp-btn {
      position: fixed;
      right: 20px;
      padding: 14px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: transform 0.3s, box-shadow 0.3s;
      z-index: 999;
    }
    .login-btn { bottom: 80px; background: #00cc99; }
    .whatsapp-btn { bottom: 20px; background: #25D366; }
    .login-btn:hover, .whatsapp-btn:hover {
      transform: scale(1.1);
      box-shadow: 0 6px 12px rgba(0,0,0,0.4);
    }
 
    /* Modal */
    .modal {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0,0,0,0.8);
      align-items: center;
      justify-content: center;
      z-index: 10000;
    }
    .modal-content {
      background: #fff;
      padding: 25px;
      border-radius: 12px;
      width: 90%;
      max-width: 400px;
      text-align: center;
      animation: slideDown 0.4s ease;
      position: relative;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }
    @keyframes slideDown {
      from { transform: translateY(-60px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    .close-btn {
      position: absolute;
      top: 10px;
      right: 15px;
      font-size: 26px;
      cursor: pointer;
      color: #333;
    }

    /* Testimonials Section */
    #testimonials {
      background: #f0f8f7;
      padding: 50px 20px;
      text-align: center;
    }
    .testimonial-container {
      max-width: 700px;
      margin: 0 auto;
      position: relative;
    }
    .testimonial {
      display: none;
      font-size: 18px;
      line-height: 1.6;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: opacity 0.5s ease-in-out;
    }
    .testimonial.active {
      display: block;
    }
    .testimonial h4 {
      margin-top: 15px;
      font-size: 16px;
      color: #00cc99;
      font-weight: bold;
    }
    .testimonial-controls {
      margin-top: 15px;
    }


    .control-dot {
      height: 12px;
      width: 12px;
      margin: 0 4px;
      background-color: #ccc;
      border-radius: 50%;
      display: inline-block;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .control-dot.active {
      background-color: #00cc99;
    }
.hamburger {
  display: none;
  cursor: pointer;
}

.hamburger span {
  display: block;
  width: 25px;
  height: 3px;
  background-color: #fff;
  margin-bottom: 5px;
  transition: transform 0.3s;
}

.hamburger.active span:nth-child(1) {
  transform: rotate(45deg) translate(6px, 5px);
}

.hamburger.active span:nth-child(2) {
  opacity: 0;
}

.hamburger.active span:nth-child(3) {
  transform: rotate(-45deg) translate(6px, -5px);
}

#nav-links {
  display: flex;
  gap: 20px;
  margin: 0;
  padding: 0;
}

@media (max-width: 767px) {
  .hamburger {
    display: block;
  }

  #nav-links {
    display: none;
    position: absolute;
    top: 70px;
    left: 0;
    width: 100%;
    background-color: #333;
    padding: 20px;
    flex-direction: column;
    gap: 10px;
  }

  #nav-links.active {
    display: block;
  }
}

    /* Responsive */
    @media (max-width: 767px) {
      #header { flex-direction: column; padding: 10px 15px; }
      #header h1 { font-size: 28px; }
      nav ul { flex-direction: column; gap: 10px; margin-top: 10px; }
      .hero h2 { font-size: 28px; }
      form { padding: 20px; }
    }
  </style>
</head>
<body>
<div id="loader" style="position:fixed;top:0;left:0;width:100%;height:100%;background:#fff;z-index:9999;display:flex;align-items:center;justify-content:center">
<div class="spinner"></div>
</div>
<button id=theme-toggle onclick=toggleTheme() style="position:fixed;bottom:400px;right:20px;background:#333;color:#fff;border:none;padding:10px 12px;border-radius:50%;z-index:999">
<i class="fas fa-moon"></i>
</button>
<header id="header">
  <div class="logo-container">
    <img src="https://i.postimg.cc/wBkbyv7j/create-an-image-of-henshaw-s-perfectkleen-cybercafe.jpg" alt="HENSHAW's PERFECTKLEEN">
    <h1>HENSHAW's PERFECTKLEEN</h1>
  </div>
  <nav id="nav">
    <div class="hamburger" id="hamburger">
      <span></span>
      <span></span>
      <span></span>
    </div>
    <ul id="nav-links">
      <li><a href="#"><i class="fas fa-home"></i> Home</a></li>
      <li><a href="#services"><i class="fas fa-cogs"></i> Services</a></li>
      <li><a href="#rates"><i class="fas fa-tags"></i> Rates</a></li>
      <li><a href="#contact"><i class="fas fa-phone"></i> Contact</a></li>
    </ul>
  </nav>
</header><div class=marquee-container>
<span class=marquee-text>Sign Up / Login for more features</span>
</div>
<section class=hero id=heroSection>
<div class="hero-bg active" style="background-image:url('https://i.postimg.cc/YC5Y3xtr/imagine-a-printer-photocopy-and-lamination-machine.jpg')"></div>
<div class=hero-bg style="background-image:url('https://i.postimg.cc/XYqyKmTk/imagine-a-printer-photocopy-and-lamination-machine-1.jpg')"></div>
<div class=hero-bg style="background-image:url('https://i.postimg.cc/zGT6D2f8/imagine-a-printer-photocopy-and-lamination-machine-2.jpg')"></div>
<h2 class=typing id=typingText></h2>
</section>
<section id=services>
<h2 class=section-title>Our Services</h2>
<div class=service-grid>
<div class=service-card>
<i class="fas fa-wifi"></i>
<h3>Cybercafe</h3>
<p>High-speed internet, Online Exams, online registration, browsing, and more.</p>
</div>
<div class=service-card>
<i class="fas fa-print"></i>
<h3>Printing & Photocopy</h3>
<p>Clear and professional printing and photocopying services.</p>
</div>
<div class=service-card>
<i class="fas fa-graduation-cap"></i>
<h3>Graphics and Design </h3>
<p>Experts in Graphics and Design</p>
</div>
</div>

<div id="service-grid">
<div class="service-card">
<i class="fas fa-wifi"></i>
<h3>Painting and Production</h3>
<p>Dealers in all kinds of painting, designs and interior decoration.</p>
</div>
<div class=service-card>
<i class="fas fa-print"></i>
<h3>House Agent/ Caretaker service.</h3>
<p>Experts in house or land managements and capable of maintaining a good Landlord to Tenant relationship.</p>
</div>
<div class=service-card>
<i class="fas fa-graduation-cap"></i>
<h3>House Fumigation</h3>
<p>We aid in combatting against pest, insects and deadly animals in the homes through chemicals</p>
</div>
</div>
</section>

<section id=rates>
<h2 class=section-title>Rates</h2>
<table class=rates-table>
<tr><th>Service</th><th>Price</th></tr>
<tr><td>Browsing (per hour)</td><td>₦200</td></tr>
<tr><td>Printing (per page)</td><td>₦300</td></tr>
<tr><td>Photocopy (per page)</td><td>₦100</td></tr>
<tr><td>Lamination</td><td>₦300</td></tr>
<tr><td>Printing (per page)</td><td>₦50</td></tr>
<tr><td>Spiral Bind (per Spiral)</td><td>₦500</td></tr>
<tr><td>Hard Cover</td><td>₦7,000</td></tr>
<tr><td>Passport Photograph</td><td>₦2,000</td></tr>
<tr><td>Graphics Design</td><td>Fixed Amounts Depending On Qualities</td></tr>
</table>
</section>
<br>
<br>
<br>
<br>
<main>
<section id=newsletter>
<h2 class=section-title>Subscribe to Our Newsletter</h2>
<form class="X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*">
<input type=email placeholder="Enter your email" required>
<a href=mailto:praisehenshaw56@gmail.com aria-label=Email><button type=submit>Subscribe</button></a>
</form>
</section>
<section id=submit-testimonial>
<h2 class=section-title>Share Your Feedback</h2>
<form>
<input placeholder="Your Name" required>
<textarea placeholder="Your Testimonial" required></textarea>
<button type=submit><a href=mailto:praisehenshaw56@gmail.com aria-label=Email>Submit Testimonial</a></button>
</form>
</section>
<section id=location>
<h2 class=section-title>Visit Us</h2>
<div style=max-width:100%;overflow:hidden>
<iframe src="https://www.google.com/maps?q=hadex primary school,abule-eko,ijede,ikorodu,Lagos,Nigeria&output=embed" width=100% height=300 style=border:0 allowfullscreen loading=lazy></iframe>
</div>
</section>
</main>
<br>
<br>
<br>
<section id=packages>
<h2 class=section-title>Special Packages</h2>
<div class=packages-container>
<div class=package-card>
<i class="fas fa-user-graduate"></i>
<h3>Student Bundle</h3>
<p>Get 10% off for bulk printing of 50 pages or more.</p>
</div>
<div class=package-card>
<i class="fas fa-briefcase"></i>
<h3>Business Pack</h3>
<p>Special discounts for office document printing and scanning.</p>
</div>
<div class=package-card>
<i class="fas fa-users"></i>
<h3>Group Deals</h3>
<p>Group users enjoy free extra photocopy for every 100 pages.</p>
</div>
<div class=package-card>
<i class="fas fa-gift"></i>
<h3>Promotional Offer</h3>
<p>Free lamination for every 20 pages printed in one session.</p>
</div>
</div>
<br>
<br>
</section>
<section id=gallery>
<h2 class=section-title>Gallery</h2>
<div class=gallery-grid>
<img src=https://i.postimg.cc/YC5Y3xtr/imagine-a-printer-photocopy-and-lamination-machine.jpg alt="Printing Machine">
<img src=https://i.postimg.cc/XYqyKmTk/imagine-a-printer-photocopy-and-lamination-machine-1.jpg alt="Cyber Cafe">
<img src=https://i.postimg.cc/zGT6D2f8/imagine-a-printer-photocopy-and-lamination-machine-2.jpg alt="Lamination Service">
<img src=https://i.postimg.cc/R0PHvWYv/a-free-wifi-internet.jpg alt="Office Desk">
<img src=https://i.postimg.cc/dVYbLg4n/create-an-image-of-henshaw-s-perfectkleen-cybercafe-1.jpg alt="Printing Machine">
</div>
<br>
<br>
<br>
<br>
<br>
<br>
</section>
<section id=testimonials>
<h2 class=section-title>What Our Clients Say</h2>
<div class=testimonial-container>
<div class="testimonial active">
<p>"VICK-BIZ offers the best printing services at affordable rates. Always reliable!"</p>
<h4>- Chinedu A.</h4>
</div>
<div class=testimonial>
<p>"Their head dey touch."</p>
<h4>- HENSHAW E.</h4>
</div>
<div class=testimonial>
<p>"Their cybercafe is most reliable and secure. I personally recommend that it is without issues."</p>
<h4>- HENSHAW P.</h4>
</div>
<div class=testimonial>
<p>"Their cybercafe is great. "</p>
<h4>- HENSHAW N.</h4>
</div>
<div class=testimonial>
<p>"I always recommend them for their excellent customer service."</p>
<h4>- Peter O.</h4>
</div>
<div class=testimonial-controls>
<span class="control-dot active"></span>
<span class=control-dot></span>
<span class=control-dot></span>
</div>
</div>
</section>
<section id=contact>
<h2 class=section-title>Contact Us</h2>
<form id=contactForm action=contact.php method=post>
<input id=name name=name placeholder="Your Name" required>
<input type=email id=email name=email placeholder="Your Email" required>
<textarea id=message name=message placeholder="Your Message" required></textarea>
<button type=submit><a href=mailto:praisehenshaw56@gmail.com aria-label=Email>Send Message</a></button>
</form>
</section>
<section id=faq>
<h2 class=section-title>Frequently Asked Questions</h2>
<div class=faq-container>
<div class=faq-item>
<div class=faq-question>What are your opening hours?</div>
<div class=faq-answer>We are open Monday - Saturday from 7am to 9pm.</div>
</div>
<div class=faq-item>
<div class=faq-question>Do you offer bulk discounts?</div>
<div class=faq-answer>Yes, we offer discounts on bulk printing and photocopy orders.</div>
</div>
<div class=faq-item>
<div class=faq-question>Can I send files for printing online?</div>
<div class=faq-answer>Yes! You can email your files to us, and we’ll have them ready for pickup.</div>
</div>
<div class=faq-item>
<div class=faq-question>Do you provide lamination services?</div>
<div class=faq-answer>Yes, we offer lamination services for documents and photos.</div>
</div>
<div class=faq-item>
<div class=faq-question>Can I pre-book a computer for browsing?</div>
<div class=faq-answer>Absolutely. You can pre-book a slot via our booking form or contact us directly.</div>
</div>
<div class=faq-item>
<div class=faq-question>What payment methods do you accept?</div>
<div class=faq-answer>We accept cash, bank transfers, and mobile payments.</div>
</div>
<div class=faq-item>
<div class=faq-question>Do you offer express printing services?</div>
<div class=faq-answer>Yes! We offer express and same-day printing for urgent jobs.</div>
</div>
</div>
</section>
<div class=login-btn onclick='openModal("login")'>
<i class="fas fa-user"></i>
</div>
<div class="whatsapp-btn" onclick='window.open("https://wa.me/2347010976074","_blank")'>
<i class="fab fa-whatsapp"></i>
</div>
<div class=modal id=loginModal>
<div class=modal-content>
<span class=close-btn onclick=closeModal()>&times;</span>

<form id="loginForm">
  <h3>Login</h3>
  <input placeholder="Username" required>
  <input type="password" placeholder="Password" id="login-password" required>
  
  <label for="toggle-login-password" >
    <input type="checkbox" id="toggle-login-password">
    Show Password
  </label>
  
  <button type="submit">Login</button>
</form>
<form id="signupForm" >
  <h3>Sign Up</h3>
  <input name="fullname" placeholder="Full Name" required>
  <input type="email" placeholder="Email" required>
  <input type="password" placeholder="Password" id="signup-password" required>
  
  <label for="toggle-signup-password">
    <input type="checkbox" id="toggle-signup-password">
    Show Password
  </label>
  
  <button type="submit">Sign Up</button>
</form>
 <p id="toggleText">Don't have an account? <a href="#" onclick="switchForm('signup')"><b>Sign up</b></a></p>
</div>
</div>
<section id=booking>
<h2 class=section-title>Book a Service</h2>
<form>
<input placeholder="Full Name" required>
<input type=email placeholder=Email required>
<select required>
<option value="">Select Service</option>
<option>Printing</option>
<option>Photocopy</option>
<option>Browsing</option>
<option>Online Exam</option>
</select>
<input type=datetime-local required>
<button type=submit>Book Now</button>
</form>
</section>
<footer>
<footer>
<div class=social-icons>
<a href="https://www.facebook.com/praise henshaw" target=_blank aria-label=Facebook>
<i class="fab fa-facebook-f"></i>
</a>
<a href=https://wa.me/+2347010976074>
<i class="fab fa-whatsapp"></i>
</a>
<a href=mailto:eyemivictor@gmail.com aria-label=Email>
<i class="fas fa-envelope"></i>
</a>
<a href="tel:+2347010976074"><i class="fas fa-phone"></i></a>

<a href=https://www.instagram.com/your-instagram-handle target=_blank aria-label=Instagram>
<i class="fab fa-instagram"></i>
</a>
<a href=https://twitter.com/ target=_blank aria-label=Twitter>
<i class="fab fa-twitter"></i>
</a>
</div>
<p>&copy; 2025 HENSHAW's PERFECTKLEEN. All Rights Reserved.</p>
</footer>

<script>
  // Hero Background Slideshow
const heroBackgrounds = document.querySelectorAll(".hero-bg");
if (heroBackgrounds.length > 0) {
  let bgIndex = 0;
  setInterval(() => {
    heroBackgrounds[bgIndex].classList.remove("active");
    bgIndex = (bgIndex + 1) % heroBackgrounds.length;
    heroBackgrounds[bgIndex].classList.add("active");
  }, 5000);
}

// Typing Effect
const typingText = document.getElementById("typingText");
if (typingText) {
  const textArray = ["Welcome to HENSHAW's PERFECTKLEEN!", "We Aid In", "CyberCafe", "Graphics Design", "Interior Decoration(Paintings and Productions)", "House Agent / Caretaker service", "House Fumigation.", "Kindly do well to sign up and Login for awesome benefits", "Thank You", "HENSHAW's PERFECTKLEEN"];
  let textIndex = 0, charIndex = 0;

  function typeEffect() {
    if (charIndex < textArray[textIndex].length) {
      typingText.textContent += textArray[textIndex].charAt(charIndex);
      charIndex++;
      setTimeout(typeEffect, 100);
    } else {
      setTimeout(() => {
        typingText.textContent = "";
        textIndex = (textIndex + 1) % textArray.length;
        charIndex = 0;
        typeEffect();
      }, 2000);
    }
  }
  typeEffect();
}


  // Show/Hide Login Password
  const toggleLoginPassword = document.getElementById("toggle-login-password");
  const loginPassword = document.getElementById("login-password");

  toggleLoginPassword.addEventListener("change", function () {
    if (this.checked) {
      loginPassword.type = "text";
    } else {
      loginPassword.type = "password";
    }
  });

  // Show/Hide Signup Password
  const toggleSignupPassword = document.getElementById("toggle-signup-password");
  const signupPassword = document.getElementById("signup-password");

  toggleSignupPassword.addEventListener("change", function () {
    if (this.checked) {
      signupPassword.type = "text";
    } else {
      signupPassword.type = "password";
    }
  });



// Google Analytics
window.dataLayer = window.dataLayer || [];
function gtag() { dataLayer.push(arguments); }
gtag('js', new Date());
gtag('config', 'UA-XXXXXXX-X');

// FAQ Toggle with Active Class
const faqItems = document.querySelectorAll(".faq-item");
if (faqItems.length > 0) {
  faqItems.forEach(item => {
    item.addEventListener("click", () => {
      item.classList.toggle("active");
    });
  });
}

// Create the button
const scrollTopBtn = document.createElement("button");
scrollTopBtn.id = "scrollTopBtn";
scrollTopBtn.innerHTML = "<i class='fas fa-arrow-up'></i>"; // Font Awesome icon
document.body.appendChild(scrollTopBtn);

// Style it (optional)
scrollTopBtn.style.position = "fixed";
scrollTopBtn.style.bottom = "20px";
scrollTopBtn.style.right = "20px";
scrollTopBtn.style.display = "none";
scrollTopBtn.style.padding = "10px 15px";
scrollTopBtn.style.borderRadius = "50%";
scrollTopBtn.style.border = "none";
scrollTopBtn.style.background = "#00cc99";
scrollTopBtn.style.color = "#fff";
scrollTopBtn.style.cursor = "pointer";
scrollTopBtn.style.zIndex = "1000";
scrollTopBtn.style.fontSize = "18px";

// Show button on scroll
window.addEventListener("scroll", () => {
  if (window.scrollY > 300) {
    scrollTopBtn.style.display = "block";
  } else {
    scrollTopBtn.style.display = "none";
  }
});

// Scroll to top smoothly when clicked
scrollTopBtn.addEventListener("click", () => {
  window.scrollTo({ top: 0, behavior: "smooth" });
});


// Theme Toggle
function toggleTheme() {
  document.body.classList.toggle('dark-theme');
  const themeToggleIcon = document.querySelector('#theme-toggle i');
  if (document.body.classList.contains('dark-theme')) {
    themeToggleIcon.classList.remove('fa-moon');
    themeToggleIcon.classList.add('fa-sun');
  } else {
    themeToggleIcon.classList.remove('fa-sun');
    themeToggleIcon.classList.add('fa-moon');
  }
  if (document.body.classList.contains('dark-theme')) {
    localStorage.setItem('theme', 'dark');
  } else {
    localStorage.setItem('theme', 'light');
  }
}

if (localStorage.getItem('theme') === 'dark') {
  document.body.classList.add('dark-theme');
  const themeToggleIcon = document.querySelector('#theme-toggle i');
  themeToggleIcon.classList.remove('fa-moon');
  themeToggleIcon.classList.add('fa-sun');
}
const hamburger = document.getElementById('hamburger');
const navLinks = document.getElementById('nav-links');

hamburger.addEventListener('click', () => {
  hamburger.classList.toggle('active');
  navLinks.classList.toggle('active');
});
// Modal Login/Signup
function openModal(formType = "login") {
  const modal = document.getElementById("loginModal");
  const loginForm = document.getElementById("loginForm");
  const signupForm = document.getElementById("signupForm");
  const toggleText = document.getElementById("toggleText");

  if (modal && loginForm && signupForm && toggleText) {
    modal.style.display = "flex";
    if (formType === "signup") {
      loginForm.style.display = "none";
      signupForm.style.display = "block";
      toggleText.innerHTML = `Already have an account? <a href="#" onclick="switchForm('login')">Login</a>`;
    } else {
      loginForm.style.display = "block";
      signupForm.style.display = "none";
      toggleText.innerHTML = `Don't have an account? <a href="#" onclick="switchForm('signup')">Sign up</a>`;
    }
 localStorage.setItem("savedEmail", email);

  }
}

function closeModal() {
  const modal = document.getElementById("loginModal");
  if (modal) {
    modal.style.display = "none";
  }
}

function switchForm(type) {
  openModal(type);
}

  // Loader fade-out after page fully loads
  window.addEventListener("load", function() {
    setTimeout(() => {
      document.getElementById("loader").classList.add("fade-out");
      setTimeout(() => {
        document.getElementById("loader").style.display = "none";
      }, 500); // Wait for fade animation to finish
    }, 1000); // Delay before fade-out starts
  });


// Testimonials Slider
const testimonials = document.querySelectorAll(".testimonial");
const dots = document.querySelectorAll(".control-dot");
if (testimonials.length > 0 && dots.length > 0) {
  let testimonialIndex = 0;

  function showTestimonial(index) {
    testimonials.forEach((t, i) => {
      t.classList.toggle("active", i === index);
      dots[i].classList.toggle("active", i === index);
    });
  }

  dots.forEach((dot, i) => {
    dot.addEventListener("click", () => {
      testimonialIndex = i;
      showTestimonial(i);
    });
  });

  setInterval(() => {
    testimonialIndex = (testimonialIndex + 1) % testimonials.length;
    showTestimonial(testimonialIndex);
  }, 5000);
}

// Handle Contact Form Submission
const contactForm = document.getElementById("contactForm");
if (contactForm) {
  contactForm.addEventListener("submit", function (e) {
    e.preventDefault();
    const name = document.getElementById("name").value.trim();
    const email = document.getElementById("email").value.trim();
    const message = document.getElementById("message").value.trim();

    if (name && email && message) {
      const subject = encodeURIComponent("Message from VICK-BIZ Contact Form");
      const body = encodeURIComponent(`Name: ${name}\nEmail: ${email}\n\nMessage:\n${message}`);

      window.location.href = `mailto:eyemivictor@gmail.com?subject=${subject}&body=${body}`;
    } else {
      alert("Please fill in all fields.");
    }
  });
}

// Handle Login Form Submission
const loginForm = document.getElementById("loginForm");
if (loginForm) {
  loginForm.addEventListener("submit", function (e) {
    e.preventDefault();
    const username = loginForm.querySelector("input[type='text']").value.trim();
    const password = loginForm.querySelector("input[type='password']").value.trim();
    console.log("Login attempted:", username, password);
    alert("Login submitted! ");
  });
}

// Handle Signup Form Submission
const signupForm = document.getElementById("signupForm");
if (signupForm) {
  signupForm.addEventListener("submit", function (e) {
    e.preventDefault();
    const fullName = signupForm.querySelector("input[name='fullname']").value.trim();
    const email = signupForm.querySelector("input[type='email']").value.trim();
    const password = signupForm.querySelector("input[type='password']").value.trim();
    console.log("Signup attempted:", fullName, email, password);
    alert("Signup submitted! ");
  });
} 

// Add event listener to all forms
document.querySelectorAll('form').forEach(form => {
  form.addEventListener('submit', function(event) {
    // Show loader
    document.getElementById('loader').style.display = 'flex';

    // Submit form using AJAX or default form submission
    // If using AJAX
    event.preventDefault();
    // Your AJAX code here...

    // If using default form submission
    // After a short delay, hide loader and reset form
    setTimeout(() => {
      document.getElementById('loader').style.display = 'none';
      form.reset(); // Reset form inputs
    }, 2000); // Adjust the delay as needed
  });
});
 </script>

</body>
</html>
