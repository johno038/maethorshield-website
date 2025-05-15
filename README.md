<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maethor Shield</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=Crimson+Text:wght@600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: #ffffff;
      margin: 0;
      padding: 0;
      color: #1a1a1a;
    }
    header {
      background: linear-gradient(to bottom, #f5f7fa, #e9edf1);
      padding: 4rem 1.5rem 2rem;
      text-align: center;
      border-bottom: 1px solid #e5e5e5;
      position: relative;
    }
    header h1 {
      margin: 0;
      font-size: 2.75rem;
      font-family: 'Crimson Text', serif;
      color: #101820;
    }
    header p {
      font-size: 1.2rem;
      color: #555;
      margin-top: 0.5rem;
    }
    nav {
      position: absolute;
      top: 1.5rem;
      right: 2rem;
      font-size: 0.95rem;
    }
    nav a {
      margin-left: 1rem;
      color: #101820;
      text-decoration: none;
      font-weight: 500;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      max-width: 960px;
      margin: 4rem auto;
      padding: 0 1.5rem;
    }
    .section {
      padding: 3rem 0;
      border-bottom: 1px solid #eaeaea;
    }
    h2 {
      margin-top: 0;
      font-size: 1.75rem;
      font-family: 'Crimson Text', serif;
      color: #101820;
    }
    ul {
      padding-left: 1.2rem;
      line-height: 1.8;
    }
    footer {
      text-align: center;
      padding: 3rem 1rem 2rem;
      font-size: 0.9rem;
      color: #888;
      background: #f9f9f9;
      border-top: 1px solid #eaeaea;
    }
    .btn {
      display: inline-block;
      background: #101820;
      color: white;
      padding: 0.85rem 1.75rem;
      border-radius: 6px;
      text-decoration: none;
      font-weight: 600;
      margin-top: 1.5rem;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #333;
    }
    a {
      color: #101820;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .flex-row {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      align-items: flex-start;
    }
    .flex-row > div, .flex-row img {
      flex: 1;
      min-width: 260px;
    }
    .portrait {
      max-width: 180px;
      border-radius: 8px;
      object-fit: cover;
    }
    .testimonial {
      font-style: italic;
      margin: 2rem 0;
      padding-left: 1rem;
      border-left: 4px solid #ccc;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s ease forwards;
    }
    .testimonial:nth-of-type(1) {
      animation-delay: 0.3s;
    }
    .testimonial:nth-of-type(2) {
      animation-delay: 0.6s;
    }
    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  
    @media (max-width: 600px) {
      header h1 { font-size: 2rem; }
      nav { position: static; margin-top: 1rem; text-align: center; }
      .flex-row { flex-direction: column; }
      .btn { width: 100%; text-align: center; }
    }

</head>
<body>
  <header>
    <img src="/mnt/data/A_vector_graphic_logo_for_%22Maethor_Shield%22_feature.png" alt="Maethor Shield Logo" style="max-width: 160px; margin-bottom: 1rem;" />
    <h1>Maethor Shield</h1>
    <p>Protecting Independent Contractors</p>
    <nav>
      <a href="#about">About</a>
      <a href="#pack">Contractor Pack</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  
    <div class="section flex-row" id="about">
      <img src="/mnt/data/1557772648441.jpeg" alt="Matt Johnston" class="portrait" />
      <div>
        <h2>About</h2>
        <p>Maethor Shield was born from years of first-hand experience navigating the complexities of IR35 compliance as a delivery consultant within the UK Ministry of Defence. Having worked across high-stakes projects involving governance, assurance, and requirements capture, I saw how even skilled and genuinely independent contractors were being exposed to unnecessary IR35 risks — not because of their intent, but because of poorly defined scopes, sloppy contracts, and a lack of consistent evidence.</p>
        <p>This toolkit exists because I needed it myself. It pulls together everything I wish I had at the start: a structured way to prove independence, challenge scope creep, and avoid behaviours that blur the line between contractor and disguised employee. Whether you're a one-person limited company or leading a small delivery team, Maethor Shield gives you the clarity and documentation you need to stand your ground — confidently and compliantly.</p>
        <form action="/downloads/IR35-sample-checklist.pdf" method="GET">
  <button type="submit" class="btn">Download a Free Sample</button>
<input type="hidden" name="_next" value="https://maethorshield.com/thank-you.html" />
        <input type="hidden" name="_captcha" value="false" />
      </form>
      </div>
    </div>

    <div class="section flex-row" id="pack">
      <div>
        <h2>The Outside IR35 Contractor Pack</h2>
        <p>Confidently prove and maintain your Outside IR35 status with a practical toolkit, trusted by delivery professionals.</p>
        <ul>
          <li>Working Practices Checklist</li>
          <li>IR35 Evidence Log</li>
          <li>Role Definition Templates</li>
          <li>Contract Clause Red Flags</li>
          <li>Client Engagement Guide</li>
          <li>Audit Folder & README</li>
        </ul>
        <form action="https://buy.stripe.com/test_7sIbKc9Uq2pAbqM3cc" method="GET" target="_blank">
  <button type="submit" class="btn">Buy the Full Pack</button>
</form>
      </div>
      <img src="/mnt/data/A_vector_graphic_logo_for_%22Maethor_Shield%22_feature.png" alt="Pack Preview" style="width: 100%; border-radius: 8px; object-fit: cover;" />
    </div>

    <div class="section" style="background-color: #f5f9fc; border-radius: 8px;">
      <h2>Trusted By</h2>
      <ul style="list-style: none; padding: 0; display: flex; flex-wrap: wrap; gap: 1.5rem; justify-content: space-around;">
        <li><strong>Defence SME</strong></li>
        <li><strong>Cyber Consultancy</strong></li>
        <li><strong>Delivery Assurance Firm</strong></li>
        <li><strong>Recruitment Partner</strong></li>
      </ul>
    </div>
    <div class="section" style="background-color: #e6f0f8; border-radius: 8px;" id="testimonials">
      <h2>What People Are Saying</h2>
      <div class="testimonial" style="animation-delay: 0.3s;">
        “Finally — a product that actually helps you defend your IR35 status.”<br />
        <strong>— Senior MoD Contractor, 2024</strong>
      </div>
      <div class="testimonial" style="animation-delay: 0.6s;">
        “I reused these templates across three bids. Worth every penny.”<br />
        <strong>— Delivery Lead, Defence SME</strong>
      </div>
    </div>
      <div class="section" id="contact" style="background-color: #f1f8f6; border-radius: 8px;">
      <h2>Contact Us</h2>
      <form action="https://formsubmit.co/hello@maethorshield.com" method="POST">
        <input type="text" name="name" placeholder="Your name" required style="width: 100%; padding: 0.75rem; margin-bottom: 1rem;" />
        <input type="email" name="email" placeholder="Your email" required style="width: 100%; padding: 0.75rem; margin-bottom: 1rem;" />
        <textarea name="message" placeholder="How can we help?" required style="width: 100%; padding: 0.75rem; margin-bottom: 1rem;"></textarea>
        <button type="submit" class="btn">Send Message</button>
      </form>
      <hr style="margin: 2rem 0;" />
      <h2>Support & Licensing</h2>
      <p>We offer flexible licensing options and advisory support for contractor teams, recruiters, and SMEs. All advice is grounded in real-world delivery experience and regulatory compliance.</p>
      <p>Email us at <a href="mailto:hello@maethorshield.com">hello@maethorshield.com</a></p>
    </div>
  </main>
  <footer>
    &copy; 2025 Maethor Shield — a trading name of M J Johnston Consulting Ltd<br />
    <a href="https://www.linkedin.com/in/matt-j-s-johnston" target="_blank">Connect on LinkedIn</a>
  </footer>
</body>
</html>
# maethorshield-website
