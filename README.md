<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>JobSeva.in - हर नौकरी, एक जगह पर</title>
  <meta name="description" content="JobSeva.in - हर नौकरी, एक जगह पर। सरकारी और प्राइवेट नौकरियाँ, रिज्यूमे अपलोड, और रोजगार से जुड़ी जानकारी।" />
  <style>
    :root{--accent:#0b74de;--dark:#0b1720;--muted:#6b7280}
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%;font-family:'Noto Sans Devanagari', system-ui, sans-serif;line-height:1.5;color:var(--dark);background:#f8fafc}
    a{color:inherit;text-decoration:none}
    img{max-width:100%;height:auto;display:block}
    .container{max-width:1100px;margin:0 auto;padding:24px}

    header{background:white;border-bottom:2px solid var(--accent);box-shadow:0 3px 8px rgba(0,0,0,0.05)}
    .nav{display:flex;align-items:center;justify-content:space-between;padding:14px 0}
    .brand{display:flex;align-items:center;gap:10px}
    .logo{background:var(--accent);color:white;padding:10px 14px;border-radius:8px;font-weight:700}
    nav ul{display:flex;gap:20px;list-style:none}
    nav a{font-weight:500}
    .cta{background:var(--accent);color:white;padding:8px 16px;border-radius:8px}

    .hero{display:grid;grid-template-columns:1fr 400px;align-items:center;gap:30px;padding:50px 0}
    .hero h1{font-size:clamp(28px,4vw,42px);margin-bottom:12px;color:var(--accent)}
    .hero p{color:var(--muted);margin-bottom:18px}

    .card{background:white;border-radius:12px;box-shadow:0 4px 12px rgba(0,0,0,0.06);padding:18px}

    .jobs{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px;margin-top:24px}
    .job{background:white;padding:16px;border-radius:10px;border:1px solid #e6eef7}
    .job h3{color:var(--accent);margin-bottom:8px}

    .contact-form{display:flex;flex-direction:column;gap:10px}
    input,textarea,button{font:inherit}
    input,textarea{padding:10px;border:1px solid #d1d5db;border-radius:8px}
    button{padding:10px 14px;border-radius:8px;border:0;background:var(--accent);color:white;cursor:pointer}

    footer{margin-top:36px;padding:24px 0;border-top:1px solid #e6eef7;text-align:center;color:var(--muted)}

    @media(max-width:900px){.hero{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo">JS</div>
        <div>
          <strong>JobSeva.in</strong><br>
          <small style="color:var(--muted)">हर नौकरी, एक जगह पर</small>
        </div>
      </div>
      <nav>
        <ul>
          <li><a href="#home">होम</a></li>
          <li><a href="#govt">सरकारी नौकरियाँ</a></li>
          <li><a href="#private">प्राइवेट नौकरियाँ</a></li>
          <li><a href="#resume">रिज्यूमे अपलोड करें</a></li>
          <li><a href="#contact">संपर्क करें</a></li>
        </ul>
      </nav>
      <a class="cta" href="#resume">अभी आवेदन करें</a>
    </div>
  </header>

  <main class="container">
    <section id="home" class="hero">
      <div>
        <h1>हर नौकरी, एक जगह पर</h1>
        <p>JobSeva.in पर पाएँ सभी सरकारी और प्राइवेट नौकरियों की ताज़ा जानकारी। जल्दी आवेदन करें और अपने करियर की शुरुआत करें।</p>
        <a class="cta" href="#govt">सरकारी नौकरियाँ देखें</a>
      </div>
      <aside class="card">
        <h3>तुरंत आवेदन करें</h3>
        <p>अपना नाम और मोबाइल नंबर दर्ज करें – हमारी टीम आपसे संपर्क करेगी।</p>
        <form class="contact-form" onsubmit="return submitLead(event)">
          <input type="text" placeholder="पूरा नाम" required />
          <input type="tel" placeholder="मोबाइल नंबर" required />
          <button type="submit">सबमिट करें</button>
        </form>
        <div id="msg" style="display:none;color:green;margin-top:6px">धन्यवाद! हम जल्द ही संपर्क करेंगे।</div>
      </aside>
    </section>

    <section id="govt">
      <h2>सरकारी नौकरियाँ</h2>
      <div class="jobs">
        <div class="job">
          <h3>राजस्थान पुलिस भर्ती 2025</h3>
          <p>आवेदन की अंतिम तिथि: 30 नवम्बर 2025</p>
          <button>विवरण देखें</button>
        </div>
        <div class="job">
          <h3>रेलवे अप्रेंटिस 2025</h3>
          <p>योग्यता: 10वीं पास, ITI</p>
          <button>विवरण देखें</button>
        </div>
      </div>
    </section>

    <section id="private">
      <h2 style="margin-top:36px">प्राइवेट नौकरियाँ</h2>
      <div class="jobs">
        <div class="job">
          <h3>BPO Executive (जयपुर)</h3>
          <p>सैलरी: ₹15,000 – ₹25,000 | अनुभव: 0–2 वर्ष</p>
          <button>अभी आवेदन करें</button>
        </div>
        <div class="job">
          <h3>Computer Operator (मERTA CITY)</h3>
          <p>सैलरी: ₹10,000 – ₹18,000 | बेसिक कंप्यूटर नॉलेज</p>
          <button>अभी आवेदन करें</button>
        </div>
      </div>
    </section>

    <section id="resume" style="margin-top:36px">
      <h2>रिज्यूमे अपलोड करें</h2>
      <div class="card" style="margin-top:12px">
        <form class="contact-form" onsubmit="return uploadResume(event)">
          <input type="text" placeholder="नाम" required />
          <input type="email" placeholder="ईमेल" />
          <input type="file" required />
          <button type="submit">अपलोड करें</button>
        </form>
        <div id="rmsg" style="display:none;color:green;margin-top:6px">रिज्यूमे सफलतापूर्वक सबमिट हुआ (डेमो)।</div>
      </div>
    </section>

    <section id="contact" style="margin-top:36px">
      <h2>संपर्क करें</h2>
      <div class="card" style="margin-top:12px">
        <p>📍 पता: MERTA CITY</p>
        <p>📞 संपर्क: 8875335314, 9782617494</p>
        <p>📧 ईमेल: jobseva@gmail.com</p>
      </div>
    </section>

    <footer>
      © 2025 <strong>JobSeva.in</strong> | हर नौकरी, एक जगह पर
    </footer>
  </main>

  <script>
    function submitLead(e){e.preventDefault();document.getElementById('msg').style.display='block';setTimeout(()=>{e.target.reset();},1000);return false;}
    function uploadResume(e){e.preventDefault();document.getElementById('rmsg').style.display='block';setTimeout(()=>{e.target.reset();document.getElementById('rmsg').style.display='none';},3000);return false;}
  </script>
</body>
</html>
