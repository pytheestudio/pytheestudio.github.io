<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pythee Studio</title>

  <style>
    /* =========================
       FLORA-INSPIRED THEME
       Pink + Green Magical Palette
    ========================== */
    :root {
      --primary: #ff4fb3;   /* magical pink */
      --accent: #7be495;    /* soft nature green */
      --bg: #fff7fb;        /* soft pink-white background */
      --text: #2b2b2b;      /* dark readable text */
      --card: #ffffff;      /* clean card */
      --border: #f2c6de;    /* soft pink border */
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid var(--border);
      background: #fff;
    }

    header h1 {
      color: var(--primary);
      font-size: 20px;
    }

    nav a {
      margin-left: 15px;
      text-decoration: none;
      color: var(--text);
      transition: 0.2s;
    }

    nav a:hover {
      color: var(--primary);
    }

    /* HERO SECTION */
    .hero {
      padding: 80px 20px;
      text-align: center;
      background: linear-gradient(135deg, #ffe4f2, #e6fff0);
    }

    .hero h2 {
      font-size: 36px;
      color: var(--primary);
      margin-bottom: 10px;
    }

    .hero p {
      max-width: 600px;
      margin: 0 auto 20px;
      color: #444;
    }

    .btn {
      display: inline-block;
      padding: 10px 20px;
      margin: 5px;
      border-radius: 20px;
      text-decoration: none;
      color: white;
      background: var(--primary);
      transition: 0.2s ease;
      box-shadow: 0 4px 10px rgba(255, 79, 179, 0.2);
    }

    .btn:hover {
      background: var(--accent);
      color: #1f1f1f;
    }

    .btn.secondary {
      background: var(--accent);
      color: #1f1f1f;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }

    h3 {
      color: var(--primary);
      margin-bottom: 20px;
      text-align: center;
    }

    /* SERVICES */
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    .card {
      padding: 20px;
      border: 1px solid var(--border);
      border-radius: 15px;
      background: var(--card);
      box-shadow: 0 5px 15px rgba(0,0,0,0.05);
      transition: 0.2s;
    }

    .card:hover {
      transform: translateY(-3px);
      border-color: var(--accent);
    }

    .card h4 {
      color: var(--primary);
      margin-bottom: 10px;
    }

    /* CONTACT */
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 400px;
      margin: auto;
    }

    input, textarea {
      padding: 10px;
      border: 1px solid var(--border);
      border-radius: 10px;
      background: #fff;
      color: var(--text);
    }

    button {
      padding: 10px;
      border: none;
      background: var(--primary);
      color: white;
      cursor: pointer;
      border-radius: 20px;
      transition: 0.2s;
    }

    button:hover {
      background: var(--accent);
      color: #1f1f1f;
    }

    footer {
      text-align: center;
      padding: 20px;
      border-top: 1px solid var(--border);
      font-size: 14px;
      color: #777;
      background: #fff;
    }
  </style>
</head>

<body>

  <header>
    <h1>Pythee Studio</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Bring AI Into Your Business</h2>

    <p>
      Pythee Studio helps small businesses integrate AI, automate workflows,
      and modernize their websites for a smarter digital presence.
    </p>

    <a class="btn" href="#contact">Book a Consultation</a>
    <a class="btn secondary" href="#services">View Services</a>
  </div>

  <section id="services">
    <h3>Services</h3>

    <div class="services">
      <div class="card">
        <h4>AI Automation</h4>
        <p>Streamline repetitive tasks using AI tools.</p>
      </div>

      <div class="card">
        <h4>Chatbots</h4>
        <p>Improve customer support with AI assistants.</p>
      </div>

      <div class="card">
        <h4>Website Modernization</h4>
        <p>Upgrade outdated websites into modern experiences.</p>
      </div>

      <div class="card">
        <h4>AI Consulting</h4>
        <p>Get guidance on how to use AI in your business.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h3>About</h3>
    <p style="text-align:center; max-width:700px; margin:auto;">
      Pythee Studio helps small businesses adopt AI in a simple, practical way.
      We focus on real results, not technical complexity.
    </p>
  </section>

  <section id="contact">
    <h3>Contact</h3>

    <form>
      <input type="text" placeholder="Your Name" />
      <input type="email" placeholder="Your Email" />
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    © 2026 Pythee Studio. All rights reserved.
  </footer>

</body>
</html>
