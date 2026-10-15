<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="EasyWrite Ghana helps you create professional letters, CVs, and business content.">
  <title>EasyWrite Ghana | Words That Work</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #18302b;
      background: #f7faf8;
      line-height: 1.6;
    }
    header {
      background: #075e45;
      color: white;
      padding: 18px 7%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }
    header h2 { margin: 0; }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 16px;
    }
    .hero {
      padding: 75px 7%;
      text-align: center;
      background: #e4f5eb;
    }
    .hero h1 {
      font-size: clamp(32px, 5vw, 52px);
      line-height: 1.15;
      margin: 0 auto 20px;
      max-width: 750px;
    }
    .hero p {
      max-width: 650px;
      margin: 0 auto 25px;
      font-size: 18px;
    }
    .button {
      display: inline-block;
      background: #075e45;
      color: white;
      padding: 13px 23px;
      border-radius: 7px;
      text-decoration: none;
      font-weight: bold;
    }
    section { padding: 48px 7%; }
    section h2 { text-align: center; margin-top: 0; }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 25px;
    }
    .card {
      background: white;
      padding: 24px;
      border-radius: 12px;
      border: 1px solid #e1ebe5;
    }
    .card h3 { color: #075e45; }
    .center { text-align: center; }
    .price { font-size: 27px; font-weight: bold; }
    .contact { background: #e4f5eb; text-align: center; }
    footer {
      background: #12372c;
      color: white;
      text-align: center;
      padding: 22px;
    }
    @media (max-width: 520px) {
      header { justify-content: center; }
      nav a { margin: 0 7px; }
      .hero { padding: 55px 6%; }
    }
  </style>
</head>
<body>
  <header>
    <h2>EasyWrite Ghana ✍️</h2>
    <nav>
      <a href="#services">Services</a>
      <a href="#pricing">Pricing</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <div class="hero">
      <h1>Words That Work. Ideas That Shine.</h1>
      <p>
        Create clear, professional writing for your career,
        business and everyday life. Simple, helpful and made for you.
      </p>
      <a class="button" href="#services">Explore Our Services</a>
    </div>

    <section id="services">
      <h2>How We Can Help You</h2>
      <div class="cards">
        <div class="card">
          <h3>📄 CVs & Cover Letters</h3>
          <p>Present your experience clearly with professional career documents.</p>
        </div>
        <div class="card">
          <h3>✉️ Professional Letters</h3>
          <p>Write polished application letters, requests and business emails.</p>
        </div>
        <div class="card">
          <h3>💡 Business Writing</h3>
          <p>Improve product descriptions, business proposals and advertisements.</p>
        </div>
        <div class="card">
          <h3>🌍 Rewrite & Translate</h3>
          <p>Make your writing clearer and communicate across languages.</p>
        </div>
      </div>
    </section>

    <section id="pricing">
      <h2>Simple, Affordable Service</h2>
      <div class="cards">
        <div class="card center">
          <h3>Free Starter</h3>
          <p class="price">GH₵0</p>
          <p>Explore our services and ask about available writing samples.</p>
        </div>
        <div class="card center">
          <h3>Personal Writing</h3>
          <p class="price">Get a Quote</p>
          <p>Tell us what you need and receive a price before work begins.</p>
        </div>
      </div>
    </section>

    <section id="contact" class="contact">
      <h2>Let's Get Your Words Right</h2>
      <p>email us to discuss your writing needs.</p>
      <a class="button" href="mailto:expensivejr93@gmail.com?subject=EasyWrite%20Ghana%20Enquiry">
        Email EasyWrite Ghana
      </a>
      <p><small>Website owner: replace the sample email address with your own before publishing.</small></p>
    </section>
  </main>

  <footer>
    <p>© 2026 EasyWrite Ghana. All rights reserved.</p>
  </footer>
</body>
</html>
