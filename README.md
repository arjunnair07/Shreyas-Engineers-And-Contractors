<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shreyas Engineers and Contractors</title>
  <style>
    /* General Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.75;
      background-color: #f4f4f4;
      color: #333;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
      overflow: hidden;
    }
    /* Header with Hero Section */
    header {
      background: linear-gradient(135deg, #003366 70%, #ffd700 100%);
      color: #fff;
      text-align: center;
      padding: 40px 0 30px;
      position: relative;
    }
    header img {
      max-width: 150px;
      height: auto;
      margin-bottom: 10px;
      border-radius: 50%;
      box-shadow: 0 4px 16px rgba(0,0,0,0.07);
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      letter-spacing: 1px;
    }
    header p {
      margin: 14px 0 24px;
      font-size: 1.15em;
      color: #ffd700;
      font-weight: bold;
      letter-spacing: 0.5px;
    }
    .cta-btn {
      display: inline-block;
      background: #ffd700;
      color: #003366;
      padding: 14px 32px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      margin-top: 18px;
      transition: background 0.2s, color 0.2s, border 0.2s;
      border: none;
      box-shadow: 0 3px 12px rgba(0,0,0,0.05);
    }
    .cta-btn:hover {
      background: #003366;
      color: #ffd700;
      border: 1px solid #ffd700;
    }
    /* Sections */
    section {
      padding: 42px 0;
      background: #fff;
      margin-bottom: 14px;
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s, transform 0.7s;
      border-radius: 8px;
      box-shadow: 0 2px 20px rgba(0,0,20,0.035);
    }
    section.visible {
      opacity: 1;
      transform: none;
    }
    section h2 {
      text-align: center;
      color: #003366;
      margin-bottom: 18px;
      font-size: 2em;
      letter-spacing: 0.5px;
    }
    /* Services List */
    .services ul {
      list-style-type: none;
      padding-left: 0;
      margin-top: 24px;
      font-size: 1.08em;
    }
    .services li {
      margin-bottom: 14px;
      display: flex;
      align-items: center;
    }
    .services li::before {
      content: "✔";
      color: #003366;
      margin-right: 12px;
      font-weight: bold;
    }
    .clients p {
      text-align: center;
      font-size: 1.1em;
      letter-spacing: 0.4px;
    }
    /* Contact Info */
    .contact-info {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      font-size: 1.08em;
      gap: 10px;
    }
    .contact-info a {
      color: #003366;
      text-decoration: none;
    }
    .contact-info a:hover {
      text-decoration: underline;
    }
    /* Responsive */
    @media (max-width: 768px) {
      .container {
        width: 98%;
      }
      header h1 {
        font-size: 1.3em;
      }
      section {
        padding: 24px 0;
      }
    }
    @media (max-width: 480px) {
      header img {
        max-width: 85px;
      }
      section h2 {
        font-size: 1.2em;
      }
    }
    /* Footer */
    footer {
      background: #003366;
      color: #fff;
      text-align: center;
      padding: 22px 0;
      font-size: 1em;
      letter-spacing: 0.6px;
      border-top: 3px solid #ffd700;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <img src="logo.jpg" alt="Shreyas Engineers & Contractors Logo" />
      <h1>Shreyas Engineers and Contractors</h1>
      <p>Trusted Experts in Offshore Platform Engineering for ONGC</p>
      <a href="#contact" class="cta-btn">Contact Us</a>
    </div>
  </header>

  <section class="about">
    <div class="container">
      <h2>About Us</h2>
      <p>Shreyas Engineers and Contractors is a top-ranked engineering and contracting firm, renowned for our specialization in offshore platform projects, oil rigging, and drilling fabrication works. We are a proud and long-standing contractor for ONGC, delivering world-class offshore infrastructure with precision and commitment.</p>
    </div>
  </section>

  <section class="services">
    <div class="container">
      <h2>Our Services</h2>
      <ul>
        <li>Offshore platform design and construction</li>
        <li>Oil rig structural fabrication and assembly</li>
        <li>Drilling platform engineering solutions</li>
        <li>Welding, pipeline, and structural works</li>
        <li>Maintenance and upgrade of offshore systems</li>
      </ul>
    </div>
  </section>

  <section class="clients">
    <div class="container">
      <h2>Our Clients</h2>
      <p>We are a preferred contractor for ONGC and serve major oil and gas companies in India.</p>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <div class="contact-info">
        <p>Email: <a href="mailto:shreyasengineeringsongc@gmail.com">shreyasengineeringsongc@gmail.com</a></p>
        <p>Phone: <a href="tel:+919820064872">+91 9820064872</a></p>
        <p>Address: <a href="https://www.google.com/search?sca_esv=a0f38eb77c23691f&amp;rlz=1C1SQJL_enIN915IN915&amp;sxsrf=AE3TifMii2W0R4lbr_zmO83vGg6WPFk8hA:1753805249333&amp;q=shreyas+engineers+and+contractors+address&amp;ludocid=9843437290265415290&amp;sa=X&amp;ved=2ahUKEwjl75DXueKOAxW91TgGHdMEBY4Q6BN6BAgwEAI" target="_blank" rel="noopener noreferrer">S1/S2 Tandon Chl, 28 JB Road, Barrister Nath Pai Marg, Cotton Green (W), Mumbai, Maharashtra 400033</a></p>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Shreyas Engineers and Contractors. All rights reserved.</p>
    </div>
  </footer>

  <script>
    // Fade in sections on scroll
    function revealSections() {
      document.querySelectorAll('section').forEach(function(sec) {
        const sectionTop = sec.getBoundingClientRect().top;
        if (sectionTop < window.innerHeight - 80) {
          sec.classList.add('visible');
        }
      });
    }
    document.addEventListener('scroll', revealSections);
    document.addEventListener('DOMContentLoaded', () => {
      revealSections();
    });
  </script>
</body>
</html>
