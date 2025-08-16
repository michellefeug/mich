<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Michelle Feugueng | Virtual Assistant</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; padding:0; line-height:1.6; }
    header { background:#2a2a72; color:#fff; padding:20px 0; text-align:center; }
    nav a { color:#fff; margin:0 15px; text-decoration:none; font-weight:bold; }
    .hero { background:#f4f4f4; padding:60px; text-align:center; }
    .hero h1 { font-size:2.5rem; margin-bottom:10px; }
    section { padding:40px 20px; max-width:1000px; margin:auto; }
    h2 { color:#2a2a72; margin-bottom:20px; }
    .services { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; }
    .card { background:#fff; padding:20px; border:1px solid #ddd; border-radius:8px; }
    footer { background:#2a2a72; color:#fff; text-align:center; padding:20px; margin-top:40px; }
    form { display:flex; flex-direction:column; max-width:500px; margin:auto; }
    input, textarea { padding:10px; margin:10px 0; border:1px solid #ccc; border-radius:5px; }
    button { background:#2a2a72; color:#fff; border:none; padding:12px; border-radius:5px; cursor:pointer; }
    button:hover { background:#4444aa; }
  </style>
</head>
<body>
  <header>
    <h1>Michelle Feugueng</h1>
    <p>Virtual Assistant | Helping You Work Smarter</p>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Efficient. Reliable. Organized.</h1>
    <p>I help busy entrepreneurs and small businesses streamline their tasks so they can focus on growth.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I’m Michelle, your dedicated Virtual Assistant. With strong skills in organization, communication, and digital tools, I specialize in helping entrepreneurs, creators, and businesses manage their schedules, communications, and admin tasks. My goal is to give you back your time so you can focus on what matters most.</p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="services">
      <div class="card">
        <h3>Admin Support</h3>
        <p>Email management, data entry, scheduling, and organization.</p>
      </div>
      <div class="card">
        <h3>Social Media</h3>
        <p>Content scheduling, engagement, and basic design support.</p>
      </div>
      <div class="card">
        <h3>Research & Assistance</h3>
        <p>Market research, travel planning, and project coordination.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="How can I help you?" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Michelle Feugueng | Virtual Assistant</p>
  </footer>
</body>
</html>
