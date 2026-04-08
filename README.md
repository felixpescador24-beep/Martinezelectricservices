# Martinezelectricservices
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Martinez Electric Services LLC</title>
  <meta name="description" content="Professional electric services in Harris and Montgomery County, Texas. New homes, remodels, add-ons, and general electric work.">
  <style>
    * {margin:0;padding:0;box-sizing:border-box;font-family:Arial, sans-serif;}
    body {background:#0f172a;color:#fff;line-height:1.6;scroll-behavior:smooth;}
    a {text-decoration:none;}
    
    nav {position:sticky;top:0;background:#111827;display:flex;justify-content:space-between;align-items:center;padding:15px 40px;z-index:1000;box-shadow:0 2px 10px rgba(0,0,0,0.3);}
    nav h2 {color:#facc15;font-size:1.5rem;}
    nav ul {display:flex; gap:25px; list-style:none;}
    nav ul li a {color:#e2e8f0;font-weight:bold; transition:0.3s;}
    nav ul li a:hover {color:#facc15;}

    header {background:linear-gradient(rgba(15,23,42,0.8), rgba(15,23,42,0.8)), url('https://via.placeholder.com/1600x900') center/cover no-repeat;min-height:100vh;display:flex;align-items:center;justify-content:center;text-align:center;padding:20px;}
    .hero h1 {font-size:3rem;color:#facc15;margin-bottom:15px;}
    .hero h2 {font-size:2rem;margin-bottom:25px;}
    .hero p {font-size:1.2rem;margin-bottom:35px;color:#e2e8f0;}
    .btn-group {display:flex; flex-wrap:wrap; justify-content:center; gap:20px;}
    .btn {background:#facc15;color:#0f172a;padding:15px 28px;border-radius:8px;font-weight:bold;transition:0.3s;}
    .btn:hover {background:#fde047;transform:translateY(-2px);}
    .btn-outline {background:transparent;border:2px solid #facc15;color:#facc15;}
    .btn-outline:hover {background:#facc15;color:#0f172a;}

    section {padding:90px 20px;}
    .container {max-width:1200px;margin:auto;}
    h3 {font-size:2rem;color:#facc15;margin-bottom:25px;text-align:center;}
    .section-text {text-align:center;max-width:900px;margin:0 auto 50px;color:#cbd5e1;font-size:1.1rem;}

    .services-grid, .why-grid, .areas-grid {display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:25px;margin-top:40px;}
    .card {background:#1e293b;padding:25px;border-radius:12px;box-shadow:0 8px 25px rgba(0,0,0,0.2);text-align:center;opacity:0;transform:translateY(20px);transition:0.6s ease-out;}
    .card.visible {opacity:1; transform:translateY(0);}
    .card img {width:100%;border-radius:10px;margin-bottom:15px;}
    .card h4 {color:#facc15;margin-bottom:12px;font-size:1.2rem;}
    .card p {color:#cbd5e1;font-size:1rem;}

    .contact-box {background:#1e293b;padding:40px;border-radius:15px;text-align:center;max-width:750px;margin:auto;box-shadow:0 8px 25px rgba(0,0,0,0.25);}
    .contact-box p {font-size:1.15rem;margin:12px 0;color:#e2e8f0;}
    .contact-box .btn-group {margin-top:25px;}

    footer {background:#020617;padding:30px 20px;text-align:center;color:#94a3b8;font-size:1rem;}

    @media(max-width:768px){
      .hero h1{font-size:2.2rem;}
      .hero h2{font-size:1.5rem;}
      .hero p{font-size:1rem;}
      h3{font-size:1.7rem;}
    }
  </style>
</head>
<body>

  <nav>
    <h2>Martinez Electric</h2>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#why">Why Us</a></li>
      <li><a href="#area">Service Area</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header>
    <div class="hero">
      <h1>Martinez Electric Services LLC</h1>
      <h2>Professional Electric Services You Can Trust</h2>
      <p>Serving Harris County, Montgomery County, and surrounding Texas areas. New custom homes, remodels, add-ons, and general residential electric work.</p>
      <div class="btn-group">
        <a class="btn" href="tel:8325630637">Call Now</a>
        <a class="btn btn-outline" href="mailto:Martinezelectricservicesllc@gmail.com">Email Us</a>
        <a class="btn btn-outline" href="https://www.facebook.com/share/1NzYjT6QcT/?mibextid=wwXIfr" target="_blank">Visit Facebook</a>
      </div>
    </div>
  </header>

  <section id="about">
    <div class="container">
      <h3>About Us</h3>
      <p class="section-text">At Martinez Electric Services LLC, we deliver quality workmanship, dependable service, and honest communication. Whether you're building a new custom home, remodeling, or adding on, we provide safe, efficient, and professional electric solutions you can trust.</p>
    </div>
  </section>

  <section id="services" style="background:#111827;">
    <div class="container">
      <h3>Our Services</h3>
      <p class="section-text">From new construction to remodels and additions, we handle a wide range of residential electric work.</p>
      <div class="services-grid">
        <div class="card"><img src="https://via.placeholder.com/300x200" alt="New Custom Home Wiring"><h4>New Custom Home Wiring</h4><p>Professional electric setup for new residential builds.</p></div>
        <div class="card"><img src="https://via.placeholder.com/300x200" alt="Home Remodel Electric"><h4>Home Remodel Electric</h4><p>Electric upgrades and rewiring for remodel projects.</p></div>
        <div class="card"><img src="https://via.placeholder.com/300x200" alt="Room Add-Ons"><h4>Room Add-Ons</h4><p>Electric work for home additions and expansions.</p></div>
        <div class="card"><img src="https://via.placeholder.com/300x200" alt="Lighting Installation"><h4>Lighting Installation</h4><p>Indoor and outdoor lighting installation and upgrades.</p></div>
        <div class="card"><img src="https://via.placeholder.com/300x200" alt="Outlet & Switch Installation"><h4>Outlet & Switch Installation</h4><p>Safe and efficient installation of outlets and switches.</p></div>
        <div class="card"><img src="https://via.placeholder.com/300x200" alt="Ceiling Fan Installation"><h4>Ceiling Fan Installation</h4><p>Reliable fan wiring and installation services.</p></div>
        <div class="card"><img src="https://via.placeholder.com/300x200" alt="Panel Upgrades"><h4>Panel Upgrades</h4><p>Electric panel improvements for better safety and capacity.</p></div>
        <div class="card"><img src="https://via.placeholder.com/300x200" alt="Troubleshooting & Repairs"><h4>Troubleshooting & Repairs</h4><p>Fast diagnosis and repair for electric issues.</p></div>
      </div>
    </div>
  </section>

  <section id="why">
    <div class="container">
      <h3>Why Choose Us</h3>
      <div class="why-grid">
        <div class="card"><h4>Quality Workmanship</h4><p>We focus on doing the job right the first time.</p></div>
        <div class="card"><h4>Reliable Service</h4><p>Professional, dependable, and responsive on every project.</p></div>
        <div class="card"><h4>Honest Communication</h4><p>Clear updates and straightforward service you can count on.</p></div>
        <div class="card"><h4>Safe Electric Solutions</h4><p>Electric work completed with safety and care in mind.</p></div>
      </div>
    </div>
  </section>

  <section id="area" style="background:#111827;">
    <div class="container">
      <h3>Service Area</h3>
      <p class="section-text">Proudly serving homeowners and builders across Harris County, Montgomery County, and surrounding areas.</p>
      <div class="areas-grid">
        <div class="card"><h4>Harris County</h4><p>Residential electric services across the county.</p></div>
        <div class="card"><h4>Montgomery County</h4><p>Dependable electric work for homes and projects.</p></div>
        <div class="card"><h4>Surrounding Areas</h4><p>Contact us to see if we service your location.</p></div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h3>Contact Us</h3>
      <div class="contact-box">
        <p><strong>Martinez Electric Services LLC</strong></p>
        <p>📞 <a href="tel:8325630637" style="color:#facc15;">832-563-0637</a></p>
        <p>✉️ <a href="mailto:Martinezelectricservicesllc@gmail.com" style="color:#facc15;">Martinezelectricservicesllc@gmail.com</a></p>
        <p>Need electric work done? Call, email, or message us on Facebook today.</p>
        <div class="btn-group">
          <a class="btn" href="tel:8325630637">Call Now</a>
          <a class="btn btn-outline" href="mailto:Martinezelectricservicesllc@gmail.com">Request a Quote</a>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <p>Martinez Electric Services LLC</p>
    <p>Serving Harris County & Montgomery County, Texas</p>
    <p>832-563-0637 | Martinezelectricservicesllc@gmail.com</p>
  </footer>

  <script>
    const cards = document.querySelectorAll('.card');
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if(entry.isIntersecting){
          entry.target.classList.add('visible');
        }
      });
    }, {threshold:0.2});
    cards.forEach(card => observer.observe(card));
  </script>

</body>
</html>
