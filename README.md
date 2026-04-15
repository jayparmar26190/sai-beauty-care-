
<!DOCTYPE html>
<html lang="en">
<head>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/js/all.min.js"></script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sai Beauty Care</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #f0f7f6; /* duck egg */
      color: #2f3e3e;
    }

    header {
      background: linear-gradient(270deg, #ff7f6a, #2ec4b6, #f0f7f6);
      background-size: 600% 600%;
      animation: gradientMove 8s ease infinite;
      padding: 20px;
      text-align: center;
      color: white;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 10px;
    }

    nav a {
      text-decoration: none;
      color: white;
      font-weight: 500;
    }

    .hero {
      text-align: center;
      padding: 60px 20px;
    }

    .hero h2 {
      font-size: 2rem;
      background: linear-gradient(270deg, #ff7f6a, #2ec4b6);
      background-size: 400% 400%;
      animation: gradientMove 6s ease infinite;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }

    .card {
      background: white;
      border-radius: 15px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      text-align: center;
      opacity: 0;
      transform: translateY(40px);
      transition: all 0.6s ease;
    }

    .card.show {
      opacity: 1;
      transform: translateY(0);
    }

    .card h3 {
      color: #2ec4b6; /* emerald sea */
    }

    .badge {
      display:inline-block; 
      margin-top:10px; 
      padding:5px 12px; 
      background:#ff7f6a; 
      color:white; 
      border-radius:20px; 
      font-size:0.8rem;
    }

    .booking {
      background: #e6f4f1; /* soft emerald/duck mix */
      padding: 40px;
      text-align: center;
    }

    input, textarea, select {
      width: 80%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 10px;
      border: 1px solid #ccc;
    }

    button {
      background: linear-gradient(270deg, #2ec4b6, #ff7f6a);
      background-size: 400% 400%;
      animation: gradientMove 6s ease infinite;
      color: white;
      border: none;
      padding: 12px 25px;
      border-radius: 25px;
      cursor: pointer;
      font-size: 1rem;
    }

    button:hover {
      background: #25a89c;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: linear-gradient(270deg, #2ec4b6, #ff7f6a);
      background-size: 400% 400%;
      animation: gradientMove 8s ease infinite;
      color: white;
    }
  
    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Sai Beauty Care</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#services">Services</a>
      <a href="#booking">Book Now</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Enhance Your Natural Beauty ✨</h2>
    <p>Exclusive beauty services for women. Feel confident, feel beautiful.</p>
  </section>

  <section class="services" id="services">
    <div class="card">
      <i class="fa-solid fa-spa" style="font-size:30px; color:#ff7f6a;"></i>
      <h3>Facials</h3>
      <p>Basic Facial - ₹550</p>
      <p>O3+ Premium Facial - ₹1250 to ₹1500</p>
      <p>Hydra Facial - ₹1000</p>
      <p>Korean Glass Facial - ₹1000</p>
      <button onclick="window.location.href='#booking'">Book Service</button>
    </div>
    
    

    <div class="card">
      <i class="fa-solid fa-hand-sparkles" style="font-size:30px; color:#ff7f6a;"></i>
      <h3>Waxing & Cleanup</h3>
      <p>Smooth and clean skin with professional care.</p>
    </div>

    <div class="card">
      <i class="fa-solid fa-leaf" style="font-size:30px; color:#ff7f6a;"></i>
      <h3>Shining</h3>
      <p>Professional shining services for glowing skin.</p>
    </div>

    <div class="card">
      <i class="fa-solid fa-hand" style="font-size:30px; color:#ff7f6a;"></i>
      <h3>Mehndi</h3>
      <p>Beautiful mehndi designs for all occasions.</p>
      <p>We make you avail best mehndi artist.</p>
    </div>
  </section>

  <section class="services" id="pricing">
    <h2 style="text-align:center; color:#ff7f6a;">Price List</h2>
    <div class="card">
      <h3>Facials</h3>
      <p>Basic Facial - ₹550</p>
      <p>O3+ Premium Facial - ₹1250 to ₹1500</p>
      <p>Hydra Facial - ₹1000</p>
      <p>Korean Glass Facial - ₹1000</p>
      <button onclick="window.location.href='#booking'">Book Service</button>
    </div>

    <div class="card">
      <h3>Hair</h3>
      <p>Basic Haircut (Basic cuts only) - ₹100 to ₹300 (can vary)</p>
            <button onclick="window.location.href='#booking'">Book Service</button>
    </div>

    <div class="card">
      <h3>Waxing (Normal)</h3>
      <p>Half Wax (Normal) - ₹400</p>
      <p>Full Wax (Normal) - ₹550</p>
      <button onclick="window.location.href='#booking'">Book Service</button>
    </div>

    <div class="card">
      <h3>Rica Wax</h3>
      <p>Half Wax (Rica) - ₹600</p>
      <p>Full Wax (Rica) - ₹850</p>
      <button onclick="window.location.href='#booking'">Book Service</button>
    </div>

    <div class="card">
      <h3>Shining</h3>
      <p>Face Shining - ₹300</p>
      <p>Full Body Shining - ₹1200</p>
            <button onclick="window.location.href='#booking'">Book Service</button>
    </div>

    <div class="card">
      <h3>Mehndi</h3>
      <p><i>Prices may vary depending on design.</i></p>
      <button onclick="window.location.href='#booking'">Book Service</button>
    </div>
  </section>

  <section class="services" id="cities">
    <h2 style="text-align:center; color:#2ec4b6;">Service Cities</h2>
    <div class="card"><h3>Navsari</h3><p>Available for home & studio services</p><span class="badge">Home Service Available</span></div>
    <div class="card"><h3>Surat</h3><p>Available for all services</p><span class="badge">Home Service Available</span></div>
    <div class="card"><h3>Palsana</h3><p>Available on prior booking</p><span class="badge">Home Service Available</span></div>
    <div class="card"><h3>Chikhli</h3><p>Special appointments only</p><span class="badge">Home Service Available</span></div>
    <div class="card"><h3>Sisodra</h3><p>Nearby service coverage</p><span class="badge">Home Service Available</span></div>
    <div class="card"><h3>Sachin</h3><p>Weekend availability</p><span class="badge">Home Service Available</span></div>
  </section>

  <section class="booking" id="booking">
    <h2>Book an Appointment</h2>
    <input type="text" placeholder="Your Name"><br>
    <input type="email" placeholder="Your Email"><br>
    <select>
      <option value="">Select Your City</option>
      <option>Navsari</option>
      <option>Surat</option>
      <option>Palsana</option>
      <option>Chikhli</option>
      <option>Sisodra</option>
      <option>Sachin</option>
    </select><br>
    <textarea placeholder="Your Service & Time"></textarea><br>
    <button>Book Now</button>
  </section>

  <footer id="contact">
    <p>Contact: <a href="https://wa.me/919374871444" target="_blank" style="color:white;">WhatsApp: 9374871444</a> | <a href="tel:+919374871444" style="color:white;">Call: 9374871444</a> | <a href="mailto:nilaparmar2810@gmail.com" style="color:white;">nilaparmar2810@gmail.com</a></p>
    <p>© 2026 Sai Beauty Care. All rights reserved.</p>
  </footer>

  <script>
    const cards = document.querySelectorAll('.card');

    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
        }
      });
    }, {
      threshold: 0.2
    });

    cards.forEach(card => {
      observer.observe(card);
    });
  </script>
</body>
</html>

