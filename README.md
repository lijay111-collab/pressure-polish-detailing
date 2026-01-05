<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pressure & Polish | Houston TX</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #020617;
  color: #fff;
}
header {
  background: linear-gradient(to right, #1e40af, #020617);
  padding: 50px 20px;
  text-align: center;
}
header h1 { font-size: 2.5rem; }
header p { font-size: 1.1rem; }

.btn {
  display: inline-block;
  margin: 10px;
  padding: 15px 25px;
  background: #22c55e;
  color: #000;
  text-decoration: none;
  font-weight: bold;
  border-radius: 8px;
}

section {
  padding: 50px 20px;
  max-width: 1100px;
  margin: auto;
}

h2 {
  color: #38bdf8;
  margin-bottom: 25px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: #0f172a;
  padding: 20px;
  border-radius: 10px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
}

form input, form textarea {
  width: 100%;
  padding: 15px;
  margin-bottom: 15px;
  border-radius: 8px;
  border: none;
}

form button {
  width: 100%;
  padding: 15px;
  background: #22c55e;
  border: none;
  font-weight: bold;
  font-size: 1.1rem;
  border-radius: 8px;
}

footer {
  background: #020617;
  text-align: center;
  padding: 30px;
}
.sticky {
  position: fixed;
  bottom: 15px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  gap: 10px;
}
</style>
</head>

<body>

<header>
  <h1>Pressure & Polish</h1>
  <p>Power Washing & Mobile Car Detailing • Houston, TX</p>
  <a class="btn" href="tel:18323670110">📞 Call</a>
  <a class="btn" href="sms:18323670110">💬 Text</a>
</header>

<section>
<h2>Power Washing Services</h2>
<div class="grid">
  <div class="card">Driveway Cleaning — <b>$40+</b></div>
  <div class="card">House Wash (1-Story) — <b>$95+</b></div>
  <div class="card">House Wash (2-Story) — <b>$125+</b></div>
  <div class="card">Sidewalks / Patios — <b>$30+</b></div>
  <div class="card">Fences — <b>$50+</b></div>
</div>
</section>

<section>
<h2>🔥 Bundles</h2>
<div class="grid">
  <div class="card">Driveway + Sidewalk</div>
  <div class="card">House + Driveway — <b>$110</b></div>
</div>
</section>

<section>
<h2>Mobile Car Detailing</h2>
<div class="grid">
  <div class="card">Exterior Wash — <b>$40</b></div>
  <div class="card">Interior Detail — <b>$60</b></div>
  <div class="card">Full Detail — <b>$120</b></div>
</div>
</section>

<section>
<h2>Add-Ons</h2>
<div class="grid">
  <div class="card">Pet Hair Removal</div>
  <div class="card">Seat Shampoo</div>
  <div class="card">Headlight Restoration</div>
</div>
</section>

<section>
<h2>Before & After</h2>
<div class="grid gallery">
  <img src="before1.jpg">
  <img src="after1.jpg">
  <img src="before2.jpg">
  <img src="after2.jpg">
</div>
<p style="opacity:.7">*Replace images with your real jobs*</p>
</section>

<section>
<h2>Book Service / Get a Quote</h2>
<form action="https://formsubmit.co/YOUR-EMAIL-HERE" method="POST">
  <input type="text" name="name" placeholder="Your Name" required>
  <input type="tel" name="phone" placeholder="Phone Number" required>
  <input type="text" name="service" placeholder="Service Needed">
  <textarea name="message" placeholder="Address + details"></textarea>
  <button type="submit">Request Quote</button>
</form>
</section>

<footer>
<p>📍 Houston, TX</p>
<p>📞 (832) 367-0110</p>
<p>Same-Day & Weekend Service</p>
</footer>

<div class="sticky">
<a class="btn" href="tel:18323670110">Call</a>
<a class="btn" href="sms:18323670110">Text</a>
</div>

</body>
</html>
