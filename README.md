<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sukhay Khan Traders - Kot Radha Kishan, District Kasur</title>
<meta name="description" content="Sukhay Khan Traders - Electronics & Spray Center Solutions in Kot Radha Kishan, District Kasur. Call 03464570882">
<style>
  :root{
    --blue: #1a365d;
    --gold: #d4af37;
    --white: #ffffff;
  }
  *{margin:0;padding:0;box-sizing:border-box;font-family: 'Segoe UI', Arial, sans-serif}
  body{background:#f8f9fa;color:#333;line-height:1.6}
  
  header{background:var(--blue);color:var(--white);padding:20px;text-align:center;position:sticky;top:0;z-index:100}
  header h1{color:var(--gold);font-size:2rem}
  header p{font-size:0.9rem;opacity:0.9}
  .btn{background:var(--gold);color:var(--blue);padding:12px 25px;border-radius:30px;text-decoration:none;font-weight:bold;margin:8px;display:inline-block;border:none;cursor:pointer;transition:0.3s}
  .btn:hover{transform:translateY(-2px);box-shadow:0 4px 12px rgba(212,175,55,0.4)}
  .btn-outline{background:transparent;border:2px solid var(--gold);color:var(--gold)}
  
  section{padding:60px 20px;max-width:1100px;margin:auto}
  h2{text-align:center;color:var(--blue);margin-bottom:30px;font-size:2rem}
  
  .hero{background:linear-gradient(rgba(26,54,93,0.85), rgba(26,54,93,0.85)), url('https://images.unsplash.com/photo-1558618666-fcd25c85cd64?q=80&w=1200') center/cover;color:var(--white);text-align:center;padding:100px 20px}
  .hero h1{font-size:2.5rem;color:var(--gold);margin-bottom:10px}
  
  .hours{background:var(--white);border-radius:10px;padding:30px;box-shadow:0 2px 15px rgba(0,0,0,0.1);text-align:center}
  
  .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:25px}
  .card{background:var(--white);padding:25px;border-radius:12px;box-shadow:0 4px 15px rgba(0,0,0,0.1);transition:0.3s}
  .card:hover{transform:translateY(-5px)}
  .card h3{color:var(--blue);margin-bottom:10px}
  .card .location{color:var(--gold);font-size:0.9rem;margin-bottom:15px}
  
  .services{display:flex;flex-wrap:wrap;gap:15px;justify-content:center}
  .service-tag{background:var(--blue);color:var(--white);padding:10px 20px;border-radius:25px}
  
  .contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:30px}
  .contact-form input, .contact-form textarea{width:100%;padding:12px;margin-bottom:15px;border:1px solid #ddd;border-radius:8px}
  
  footer{background:var(--blue);color:var(--white);text-align:center;padding:25px;margin-top:40px}
  
  .whatsapp{position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;padding:15px 20px;border-radius:50px;text-decoration:none;font-weight:bold;z-index:999;box-shadow:0 4px 15px rgba(37,211,102,0.4)}
  
  /* Gallery Modal */
  .modal{display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.8);z-index:1000;justify-content:center;align-items:center}
  .modal-content{background:var(--white);padding:20px;border-radius:10px;max-width:600px;width:90%;max-height:80vh;overflow-y:auto}
  .modal-close{float:right;font-size:28px;cursor:pointer;color:var(--blue)}
  .gallery-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-top:15px}
  .gallery-item{background:#eee;height:120px;border-radius:8px;display:flex;align-items:center;justify-content:center;color:#777;font-size:0.9rem}
  
  @media(max-width:768px){
    .contact-grid{grid-template-columns:1fr}
    .hero h1{font-size:1.8rem}
  }
</style>
</head>
<body>

<header>
  <h1>Sukhay Khan Traders</h1>
  <p>Kot Radha Kishan, District Kasur, Punjab, Pakistan</p>
  <a href="tel:03464570882" class="btn">Call Now: 03464570882</a>
  <a href="https://wa.me/923464570882" class="btn btn-outline" target="_blank">WhatsApp Us</a>
</header>

<section class="hero">
  <h1>Sukhay Khan Traders - Kot Radha Kishan, District Kasur</h1>
  <p>Electronics & Spray Center Solutions</p>
</section>

<section>
  <h2>About Us</h2>
  <p style="text-align:center;max-width:800px;margin:auto">20+ Years of Trusted Service in Electronics and Spray Equipment in District Kasur. We provide quality products, reliable service, and complete customer satisfaction.</p>
  <p style="text-align:center;margin-top:15px;font-size:1.1rem">20+ سال کی قابلِ اعتماد سروس - الیکٹرانکس اور اسپرے کا سامان</p>
</section>

<section>
  <h2>Opening Hours</h2>
  <div class="hours">
    <p><b>Mon - Sat:</b> 9:00 AM - 8:00 PM</p>
    <p><b>Sunday:</b> 10:00 AM - 2:00 PM</p>
    <p style="margin-top:10px;color:var(--gold)">Call us anytime for emergency service</p>
  </div>
</section>

<section>
  <h2>Our Branches</h2>
  <div class="cards">
    <div class="card">
      <h3>Hammad Electronics</h3>
      <p class="location">📍 Kot Radha Kishan, District Kasur</p>
      <p>Electronics, TVs, Fans, Wires, Switches, Home Appliances</p>
      <button class="btn" onclick="openGallery('Hammad Electronics', ['TVs & LED', 'Ceiling & Wall Fans', 'Wires & Cables', 'Switches & Sockets', 'Home Appliances'])">View Products</button>
    </div>
    <div class="card">
      <h3>Tahir Spray Centre</h3>
      <p class="location">📍 Kot Radha Kishan, District Kasur</p>
      <p>Spray Machines, Agricultural Pumps, Spray Guns, Tanks</p>
      <button class="btn" onclick="openGallery('Tahir Spray Centre', ['Battery Sprayers', 'Agricultural Pumps', 'Spray Guns', 'Chemical Tanks'])">View Products</button>
    </div>
    <div class="card">
      <h3>Sajid Spray Centre</h3>
      <p class="location">📍 Kot Radha Kishan, District Kasur</p>
      <p>Spray Equipment, Tools, Spare Parts & Service</p>
      <button class="btn" onclick="openGallery('Sajid Spray Centre', ['Spray Equipment', 'Tools & Accessories', 'Spare Parts', 'Repair Service'])">View Products</button>
    </div>
  </div>
</section>

<section>
  <h2>Our Services</h2>
  <div class="services">
    <div class="service-tag">Electronics Sales & Repair</div>
    <div class="service-tag">Spray Machines</div>
    <div class="service-tag">Agricultural Solutions</div>
    <div class="service-tag">Spare Parts</div>
  </div>
</section>

<section>
  <h2>Contact Us</h2>
  <div class="contact-grid">
    <div>
      <p><b>Address:</b> Kot Radha Kishan, District Kasur, Punjab, Pakistan</p>
      <p><b>Phone:</b> 03464570882</p>
      <p><b>WhatsApp:</b> 03464570882</p>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d27248.123!2d74.123!3d31.123!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzHCsDA3JzI0LjAiTiA3NMKwMDcnMjQuMCJF!5e0!3m2!1sen!2s" width="100%" height="250" style="border:0;border-radius:10px;margin-top:15px" allowfullscreen loading="lazy"></iframe>
    </div>
    <form class="contact-form" onsubmit="alert('Message sent! We will call you soon.'); return false;">
      <input type="text" placeholder="Your Name" required>
      <input type="tel" placeholder="Your Phone" required>
      <textarea rows="4" placeholder="Your Message" required></textarea>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </div>
</section>

<footer>
  <p>Sukhay Khan Traders | Kot Radha Kishan, District Kasur | Phone: 03464570882 | © 2026</p>
</footer>

<a href="https://wa.me/923464570882" class="whatsapp" target="_blank">WhatsApp</a>

<!-- Gallery Modal -->
<div id="galleryModal" class="modal">
  <div class="modal-content">
    <span class="modal-close" onclick="closeGallery()">&times;</span>
    <h3 id="galleryTitle" style="color:var(--blue)"></h3>
    <div id="galleryGrid" class="gallery-grid"></div>
  </div>
</div>

<script>
  function openGallery(title, items){
    document.getElementById('galleryTitle').innerText = title + ' - Products';
    let grid = document.getElementById('galleryGrid');
    grid.innerHTML = '';
    items.forEach(item => {
      grid.innerHTML += `<div class="gallery-item">${item}</div>`;
    });
    document.getElementById('galleryModal').style.display = 'flex';
  }
  function closeGallery(){
    document.getElementById('galleryModal').style.display = 'none';
  }
  window.onclick = function(event){
    if(event.target == document.getElementById('galleryModal')){
      closeGallery();
    }
  }
</script>

</body>
</html>