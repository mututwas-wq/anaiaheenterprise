<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ANAIAH Enterprise</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #f4f6f9;
}

/* NAV */
nav {
  background: #0B2C4D;
  color: white;
  padding: 15px 30px;
  display: flex;
  justify-content: space-between;
}

/* HERO */
.hero {
  background: #0B2C4D;
  color: white;
  text-align: center;
  padding: 80px 20px;
}

.btn {
  padding: 12px 20px;
  margin: 5px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.btn-primary { background:#2ecc71; color:white; }
.btn-secondary { background:white; color:#0B2C4D; }

/* SECTIONS */
section { padding: 60px 20px; text-align:center; }

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px,1fr));
  gap: 20px;
  max-width: 1100px;
  margin: auto;
}

.card {
  background: white;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

/* FORM */
form {
  max-width: 500px;
  margin: auto;
}

input, textarea {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
}

/* CTA */
.cta { background:#2ecc71; color:white; }

/* FOOTER */
footer {
  background:#0B2C4D;
  color:white;
  padding:20px;
}

/* WHATSAPP */
.whatsapp {
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25D366;
  color:white;
  padding:15px;
  border-radius:50%;
  text-decoration:none;
}
</style>
</head>

<body>

<nav>
  <h3>ANAIAH Enterprise</h3>
  <div>ZPPA Registered</div>
</nav>

<div class="hero">
  <img src="logo.png" width="100"><br><br>
  <h1>Building & Supplying Your Vision</h1>
  <p>
    Construction • General Supply • Design<br>
    <strong>ZPPA Registered General Supplier</strong>
  </p>
  <button class="btn btn-primary">Request Quote</button>
</div>

<!-- SERVICES -->
<section>
  <h2>Our Services</h2>
  <div class="grid">
    <div class="card">🏗️ Construction</div>
    <div class="card">🛠️ Renovations</div>
    <div class="card">📐 Design</div>
    <div class="card">🚚 General Supply</div>
  </div>
</section>

<!-- SUPPLIES -->
<section style="background:#fff;">
  <h2>Supply Categories</h2>
  <div class="grid">
    <div class="card">🧱 Building Materials</div>
    <div class="card">🪑 Office Supplies</div>
    <div class="card">🔌 Electrical Materials</div>
    <div class="card">🚰 Plumbing Materials</div>
  </div>
</section>

<!-- TRUST -->
<section>
  <h2>Why Choose Us</h2>
  <div class="grid">
    <div class="card">✔ ZPPA Registered</div>
    <div class="card">✔ Reliable Service</div>
    <div class="card">✔ Quality Products</div>
    <div class="card">✔ On-Time Delivery</div>
  </div>
</section>

<!-- PROJECTS -->
<section>
  <h2>Our Projects</h2>
  <div class="grid">
    <div class="card">Project 1</div>
    <div class="card">Project 2</div>
    <div class="card">Project 3</div>
  </div>
</section>

<!-- QUOTE FORM -->
<section style="background:#fff;">
  <h2>Request a Quote</h2>
  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="tel" placeholder="Phone Number" required>
    <textarea placeholder="Describe your project or supply needs"></textarea>
    <button class="btn btn-primary">Submit</button>
  </form>
</section>

<!-- CTA -->
<section class="cta">
  <h2>Need Supplies or Construction Work?</h2>
  <p>Contact us today via call or WhatsApp</p>
</section>

<footer>
  <p>📍 Lusaka / Mongu</p>
  <p>📞 0971627899</p>
  <p>© ANAIAH Enterprise</p>
</footer>

<a href="https://wa.me/260971627899" class="whatsapp">💬</a>

</body>
</html>
