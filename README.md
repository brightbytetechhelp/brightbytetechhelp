<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BrightByte Tech Help</title>
  <meta name="description" content="BrightByte Tech Help — simple tech and school project help with parent supervision." />
  <style>
    :root{
      --blue:#1e6fd9; --light:#eef6ff; --dark:#0b2b55;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color:var(--dark); background: radial-gradient(1200px 600px at 50% -10%, #d7ebff, #ffffff);
    }
    .container{max-width:960px; margin:0 auto; padding:32px 20px}
    header{text-align:center; padding:32px 0}
    .star{
      width:180px; height:180px; margin:20px auto; position:relative;
      background: linear-gradient(180deg, #4aa3ff, #1e6fd9);
      clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
      display:flex; align-items:center; justify-content:center; color:#fff; font-weight:800; letter-spacing:2px;
      box-shadow:0 20px 40px rgba(30,111,217,.25);
    }
    h1{font-size:40px; margin:10px 0}
    h2{font-size:22px; margin:6px 0; color:#234}
    .tag{font-size:18px; margin-top:12px}
    .card{
      background:#fff; border-radius:18px; padding:28px; margin:24px 0;
      box-shadow:0 10px 30px rgba(0,0,0,.06)
    }
    .grid{display:grid; grid-template-columns: repeat(auto-fit, minmax(220px,1fr)); gap:16px}
    .pill{display:inline-flex; align-items:center; gap:10px; padding:12px 16px; border-radius:999px; background:var(--light)}
    a.btn{
      cursor:pointer;
      display:inline-block; background:var(--blue); color:#fff; padding:14px 18px; border-radius:12px; text-decoration:none; font-weight:700
    }
    footer{text-align:center; padding:24px 0; color:#456}
    small{opacity:.9}
  </style>
</head>
<body>
  <header class="container">
    <h2>Jeshnavchandra Doppalapudi’s</h2>
    <div class="star">BRIGHTBYTE<br/>TECH HELP</div>
    <h1>BrightByte Tech Help</h1>
    <p class="tag">I help with simple tech and school projects.</p>
  </header>

  <main class="container">
    <section class="card">
      <div class="grid">
        <div>
          <h3>What I can help with</h3>
          <ul>
            <li>Basic computer help</li>
            <li>School tech projects</li>
            <li>Simple websites & slides</li>
            <li>Beginner coding questions</li>
          </ul>
        </div>
        <div>
          <h3>Pricing</h3>
          <p><strong>I don’t charge</strong> — support is optional and appreciated.</p>
          <p><small>With parent supervision.</small></p>
        </div>
      </div>
    </section>

    <section class="card">
      <h3>Contact</h3>
      <p class="pill"><a href="mailto:BrightByteTechHelp@gmail.com" style="text-decoration:none;color:inherit">📧 BrightByteTechHelp@gmail.com</a></p>
      <p class="pill">📞 +61 478 359 509</p>
      <p><small>Please message with parent’s permission.</small></p>
      <a class="btn" href="mailto:BrightByteTechHelp@gmail.com">Email BrightByte Tech Help</a>
    </section>
  </main>

  <footer class="container">
    <small>© BrightByte Tech Help • With parent supervision</small>
  </footer>
</body>
</html>
