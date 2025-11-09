<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shopfloor Automation — Staff Augmentation and Manufacturing Applications</title>
  <meta name="description" content="Shop Floor Automation helps manufacturers modernize operations: CNC connectivity, MES integrations, and on-demand staff augmentation for manufacturing IT projects." />
  <meta property="og:title" content="Shop Floor Automation — Manufacturing IT & Staff Augmentation" />
  <meta property="og:description" content="On-demand engineers and developers for your plant IT projects. CNC data, MES/ERP, IIoT, and automation—delivered." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://www.shopfloorautomation.net/" />
  <meta name="theme-color" content="#0a2540" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0b1220; /* deep slate */
      --card: #101a2b;
      --muted: #7b8aa5;
      --text: #e8edf5;
      --brand: #2eb67d; /* accent green */
      --brand-2: #4ea1ff; /* accent blue */
      --ring: rgba(78,161,255,.45);
      --shadow: rgba(0,0,0,.25);
      --maxw: 1200px;
      --radius: 18px;
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Apple Color Emoji", "Segoe UI Emoji";
      background: radial-gradient(1200px 600px at 80% -10%, rgba(78,161,255,.15), transparent 60%),
                  radial-gradient(1200px 600px at 0% 10%, rgba(46,182,125,.15), transparent 60%),
                  var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    a { color: var(--brand-2); text-decoration: none; }
    a:hover { text-decoration: underline; }

    /* Layout */
    .container { max-width: var(--maxw); margin: 0 auto; padding: 0 20px; }

    /* Header */
    header { position: sticky; top: 0; z-index: 20; backdrop-filter: blur(8px); background: rgba(11,18,32,.65); border-bottom: 1px solid rgba(255,255,255,.06); }
    .nav { display: flex; align-items: center; justify-content: space-between; padding: 14px 0; }
    .brand { display: flex; align-items: center; gap: 12px; font-weight: 800; letter-spacing: .2px; }
    .brand .logo { width: 36px; height: 36px; border-radius: 9px; background: linear-gradient(135deg, var(--brand), var(--brand-2)); box-shadow: 0 8px 20px var(--shadow); text-align: center; }
    .nav a { color: var(--text); opacity: .9; font-weight: 600; }
    .nav-links { display: flex; gap: 22px; align-items: center; }
    .cta { background: linear-gradient(135deg, var(--brand-2), var(--brand)); border: 0; color: white; font-weight: 700; padding: 10px 16px; border-radius: 999px; box-shadow: 0 8px 20px var(--shadow); cursor: pointer; }

    /* Hero */
    .hero { padding: 72px 0 40px; text-align: center; }
    .eyebrow { display: inline-block; padding: 6px 12px; border-radius: 999px; background: rgba(78,161,255,.12); color: #cfe1ff; font-weight: 600; letter-spacing: .3px; }
    h1 { font-size: clamp(32px, 4.8vw, 56px); line-height: 1.08; margin: 18px 0 12px; letter-spacing: -.02em; }
    .sub {  margin: 0 auto; color: var(--muted); font-size: clamp(16px, 2.2vw, 20px); }
    .hero-cta { margin-top: 40px; display: flex; gap: 14px; justify-content: center; flex-wrap: wrap; }

    /* Trust */
    .trust { opacity: .9; padding: 40px 0 10px; text-align: center; color: var(--muted); font-size: 14px; }
    .logos { display: grid; grid-template-columns: repeat(5, 1fr); gap: 18px; align-items: center; filter: saturate(.8) brightness(1.1); }
    .logos div { background: rgba(255,255,255,.04); border: 1px solid rgba(255,255,255,.06); height: 50px; border-radius: 12px; display: grid; place-items: center; color: #cdd8eb; font-weight: 600; }

    /* Sections */
    section { padding: 72px 0; }
    h2 { font-size: clamp(24px, 3.6vw, 36px); margin: 0 0 14px; letter-spacing: -.01em; }
    .kicker { color: var(--muted); max-width: 820px; }

    .grid { display: grid; gap: 20px; }
    .grid.cols-3 { grid-template-columns: repeat(3, 1fr); }
    .grid.cols-2 { grid-template-columns: repeat(2, 1fr); }
    @media (max-width: 900px) {
      .grid.cols-3, .grid.cols-2 { grid-template-columns: 1fr; }
      .logos { grid-template-columns: repeat(2, 1fr); }
    }

    .card { background: linear-gradient(180deg, var(--card), rgba(16,26,43,.7)); border: 1px solid rgba(255,255,255,.06); border-radius: var(--radius); padding: 20px; box-shadow: 0 10px 30px var(--shadow); }
    .card h3 { margin: 6px 0 8px; font-size: 20px; }
    .badge { display: inline-block; font-size: 12px; padding: 4px 8px; border-radius: 999px; background: rgba(46,182,125,.12); color: #b6f3d6; font-weight: 700; letter-spacing: .3px; }
    .list { margin: 10px 0 0 0; padding: 0; list-style: none; }
    .list li { padding-left: 20px; position: relative; margin: 8px 0; color: #d7e2f3; }
    .list li::before { content: "•"; position: absolute; left: 0; color: var(--brand-2); }

    /* Staff Augmentation highlight */
    .highlight { background: linear-gradient(180deg, rgba(78,161,255,.18), rgba(78,161,255,.06)); border: 1px solid rgba(78,161,255,.35); }

    /* CTA band */
    .cta-band { padding: 36px; border-radius: var(--radius); background: linear-gradient(90deg, rgba(46,182,125,.22), rgba(78,161,255,.22)); display: flex; align-items: center; justify-content: space-between; gap: 16px; flex-wrap: wrap; }
    .cta-band p { margin: 0; font-weight: 600; }

    /* Contact */
    form { display: grid; gap: 12px; }
    input, textarea, select { width: 100%; padding: 12px 14px; border-radius: 12px; border: 1px solid rgba(255,255,255,.12); background: rgba(255,255,255,.05); color: var(--text); outline: none; }
    input:focus, textarea:focus, select:focus { border-color: var(--ring); box-shadow: 0 0 0 6px rgba(78,161,255,.12); }
    .btn { background: linear-gradient(135deg, var(--brand), var(--brand-2)); border: 0; color: #fff; padding: 12px 16px; border-radius: 12px; font-weight: 700; cursor: pointer; }

    /* Footer */
    footer { padding: 60px 0; color: var(--muted); font-size: 14px; }
    .cols { display: grid; grid-template-columns: 2fr 1fr 1fr; gap: 20px; }
    @media (max-width: 900px) { .cols { grid-template-columns: 1fr; } }
    .small { font-size: 13px; color: var(--muted); }
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <nav class="nav-links" aria-label="Primary">
        <!-- <a href="staff-augmentation.html">Staff Augmentation</a>-->
        <a href="#staff-aug">Staff Augmentation</a>
        <a href="#services">Custom Applications</a>
        <a href="#contact" class="cta">Get a Quote</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero container">
        <div style="display:flex;justify-content:center;align-items:center;height:100px;width: 100px;">
          <img src="sfa-logo-2.png" alt="Shopfloor Automation logo" style="max-width:100%;height:auto;" />
          <p style="text-align: left; font-size:35pt;">Shopfloor Automation, Inc.</p>
        </div>
      <!-- <span class="eyebrow">Staff Augmentation • Manufacturing Applications • PLC Connectivity • IIoT Experience</span>-->
      <h1>Modernize your shop floor.&nbsp;&nbsp;Scale up fast with on‑demand experts.</h1>
      <p class="sub">We help manufacturers connect machines, capture production data, and integrate MES/ERP. When you need extra hands, our <strong>Staff Augmentation</strong> team embeds with yours—engineers and developers who know plant IT, PLC protocols, and industrial networks. If a fast start is what you are after, we may have just the solution in our <strong>Custom Applications</strong></p>
      <div class="hero-cta" style="margin-top:30px;">
        <a class="cta" href="#staff-aug">Staff Augmentation</a>
        <a class="cta" href="#services">Custom Applications</a>
        <a class="cta" href="#contact" style="background:rgba(255,255,255,.08); border:1px solid rgba(255,255,255,.15); color:#fff;">Talk to an Engineer</a>
      </div>
    </section>
    <br />
    <section id="staff-aug" class="container">
      <div class="card highlight">
        <h2>Staff Augmentation for Manufacturing IT</h2>
        <p class="kicker">Add vetted engineers and developers to your team—only when you need them. Our people understand plants, controls, and production realities.</p>
        <div class="grid cols-3" style="margin-top: 18px;">
          <div class="card" style="background:transparent; border-color: rgba(78,161,255,.25);">
            <h3>Roles we provide</h3>
            <ul class="list">
              <li>Manufacturing IT engineer (PLC, MTConnect)</li>
              <li>Integration developer (MES/ERP, APIs)</li>
              <li>Full‑stack web dev (dashboards & portals)</li>
              <li>Industrial network specialist (Ethernet/IP, VLAN)</li>
              <li>Data engineer (IIoT pipelines, historians)</li>
            </ul>
          </div>
          <div class="card" style="background:transparent; border-color: rgba(78,161,255,.25);">
            <h3>Engagement models</h3>
            <ul class="list">
              <li>Part‑time: 20–60 hrs/mo to cover spikes</li>
              <li>Full‑time: embedded for sprints or quarters</li>
              <li>Project‑based: fixed scope, fixed fee</li>
              <li>On‑site, remote, or hybrid</li>
            </ul>
          </div>
          <div class="card" style="background:transparent; border-color: rgba(78,161,255,.25);">
            <h3>Why it works</h3>
            <ul class="list">
              <li>Manufacturing‑native skillset (PLC, MES)</li>
              <li>Rapid onboarding, documented hand‑offs</li>
              <li>Flexible contracts, simple pricing</li>
              <li>U.S. time zones, clear SLAs</li>
            </ul>
          </div>
        </div>
        <div class="cta-band" style="margin-top: 20px;">
          <p>Need help next month—or Monday? Get resumes and rates within 24 hours.</p>
          <a class="btn" href="#contact">Request talent profiles</a>
        </div>
      </div>
    </section>
    <br />
    <!-- <section class="hero container">
      <span class="eyebrow">Staff Augmentation • Manufacturing Applications • PLC Connectivity • IIoT Experience</span>
      <h1>Applications ready to super charge your shop floor!</h1>
      <p class="sub">We can deliver prebuilt, tested custom applications to fit your needs. We leveraged our experience to codify manufacturing best practices in our custom applications.</p>
      <div class="hero-cta">
        <a class="cta" href="#staff-aug">Staff Augmentation</a>
        <a class="cta" href="#services">Custom Applications</a>
        <a class="cta" href="#contact" style="background:rgba(255,255,255,.08); border:1px solid rgba(255,255,255,.15); color:#fff;">Talk to an Engineer</a>
      </div>
    </section> -->
    <section id="services" class="container">
      <div class="card highlight" style="margin-top: 18px;">
        <h2>Process Manufacturing Tools</h2>
        <p class="kicker">Our engineers act on needs from across the industry. Our applications short cut your development time/costs and provide proven success for your business.</p>
        <div class="grid cols-3" style="margin-top: 18px;">
          <div class="card" style="background:transparent; border-color: rgba(78,161,255,.25);">
            <h3>Color Capture</h3>
            <ul class="list">
              <li>Capture all spectrophotometer readings (you own the data)</li>
              <li>Compare colors across multiple sites</li>
              <li>Share successful recipes</li>
              <li>Leverage your data in new ways</li>
            </ul>
          </div>
          <div class="card" style="background:transparent; border-color: rgba(78,161,255,.25);">
            <h3>Batch UI</h3>
            <ul class="list">
              <li>Best in class workflow</li>
              <li>Accurate weigh up and data capture</li>
              <li>Easily integrated with your ERP system</li>
              <li>Save time and reduce errors</li>
              <li>Multi-platform, localized interface (your equipment, your culture)</li>
            </ul>
          </div>
          <div class="card" style="background:transparent; border-color: rgba(78,161,255,.25);">
            <h3>Your Application Here!</h3>
            <ul class="list">
              <li>Complete turn key solutions</li>
              <li>Structured specifications and process</li>
              <li>One price, no overruns (we quote, we deliver)</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <!-- <section id="case-studies" class="container">
      <h2>Recent outcomes</h2>
      <div class="grid cols-3" style="margin-top: 18px;">
        <article class="card">
          <h3>Aerospace — OEE up 18%</h3>
          <p>Connected 40 CNCs, standardized DNC, and implemented MTConnect. Built production dashboard and alerts.</p>
          <ul class="list">
            <li>Cycle/idle tracking + alarm analysis</li>
            <li>Scrap trending and operator notes</li>
          </ul>
        </article>
        <article class="card">
          <h3>Medical — faster changeovers</h3>
          <p>MES integration for part dispatch and tool offsets sync. Result: 12% quicker changeovers and fewer misloads.</p>
          <ul class="list">
            <li>Secure program release workflow</li>
            <li>Revision control & e‑signoffs</li>
          </ul>
        </article>
        <article class="card">
          <h3>Automotive — downtime cut 22%</h3>
          <p>Added PLC sensors and OPC UA gateway to catch micro‑stops, rolled up to downtime Pareto and automated RCA.</p>
          <ul class="list">
            <li>Shift‑level KPIs and SMS alerts</li>
            <li>Weekly CI reporting</li>
          </ul>
        </article>
      </div>
    </section> -->
    <section id="contact" class="container">
      <h2>Get a quote</h2>
      <p class="kicker">Tell us what you’re tackling—connectivity, MES, dashboards, or a team boost. We’ll reply with a short plan and pricing.</p>
      <div class="grid cols-2" style="margin-top: 18px;">
        <form id="quote-form" class="card" onsubmit="return submitForm(event)">
          <label>
            <span class="small">Name</span>
            <input required type="text" name="name" placeholder="Your name" />
          </label>
          <label>
            <span class="small">Company</span>
            <input type="text" name="company" placeholder="Your company" />
          </label>
          <label>
            <span class="small">Email</span>
            <input required type="email" name="email" placeholder="you@example.com" />
          </label>
          <label>
            <span class="small">What do you need?</span>
            <select name="interest" >
              <option>Staff Augmentation</option>
              <option>Machine Connectivity / DNC</option>
              <option>MES / ERP Integration</option>
              <option>IIoT & Data</option>
              <option>Other</option>
            </select>
          </label>
          <label>
            <span class="small">Details</span>
            <textarea name="details" rows="5" placeholder="What machines, systems, timelines, outcomes?"></textarea>
          </label>
          <button class="btn" type="submit">Send request</button>
          <p id="form-result" class="small" role="status" aria-live="polite" style="display:none; margin:0;"></p>
        </form>
        <div class="card">
          <h3>Prefer email or a call?</h3>
          <p>Reach us at <a href="mailto:sales@shopfloorautomation.net">sales@shopfloorautomation.net</a>. We’re in U.S. Central Time.</p>
          <p class="small">We can sign NDAs and align with supplier cybersecurity requirements.</p>
          <div class="cta-band" style="margin-top: 8px;">
            <p>Need an NDA first? We’ll send ours or sign yours.</p>
            <a class="btn" href="mailto:sales@shopfloorautomation.net?subject=NDA Request">Request NDA</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <div>
        <div class="brand">
          <div style="display:flex;justify-content:center;align-items:center;height:60px;width: 60px;">
            <img src="sfa-logo-2.png" alt="Shopfloor Automation logo" style="max-width:100%;height:auto;" />
          </div>
          <a href="#" aria-label="Shop Floor Automation home">Shopfloor Automation, Inc.</a>
        </div>
      </div>
      <!-- <div>
        <strong>Company</strong>
        <ul class="list">
          <li><a href="#services">Services</a></li>
          <li><a href="#staff-aug">Staff Augmentation</a></li>
          <li><a href="#case-studies">Case Studies</a></li>
        </ul>
      </div>
      <div>
        <strong>Legal</strong>
        <ul class="list">
          <li><a href="#">Terms</a></li>
          <li><a href="#">Privacy</a></li>
          <li><a href="#">Security</a></li>
        </ul>
      </div> -->
    </div>
  </footer>

  <script>
    // Lightweight JS: year + demo form handler
    document.getElementById('year').textContent = new Date().getFullYear();

    function submitForm(e) {
      e.preventDefault();
      const form = e.target;
      const data = Object.fromEntries(new FormData(form).entries());
      // TODO: Replace with your form endpoint (e.g., Formspree, Netlify Forms, custom API)
      // For now, just show a local success message.
      const out = document.getElementById('form-result');
      out.style.display = 'block';
      out.textContent = 'Thanks, ' + (data.name || 'there') + '! We\'ll reach out shortly.';
      form.reset();
      return false;
    }
  </script>
</body>
</html>
