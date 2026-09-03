<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>OK Fastfood | Delicious Food, Fast Service</title>

  <meta
    name="description"
    content="OK Fastfood serves delicious, fresh and affordable fast food. Call now to order."
  />

  <style>
    /* =========================================
       EASY CUSTOMIZATION
    ========================================= */

    :root {
      --primary: #e63946;
      --secondary: #ffb703;
      --dark: #171717;
      --dark-light: #242424;
      --light: #fffaf5;
      --white: #ffffff;
      --text: #333333;
      --gray: #777777;
      --radius: 18px;
      --shadow: 0 10px 30px rgba(0, 0, 0, 0.12);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: var(--light);
      color: var(--text);
      line-height: 1.6;
      overflow-x: hidden;
    }

    img {
      width: 100%;
      display: block;
      object-fit: cover;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* =========================================
       GLOBAL
    ========================================= */

    .container {
      width: min(1120px, 92%);
      margin: auto;
    }

    section {
      padding: 80px 0;
    }

    .section-title {
      text-align: center;
      margin-bottom: 15px;
      font-size: clamp(2rem, 5vw, 3rem);
      color: var(--dark);
    }

    .section-text {
      text-align: center;
      max-width: 650px;
      margin: 0 auto 45px;
      color: var(--gray);
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      padding: 14px 24px;
      border-radius: 50px;
      font-weight: bold;
      transition: 0.3s ease;
      cursor: pointer;
      border: none;
      min-height: 50px;
    }

    .btn-primary {
      background: var(--primary);
      color: var(--white);
    }

    .btn-primary:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 25px rgba(230, 57, 70, 0.35);
    }

    .btn-secondary {
      background: var(--secondary);
      color: var(--dark);
    }

    .btn-secondary:hover {
      transform: translateY(-3px);
    }

    /* =========================================
       NAVBAR
    ========================================= */

    nav {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 1000;
      background: rgba(23, 23, 23, 0.95);
      backdrop-filter: blur(10px);
    }

    .nav-container {
      min-height: 70px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      color: var(--white);
      font-size: 1.5rem;
      font-weight: 800;
    }

    .logo span {
      color: var(--secondary);
    }

    .nav-links {
      display: flex;
      gap: 25px;
      align-items: center;
    }

    .nav-links a {
      color: var(--white);
      font-size: 0.95rem;
    }

    .nav-links a:hover {
      color: var(--secondary);
    }

    /* =========================================
       HERO
    ========================================= */

    .hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      position: relative;
      background:
        linear-gradient(
          rgba(0, 0, 0, 0.65),
          rgba(0, 0, 0, 0.7)
        ),
        url("https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=1600&q=80")
        center/cover;
      color: white;
      padding-top: 70px;
    }

    .hero-content {
      max-width: 750px;
    }

    .hero-badge {
      display: inline-block;
      background: var(--secondary);
      color: var(--dark);
      padding: 8px 16px;
      border-radius: 50px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .hero h1 {
      font-size: clamp(2.5rem, 7vw, 5rem);
      line-height: 1.1;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.1rem;
      max-width: 600px;
      margin-bottom: 30px;
      color: #eeeeee;
    }

    .hero-buttons {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
    }

    /* =========================================
       ABOUT
    ========================================= */

    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 50px;
      align-items: center;
    }

    .about-image img {
      height: 450px;
      border-radius: var(--radius);
      box-shadow: var(--shadow);
    }

    .about-content h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .about-content p {
      color: var(--gray);
      margin-bottom: 15px;
    }

    /* =========================================
       MENU
    ========================================= */

    .menu {
      background: #fff;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 25px;
    }

    .menu-card {
      background: var(--white);
      border-radius: var(--radius);
      overflow: hidden;
      box-shadow: var(--shadow);
      transition: 0.3s ease;
    }

    .menu-card:hover {
      transform: translateY(-8px);
    }

    .menu-card img {
      height: 220px;
    }

    .menu-content {
      padding: 20px;
    }

    .menu-content h3 {
      margin-bottom: 8px;
      font-size: 1.3rem;
    }

    .menu-content p {
      color: var(--gray);
      margin-bottom: 15px;
      font-size: 0.9rem;
    }

    .price {
      display: block;
      color: var(--primary);
      font-size: 1.2rem;
      font-weight: bold;
      margin-bottom: 15px;
    }

    /* =========================================
       FEATURES
    ========================================= */

    .features-grid {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 20px;
    }

    .feature-card {
      background: white;
      padding: 25px 15px;
      text-align: center;
      border-radius: var(--radius);
      box-shadow: var(--shadow);
    }

    .feature-icon {
      font-size: 2.5rem;
      margin-bottom: 12px;
    }

    .feature-card h3 {
      font-size: 1rem;
    }

    /* =========================================
       OFFER
    ========================================= */

    .offer {
      background:
        linear-gradient(
          135deg,
          rgba(230, 57, 70, 0.95),
          rgba(255, 183, 3, 0.9)
        );
      color: white;
      text-align: center;
    }

    .offer h2 {
      font-size: clamp(2rem, 5vw, 3.5rem);
      margin-bottom: 15px;
    }

    .offer p {
      margin-bottom: 25px;
      font-size: 1.1rem;
    }

    /* =========================================
       LOCATION
    ========================================= */

    .location-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
    }

    .location-card,
    .contact-card {
      background: white;
      padding: 35px;
      border-radius: var(--radius);
      box-shadow: var(--shadow);
    }

    .location-card h3,
    .contact-card h3 {
      margin-bottom: 20px;
      font-size: 1.7rem;
    }

    .location-card p,
    .contact-card p {
      margin-bottom: 15px;
      color: var(--gray);
    }

    .map-placeholder {
      min-height: 300px;
      border-radius: var(--radius);
      overflow: hidden;
      background: #ddd;
    }

    .map-placeholder iframe {
      width: 100%;
      height: 300px;
      border: 0;
    }

    /* =========================================
       CONTACT
    ========================================= */

    .contact {
      background: #fff;
    }

    .contact-wrapper {
      max-width: 700px;
      margin: auto;
    }

    .contact-card {
      text-align: center;
    }

    .contact-card .phone {
      font-size: 1.5rem;
      font-weight: bold;
      color: var(--primary);
      display: block;
      margin: 15px 0 25px;
    }

    /* =========================================
       FOOTER
    ========================================= */

    footer {
      background: var(--dark);
      color: white;
      padding: 50px 0 100px;
      text-align: center;
    }

    footer h2 {
      margin-bottom: 15px;
    }

    footer p {
      color: #bbbbbb;
      margin-bottom: 8px;
    }

    .social-links {
      margin: 20px 0;
      display: flex;
      justify-content: center;
      gap: 15px;
    }

    .social-links a {
      width: 42px;
      height: 42px;
      border-radius: 50%;
      display: grid;
      place-items: center;
      background: var(--dark-light);
      transition: 0.3s;
    }

    .social-links a:hover {
      background: var(--primary);
    }

    /* =========================================
       MOBILE STICKY CTA
    ========================================= */

    .mobile-order {
      display: none;
    }

    /* =========================================
       RESPONSIVE
    ========================================= */

    @media (max-width: 900px) {

      .menu-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .features-grid {
        grid-template-columns: repeat(3, 1fr);
      }

      .about-grid,
      .location-grid {
        grid-template-columns: 1fr;
      }
    }

    @media (max-width: 650px) {

      section {
        padding: 60px 0;
      }

      .nav-links {
        display: none;
      }

      .hero {
        min-height: 90vh;
      }

      .hero h1 {
        font-size: 2.6rem;
      }

      .hero-buttons {
        flex-direction: column;
      }

      .hero-buttons .btn {
        width: 100%;
      }

      .menu-grid {
        grid-template-columns: 1fr;
      }

      .features-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .about-image img {
        height: 320px;
      }

      .mobile-order {
        display: flex;
        position: fixed;
        bottom: 0;
        left: 0;
        width: 100%;
        z-index: 9999;
        background: var(--primary);
      }

      .mobile-order a {
        width: 100%;
        text-align: center;
        color: white;
        font-weight: bold;
        padding: 16px;
      }
    }

  </style>
</head>

<body>

  <!-- =====================================
       NAVIGATION
  ====================================== -->

  <nav>
    <div class="container nav-container">

      <a href="#" class="logo">
        OK <span>Fastfood</span>
      </a>

      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#menu">Menu</a>
        <a href="#location">Location</a>
        <a href="#contact">Contact</a>
      </div>

    </div>
  </nav>


  <!-- =====================================
       HERO
  ====================================== -->

  <section class="hero">

    <div class="container">

      <div class="hero-content">

        <div class="hero-badge">
          🍔 Fresh • Fast • Delicious
        </div>

        <h1>
          Delicious Fast Food,
          Ready When You Are!
        </h1>

        <p>
          Enjoy tasty, freshly prepared and affordable fast food
          from OK Fastfood. Call us today and satisfy your hunger!
        </p>

        <div class="hero-buttons">

          <a
            href="tel:01716861596"
            class="btn btn-primary"
          >
            📞 Call & Order Now
          </a>

          <a
            href="#location"
            class="btn btn-secondary"
          >
            📍 Get Directions
          </a>

        </div>

      </div>

    </div>

  </section>


  <!-- =====================================
       ABOUT
  ====================================== -->

  <section id="about">

    <div class="container about-grid">

      <div class="about-image">

        <img
          src="https://images.unsplash.com/photo-1550547660-d9450f859349?auto=format&fit=crop&w=1000&q=80"
          alt="Delicious burger"
        >

      </div>

      <div class="about-content">

        <h2>Welcome to OK Fastfood 🍔</h2>

        <p>
          At OK Fastfood, we believe great food should be
          delicious, fresh and affordable.
        </p>

        <p>
          Whether you are craving a juicy burger, crispy fried
          chicken, tasty pizza or refreshing drinks, we are here
          to serve you quickly.
        </p>

        <p>
          Come and enjoy your favorite food in a friendly and
          welcoming environment.
        </p>

        <a
          href="tel:01716861596"
          class="btn btn-primary"
        >
          Order Now
        </a>

      </div>

    </div>

  </section>


  <!-- =====================================
       MENU
  ====================================== -->

  <section class="menu" id="menu">

    <div class="container">

      <h2 class="section-title">
        Our Popular Menu
      </h2>

      <p class="section-text">
        Explore some of our delicious customer favorites.
      </p>


      <div class="menu-grid">


        <!-- BURGER -->

        <div class="menu-card">

          <img
            src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=800&q=80"
            alt="Burger"
          >

          <div class="menu-content">

            <h3>Classic Burger 🍔</h3>

            <p>
              Juicy patty, fresh vegetables and delicious sauce.
            </p>

            <span class="price">
              ৳ Price Coming Soon
            </span>

            <a
              href="tel:01716861596"
              class="btn btn-primary"
            >
              Order Now
            </a>

          </div>

        </div>


        <!-- PIZZA -->

        <div class="menu-card">

          <img
            src="https://images.unsplash.com/photo-1513104890138-7c749659a591?auto=format&fit=crop&w=800&q=80"
            alt="Pizza"
          >

          <div class="menu-content">

            <h3>Cheesy Pizza 🍕</h3>

            <p>
              Freshly baked pizza loaded with delicious toppings.
            </p>

            <span class="price">
              ৳ Price Coming Soon
            </span>

            <a
              href="tel:01716861596"
              class="btn btn-primary"
            >
              Order Now
            </a>

          </div>

        </div>


        <!-- FRIED CHICKEN -->

        <div class="menu-card">

          <img
            src="https://images.unsplash.com/photo-1626645738196-c2a7c87a8f58?auto=format&fit=crop&w=800&q=80"
            alt="Fried Chicken"
          >

          <div class="menu-content">

            <h3>Fried Chicken 🍗</h3>

            <p>
              Crispy outside, juicy inside and full of flavor.
            </p>

            <span class="price">
              ৳ Price Coming Soon
            </span>

            <a
              href="tel:01716861596"
              class="btn btn-primary"
            >
              Order Now
            </a>

          </div>

        </div>


        <!-- SANDWICH -->

        <div class="menu-card">

          <img
            src="https://images.unsplash.com/photo-1553909489-cd47e0ef937f?auto=format&fit=crop&w=800&q=80"
            alt="Sandwich"
          >

          <div class="menu-content">

            <h3>Fresh Sandwich 🥪</h3>

            <p>
              Fresh ingredients packed into a delicious sandwich.
            </p>

            <span class="price">
              ৳ Price Coming Soon
            </span>

            <a
              href="tel:01716861596"
              class="btn btn-primary"
            >
              Order Now
            </a>

          </div>

        </div>


        <!-- SNACKS -->

        <div class="menu-card">

          <img
            src="https://images.unsplash.com/photo-1573080496219-bb080dd4f877?auto=format&fit=crop&w=800&q=80"
            alt="French Fries"
          >

          <div class="menu-content">

            <h3>Crispy Snacks 🍟</h3>

            <p>
              Perfect crispy snacks for your hunger cravings.
            </p>

            <span class="price">
              ৳ Price Coming Soon
            </span>

            <a
              href="tel:01716861596"
              class="btn btn-primary"
            >
              Order Now
            </a>

          </div>

        </div>


        <!-- DRINK -->

        <div class="menu-card">

          <img
            src="https://images.unsplash.com/photo-1544145945-f90425340c7e?auto=format&fit=crop&w=800&q=80"
            alt="Cold Drinks"
          >

          <div class="menu-content">

            <h3>Cold Drinks 🥤</h3>

            <p>
              Refresh yourself with our delicious cold drinks.
            </p>

            <span class="price">
              ৳ Price Coming Soon
            </span>

            <a
              href="tel:01716861596"
              class="btn btn-primary"
            >
              Order Now
            </a>

          </div>

        </div>

      </div>

    </div>

  </section>


  <!-- =====================================
       WHY CHOOSE US
  ====================================== -->

  <section>

    <div class="container">

      <h2 class="section-title">
        Why Choose Us?
      </h2>

      <p class="section-text">
        We focus on great taste, quality ingredients and
        excellent customer service.
      </p>


      <div class="features-grid">

        <div class="feature-card">
          <div class="feature-icon">🍔</div>
          <h3>Delicious Food</h3>
        </div>

        <div class="feature-card">
          <div class="feature-icon">⚡</div>
          <h3>Fast Service</h3>
        </div>

        <div class="feature-card">
          <div class="feature-icon">🥗</div>
          <h3>Fresh Ingredients</h3>
        </div>

        <div class="feature-card">
          <div class="feature-icon">💰</div>
          <h3>Affordable Prices</h3>
        </div>

        <div class="feature-card">
          <div class="feature-icon">😊</div>
          <h3>Customer Satisfaction</h3>
        </div>

      </div>

    </div>

  </section>


  <!-- =====================================
       OFFER
  ====================================== -->

  <section class="offer">

    <div class="container">

      <h2>
        Hungry? Order Your Favorite Food Today!
      </h2>

      <p>
        Delicious food is just one call away.
      </p>

      <a
        href="tel:01716861596"
        class="btn btn-secondary"
      >
        📞 Call Now to Order
      </a>

    </div>

  </section>


  <!-- =====================================
       LOCATION
  ====================================== -->

  <section id="location">

    <div class="container">

      <h2 class="section-title">
        Find Us
      </h2>

      <p class="section-text">
        Visit OK Fastfood and enjoy your favorite meals.
      </p>


      <div class="location-grid">

        <div class="location-card">

          <h3>📍 Our Location</h3>

          <p>
            <strong>Location:</strong>
            85C9+7JH
          </p>

          <p>
            Use Google Maps to find directions to our location.
          </p>

          <br>

          <a
            href="https://www.google.com/maps/search/?api=1&query=85C9%2B7JH"
            target="_blank"
            class="btn btn-primary"
          >
            Get Directions
          </a>

        </div>


        <div class="map-placeholder">

          <iframe
            src="https://www.google.com/maps?q=85C9%2B7JH&output=embed"
            loading="lazy"
          ></iframe>

        </div>

      </div>

    </div>

  </section>


  <!-- =====================================
       CONTACT
  ====================================== -->

  <section class="contact" id="contact">

    <div class="container">

      <div class="contact-wrapper">

        <div class="contact-card">

          <h3>Contact OK Fastfood</h3>

          <p>
            Have a question or ready to order?
          </p>

          <p>
            Call us now and enjoy delicious fast food!
          </p>

          <a
            href="tel:01716861596"
            class="phone"
          >
            📞 01716-861596
          </a>

          <a
            href="tel:01716861596"
            class="btn btn-primary"
          >
            📞 Call Now
          </a>

        </div>

      </div>

    </div>

  </section>


  <!-- =====================================
       FOOTER
  ====================================== -->

  <footer>

    <div class="container">

      <h2>
        OK Fastfood 🍔
      </h2>

      <p>
        Delicious. Fresh. Affordable.
      </p>

      <p>
        📞 01716-861596
      </p>

      <p>
        📍 85C9+7JH
      </p>


      <div class="social-links">

        <a href="#" aria-label="Facebook">
          f
        </a>

        <a href="#" aria-label="Instagram">
          ◎
        </a>

        <a href="#" aria-label="WhatsApp">
          W
        </a>

      </div>


      <p>
        © 2026 OK Fastfood.
        All Rights Reserved.
      </p>

    </div>

  </footer>


  <!-- =====================================
       MOBILE STICKY ORDER BUTTON
  ====================================== -->

  <div class="mobile-order">

    <a href="tel:01716861596">
      📞 Call & Order Now
    </a>

  </div>


  <!-- =====================================
       SIMPLE JAVASCRIPT
  ====================================== -->

  <script>

    console.log("OK Fastfood Website Loaded Successfully");

  </script>

</body>
</html>
