<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>VMD Pharmacy Billing Software</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --primary:#0b6e4f;
  --secondary:#1bb98a;
  --dark:#064d38;
  --light:#f6f9fb;
}
*{box-sizing:border-box}
body{margin:0;font-family:'Poppins',sans-serif;background:var(--light);color:#333}
a{text-decoration:none}

/* HEADER */
header{
  background:linear-gradient(135deg,var(--primary),var(--secondary));
  color:#fff;
  padding:60px 20px;
  text-align:center;
}
header h1{margin:0;font-size:40px}
header p{font-size:18px;opacity:.95}

/* RGB animation */
@keyframes rgbColor{
  0%{color:#ff5252}
  33%{color:#40c4ff}
  66%{color:#69f0ae}
  100%{color:#ff5252}
}
.rgb-text{animation:rgbColor 3s infinite}

/* NAVBAR */
nav{background:var(--dark);position:sticky;top:0;z-index:10}
.navbar{max-width:1200px;margin:auto;display:flex;align-items:center;padding:12px 20px}
.navbar a{color:#fff;font-weight:500;margin-right:18px}
.navbar a:hover{color:#ffeb3b}
.right-contact{margin-left:auto;display:flex;align-items:center;gap:18px}
.whatsapp{color:#25D366;font-weight:600}

/* CONTENT */
.container{max-width:1200px;margin:auto;padding:50px 20px}
.section-title{font-size:30px;color:var(--primary);margin-bottom:30px;text-align:center}

.features{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:22px}
.card{
  background:#fff;
  padding:25px;
  border-radius:14px;
  box-shadow:0 10px 25px rgba(0,0,0,.08);
  transition:.3s;
}
.card:hover{transform:translateY(-8px)}
.card h3{color:var(--secondary);margin-top:0}

.btn{
  display:inline-block;
  background:#e53935;
  color:#fff;
  padding:14px 30px;
  border-radius:30px;
  font-weight:600;
  transition:.3s;
}
.btn:hover{background:#c62828}

/* FLOATING WHATSAPP */
.float-whatsapp{
  position:fixed;
  right:20px;
  bottom:20px;
  background:#25D366;
  color:#fff;
  width:56px;
  height:56px;
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:28px;
  box-shadow:0 8px 20px rgba(0,0,0,.25);
}

/* FOOTER */
footer{background:var(--dark);color:#fff;text-align:center;padding:25px;margin-top:40px}

@media(max-width:768px){
  header h1{font-size:30px}
  .right-contact{flex-wrap:wrap;justify-content:center}
}
</style>
</head>
<body>

<header>
  <h1 class="rgb-text">Vmd Pharmacy Billing Software</h1>
  <p>Fast • Secure • GST‑Ready Billing & Inventory Solution for Medical Stores</p>
</header>

<nav>
  <div class="navbar">
    <div class="right-contact">

      <a href="#" onclick="alert('Contact Number: +91-9412-56-1200')">
        Contact Us
      </a>

      <a href="tel:+919412561200">
        📞 +91 9412561200
      </a>

      <a href="https://wa.me/919412561200?text=Hello%20I%20need%20support"
         class="whatsapp" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg"
             width="20" style="vertical-align:middle;">
        WhatsApp
      </a>

    </div>
  </div>
</nav>


<section id="features" class="container">
  <h2 class="section-title">Powerful Features</h2>
  <div class="features">
    <div class="card"><h3>⚡ Fast Billing</h3><p>Generate invoices in seconds with shortcut support.</p></div>
    <div class="card"><h3>🧾 GST Ready</h3><p>Automatic GST, HSN codes, and GSTR reports.</p></div>
    <div class="card"><h3>📦 Stock Control</h3><p>Batch‑wise stock, expiry alerts, and low‑stock warnings.</p></div>
    <div class="card"><h3>🛒 Purchase Module</h3><p>Supplier bills, returns, and outstanding tracking.</p></div>
    <div class="card"><h3>👥 Customer Ledger</h3><p>Credit history, payments, and balance reports.</p></div>
    <div class="card"><h3>📊 Reports</h3><p>Sales, profit, tax, and monthly analysis reports.</p></div>
    <div class="card"><h3>💾 Backup</h3><p>Save Backup As (Choose Your Drive)</p></div>
  </div>

  <div id="download" style="text-align:center;margin-top:35px">
    <a href="https://drive.google.com/uc?export=download&id=1NaMYOnSuCPI3HLGxhBHzctPTVF9Tvle0" class="btn" target="_blank">⬇ Download Free Demo</a>
  </div>
</section>

<a href="https://wa.me/919412561200" target="_blank" class="float-whatsapp">💬</a>

<footer>
  © 2026 Vmd Pharmacy Billing Software • All Rights Reserved
</footer>

</body>
</html>
