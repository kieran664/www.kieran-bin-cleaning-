<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fresh Bins | Wheelie Bin Cleaning</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box}
body{font-family:'Inter',sans-serif;margin:0;background:#f5f7f8;color:#1a1a1a}
header{background:linear-gradient(135deg,#1f8f5f,#2fbf71);color:white;padding:40px 20px;text-align:center}
header h1{margin:0;font-size:36px}
header p{margin-top:10px;font-size:18px}
nav{background:#0f6b44;padding:14px;text-align:center}
nav a{color:white;text-decoration:none;margin:0 18px;font-weight:600}
.hero{padding:80px 20px;text-align:center;background:#e9f7f1}
.hero h2{font-size:38px;margin-bottom:10px}
.hero p{font-size:18px;margin-bottom:25px}
.btn{background:#1f8f5f;color:white;border:none;padding:14px 26px;border-radius:8px;font-size:16px;cursor:pointer;font-weight:600}
.btn:hover{background:#176e49}
.container{max-width:1100px;margin:auto;padding:60px 20px}
.section-title{text-align:center;font-size:30px;margin-bottom:40px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:25px}
.card{background:white;border-radius:16px;padding:25px;box-shadow:0 8px 20px rgba(0,0,0,0.06);transition:transform .2s}
.card:hover{transform:translateY(-5px)}
.price{font-size:24px;color:#1f8f5f;font-weight:700}
form{display:grid;gap:15px;max-width:600px;margin:auto}
input,textarea,select{padding:14px;border-radius:8px;border:1px solid #ccc;font-size:16px}
textarea{min-height:120px}
.contact-box{background:white;border-radius:16px;padding:30px;text-align:center;box-shadow:0 8px 20px rgba(0,0,0,0.06);max-width:600px;margin:auto}
.contact-box p{margin:10px 0;font-size:18px}
footer{background:#111;color:#ddd;text-align:center;padding:30px;margin-top:60px}
.badges{display:flex;flex-wrap:wrap;justify-content:center;gap:20px;margin-top:30px}
.badge{background:white;padding:12px 18px;border-radius:8px;font-weight:600;box-shadow:0 4px 10px rgba(0,0,0,0.05)}
</style>
</head>
<body>

<header>
<h1>Fresh Bins</h1>
<p>Professional Wheelie Bin Cleaning in Sleaford & Holdingham</p>
</header>

<nav>
<a href="#services">Services</a>
<a href="#prices">Prices</a>
<a href="#how">How It Works</a>
<a href="#book">Book</a>
<a href="#contact">Contact</a>
</nav>

<section class="hero">
<h2>Keep Your Bins Clean, Fresh & Germ-Free</h2>
<p>Eco‑friendly wheelie bin cleaning for homes and businesses.</p>
<button class="btn" onclick="document.getElementById('book').scrollIntoView({behavior:'smooth'})">Book a Clean</button>

<div class="badges">
<div class="badge">Eco Friendly</div>
<div class="badge">Kills Bacteria</div>
<div class="badge">Removes Odours</div>
<div class="badge">Local Service</div>
</div>
</section>

<section id="services" class="container">
<h2 class="section-title">Our Services</h2>
<div class="grid">
<div class="card">
<h3>Domestic Bin Cleaning</h3>
<p>Professional pressure washing and disinfecting of household bins.</p>
</div>
<div class="card">
<h3>Commercial Bins</h3>
<p>Cleaning services for restaurants, shops and businesses.</p>
</div>
<div class="card">
<h3>Sanitised & Deodorised</h3>
<p>Bins cleaned inside and outside then deodorised.</p>
</div>
<div class="card">
<h3>Regular Cleans</h3>
<p>Fortnightly, monthly or one‑off cleans available.</p>
</div>
</div>
</section>

<section id="prices" class="container">
<h2 class="section-title">Prices</h2>
<div class="grid">
<div class="card">
<h3>1 Bin</h3>
<p class="price">£5</p>
<p>Per clean</p>
</div>
<div class="card">
<h3>2 Bins</h3>
<p class="price">£8</p>
<p>Per clean</p>
</div>
<div class="card">
<h3>3 Bins</h3>
<p class="price">£10</p>
<p>Per clean</p>
</div>
</div>
</section>

<section id="how" class="container">
<h2 class="section-title">How It Works</h2>
<div class="grid">
<div class="card">
<h3>1. Collection Day</h3>
<p>We arrive after your bins have been emptied.</p>
</div>
<div class="card">
<h3>2. Deep Clean</h3>
<p>Your bin is pressure washed, disinfected and deodorised.</p>
</div>
<div class="card">
<h3>3. Fresh & Hygienic</h3>
<p>You come home to a clean, fresh bin.</p>
</div>
</div>
</section>

<section id="book" class="container">
<h2 class="section-title">Book a Bin Clean</h2>
<p style="text-align:center;margin-bottom:30px">Send a booking request and we will contact you to confirm.</p>

<form action="https://formspree.io/f/mayvlqrr" method="POST">
<input type="text" name="name" placeholder="Your Name" required>
<input type="email" name="email" placeholder="Your Email" required>
<input type="tel" name="phone" placeholder="Phone Number" required>
<input type="text" name="address" placeholder="Address" required>
<select name="bins" required>
<option value="">Number of Bins</option>
<option>1 Bin</option>
<option>2 Bins</option>
<option>3 Bins</option>
</select>
<textarea name="message" placeholder="Ask a question or request a date"></textarea>
<button class="btn" type="submit">Send Booking Request</button>
</form>

</section>

<section id="contact" class="container">
<h2 class="section-title">Contact</h2>
<div class="contact-box">
<p><strong>Phone:</strong> 07534 210021</p>
<p><strong>Email:</strong> kieranshield@outlook.com</p>
<p><strong>Serving:</strong> Sleaford & Holdingham</p>
<p>You can also book using the form above.</p>
</div>
</section>

<footer>
<p>© 2026 Fresh Bins – Wheelie Bin Cleaning</p>
</footer>

</body>
</html>
