# clarityink.website<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ClarityInk.Apparel</title>
  <link rel="icon" type="image/png" href="assets/logo.png">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #3e416d;
      --accent-color: #9c9eff;
      --bg-light: #f7f9fc;
      --text-dark: #222;
      --muted: #666;
    }
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: var(--bg-light);
      color: var(--text-dark);
    }
    header {
      background: #ffffff;
      color: #333;
      text-align: center;
      padding: 2rem 1rem;
      border-bottom: 1px solid #e5e5e5;
    }
    header img {
      width: 180px;
      margin-bottom: 1rem;
    }
    nav {
      background: var(--primary-color);
      padding: 0.75rem;
      text-align: center;
    }
    nav a {
      color: #ffffff;
      margin: 0.5rem;
      text-decoration: none;
      font-weight: 600;
      display: inline-block;
    }
    .section {
      padding: 4rem 1.5rem;
      max-width: 900px;
      margin: auto;
    }
    .section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #444;
    }
    .section p {
      font-size: 1.1rem;
      line-height: 1.6;
    }
    .section img {
      width: 100%;
      border-radius: 12px;
      margin-top: 1.5rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .product-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }
    .product-gallery img {
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      width: 100%;
      height: auto;
    }
    footer {
      text-align: center;
      padding: 1.5rem;
      background: #f0f0f0;
      font-size: 0.9rem;
      color: var(--muted);
      border-top: 1px solid #ddd;
    }
    a.button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.7rem 1.5rem;
      background-color: var(--primary-color);
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: 600;
    }
    .social-links {
      margin-top: 1rem;
    }
    .social-links a {
      margin: 0 10px;
      text-decoration: none;
      color: var(--primary-color);
      font-weight: 600;
    }
    form {
      margin-top: 2rem;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    input, textarea {
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-family: inherit;
    }
    button[type="submit"] {
      background-color: var(--primary-color);
      color: white;
      padding: 0.75rem;
      border: none;
      border-radius: 6px;
      font-weight: 600;
      cursor: pointer;
    }
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 0.3rem 0;
      }
      .section {
        padding: 2rem 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="assets/logo.png" alt="ClarityInk.Apparel Logo">
    <h1>ClarityInk.Apparel</h1>
    <p style="font-size: 1.1rem; color: var(--muted); max-width: 600px; margin: auto;">
      Apparel that speaks from the heart. Designed with intention. Worn with purpose.
    </p>
    <div class="social-links">
      <a href="https://instagram.com/clarityink.apparel" target="_blank">Instagram</a>
      <a href="https://facebook.com/clarityink.apparel" target="_blank">Facebook</a>
      <a href="https://pinterest.com/clarityinkapparel" target="_blank">Pinterest</a>
    </div>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#shop">Shop</a>
    <a href="#contact">Contact</a>
    <a href="#community">Community</a>
    <a href="#impact">Impact</a>
    <a href="#newsletter">Newsletter</a>
    <a href="values.html">Values</a>
    <a href="faqs.html">FAQs</a>
    <a href="styleguide.html">Style Guide</a>
  </nav>

  <!-- Existing sections remain unchanged -->

  <div id="impact" class="section">
    <h2>Our Impact</h2>
    <p>
      At ClarityInk.Apparel, giving back is part of our DNA. A portion of proceeds supports mental health initiatives and creative arts therapy for youth. Every purchase helps spread awareness and spark healing conversations.
    </p>
    <img src="https://source.unsplash.com/800x500/?impact,hope" alt="Impact and outreach">
  </div>

  <div id="newsletter" class="section">
    <h2>Join the Newsletter</h2>
    <p>
      Be the first to hear about new drops, exclusive discounts, and stories from our creative community. No spam, just soulful updates.
    </p>
    <form action="https://formspree.io/f/moqgqepv" method="POST">
      <input type="email" name="email" placeholder="Your Email" required>
      <button type="submit">Subscribe</button>
    </form>
  </div>

  <footer>
    &copy; 2025 ClarityInk.Apparel. All rights reserved.
  </footer>
</body>
</html>
