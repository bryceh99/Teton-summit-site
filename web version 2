<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Teton Summit Excavation | Victor, Idaho</title>
  <meta name="description" content="Teton Summit Excavation — precision excavation, site prep, utilities, grading, and project management in Teton Valley and surrounding areas." />
  <style>
    :root{
      /* Brand palette (easy to tweak) */
      --bg: #f3f5f7;          /* light gray */
      --card: #ffffff;       /* white */
      --text: #0f172a;       /* slate/near-black */
      --muted: #475569;      /* slate */
      --line: #e2e8f0;       /* light border */
      --accent: #1d4ed8;     /* strong blue */
      --accent2:#2563eb;     /* hover blue */
      --shadow: 0 10px 30px rgba(2,6,23,.08);
      --radius: 18px;
      --max: 1120px;
    }

    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      background: radial-gradient(1200px 700px at 20% 0%, #ffffff 0%, var(--bg) 55%);
      color: var(--text);
      line-height:1.45;
    }
    a{color:inherit}
    .wrap{max-width:var(--max); margin:0 auto; padding:0 20px;}
    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      gap:.55rem;
      padding:12px 16px;
      border-radius:999px;
      border:1px solid transparent;
      font-weight:700;
      text-decoration:none;
      cursor:pointer;
      transition:.18s ease;
      user-select:none;
      white-space:nowrap;
    }
    .btn.primary{background:var(--accent); color:#fff;}
    .btn.primary:hover{background:var(--accent2);}
    .btn.ghost{background:transparent; border-color:var(--line); color:var(--text);}
    .btn.ghost:hover{border-color:#cbd5e1; transform:translateY(-1px);}
    .pill{
      display:inline-flex; align-items:center; gap:.5rem;
      padding:6px 10px;
      border-radius:999px;
      border:1px solid var(--line);
      background:rgba(255,255,255,.75);
      color:var(--muted);
      font-weight:600;
      font-size:13px;
    }

    /* Header */
    header{
      position:sticky; top:0; z-index:50;
      backdrop-filter:saturate(160%) blur(10px);
      background:rgba(243,245,247,.75);
      border-bottom:1px solid var(--line);
    }
    .topbar{
      display:flex; align-items:center; justify-content:space-between;
      padding:12px 0;
      gap:14px;
    }
    .brand{
      display:flex; align-items:center; gap:12px; min-width:220px;
      text-decoration:none;
    }
    .brand img{
      width:44px; height:44px; object-fit:contain;
      border-radius:12px;
      background:#fff;
      border:1px solid var(--line);
      padding:6px;
    }
    .brand .name{
      display:flex; flex-direction:column; line-height:1.1;
    }
    .brand .name strong{font-size:14px; letter-spacing:.2px;}
    .brand .name span{font-size:12px; color:var(--muted); font-weight:600;}

    nav{
      display:flex; align-items:center; gap:18px;
    }
    nav a{
      text-decoration:none;
      color:var(--muted);
      font-weight:700;
      font-size:13px;
      padding:8px 10px;
      border-radius:999px;
      transition:.18s ease;
    }
    nav a:hover{background:#ffffff; color:var(--text); border:1px solid var(--line);}
    .ctaRow{display:flex; align-items:center; gap:10px;}

    /* Mobile nav */
    .menuBtn{display:none;}
    @media (max-width: 880px){
      nav{display:none;}
      .menuBtn{display:inline-flex;}
    }
    .mobileNav{
      display:none;
      border-top:1px solid var(--line);
      padding:10px 0 14px;
    }
    .mobileNav a{
      display:block; padding:10px 12px; text-decoration:none;
      border-radius:12px; color:var(--muted); font-weight:800;
    }
    .mobileNav a:hover{background:#fff; border:1px solid var(--line); color:var(--text);}
    .mobileNav .ctaRow{padding:10px 12px;}

    /* Hero */
    .hero{
      padding:44px 0 26px;
    }
    .heroGrid{
      display:grid; grid-template-columns: 1.15fr .85fr;
      gap:18px;
      align-items:stretch;
    }
    @media (max-width: 980px){
      .heroGrid{grid-template-columns:1fr; }
    }
    .heroCard{
      background:linear-gradient(180deg,#ffffff 0%, rgba(255,255,255,.85) 100%);
      border:1px solid var(--line);
      border-radius:var(--radius);
      box-shadow: var(--shadow);
      padding:26px;
      position:relative;
      overflow:hidden;
    }
    .heroCard:before{
      content:"";
      position:absolute; inset:-40px -40px auto auto;
      width:220px; height:220px;
      background:radial-gradient(circle at 30% 30%, rgba(29,78,216,.18), transparent 60%);
      transform:rotate(12deg);
    }
    h1{
      margin:10px 0 10px;
      font-size:44px;
      line-height:1.05;
      letter-spacing:-.6px;
    }
    @media (max-width:520px){
      h1{font-size:36px;}
    }
    .sub{
      margin:0 0 18px;
      color:var(--muted);
      font-size:16px;
      font-weight:600;
      max-width:58ch;
    }
    .heroActions{
      display:flex; gap:10px; flex-wrap:wrap;
      margin:10px 0 4px;
    }
    .trustRow{
      display:flex; gap:10px; flex-wrap:wrap;
      margin-top:16px;
      color:var(--muted);
      font-weight:700;
      font-size:13px;
    }
    .trustRow .dot{
      width:6px; height:6px; border-radius:999px; background:var(--accent);
      display:inline-block; margin:0 8px;
    }

    .logoPanel{
      background:linear-gradient(180deg, rgba(29,78,216,.08), rgba(255,255,255,.85));
      border:1px solid var(--line);
      border-radius:var(--radius);
      padding:22px;
      box-shadow: var(--shadow);
      display:flex; flex-direction:column; gap:14px;
    }
    .logoBig{
      background:#fff;
      border:1px dashed #cbd5e1;
      border-radius:16px;
      padding:18px;
      display:flex;
      align-items:center; justify-content:center;
      min-height:220px;
    }
    .logoBig img{
      max-width:100%;
      height:auto;
      display:block;
    }
    .quickFacts{
      display:grid; gap:10px;
    }
    .fact{
      background:#fff;
      border:1px solid var(--line);
      border-radius:14px;
      padding:12px 14px;
      display:flex; justify-content:space-between; gap:12px;
      font-weight:800;
    }
    .fact span{color:var(--muted); font-weight:700;}

    /* Sections */
    section{padding:28px 0;}
    .sectionHead{
      display:flex; justify-content:space-between; align-items:flex-end; gap:14px;
      margin-bottom:14px;
    }
    h2{margin:0; font-size:26px; letter-spacing:-.2px;}
    .sectionHead p{margin:0; color:var(--muted); font-weight:600; max-width:60ch;}

    .grid3{
      display:grid; grid-template-columns: repeat(3, 1fr);
      gap:14px;
    }
    @media (max-width: 980px){ .grid3{grid-template-columns:1fr;} }

    .card{
      background:var(--card);
      border:1px solid var(--line);
      border-radius:var(--radius);
      box-shadow: var(--shadow);
      padding:18px;
    }
    .card h3{margin:0 0 8px; font-size:16px;}
    .card p{margin:0; color:var(--muted); font-weight:600;}
    .list{
      margin:10px 0 0; padding:0 0 0 18px;
      color:var(--muted);
      font-weight:650;
    }
    .list li{margin:6px 0;}

    /* Projects */
    .projectGrid{
      display:grid; grid-template-columns: repeat(3, 1fr);
      gap:14px;
    }
    @media (max-width: 980px){ .projectGrid{grid-template-columns:1fr;} }
    .project{
      border-radius:var(--radius);
      border:1px solid var(--line);
      background:linear-gradient(180deg,#fff 0%, rgba(255,255,255,.85) 100%);
      overflow:hidden;
      box-shadow: var(--shadow);
    }
    .project .ph{
      height:160px;
      background:
        linear-gradient(180deg, rgba(29,78,216,.12), rgba(15,23,42,.04)),
        repeating-linear-gradient(45deg, rgba(148,163,184,.16) 0 12px, rgba(148,163,184,.06) 12px 24px);
      border-bottom:1px solid var(--line);
    }
    .project .meta{padding:14px 16px;}
    .project .meta strong{display:block; margin-bottom:6px;}
    .project .meta span{color:var(--muted); font-weight:650; font-size:14px;}

    /* Contact */
    .contactGrid{
      display:grid; grid-template-columns: 1fr 1fr;
      gap:14px;
    }
    @media (max-width: 980px){ .contactGrid{grid-template-columns:1fr;} }

    label{display:block; font-weight:800; font-size:13px; margin:10px 0 6px;}
    input, textarea, select{
      width:100%;
      border:1px solid var(--line);
      border-radius:14px;
      padding:12px 12px;
      font:inherit;
      background:#fff;
      outline:none;
      transition:.15s ease;
    }
    input:focus, textarea:focus, select:focus{border-color:rgba(29,78,216,.55); box-shadow: 0 0 0 4px rgba(29,78,216,.12);}
    textarea{min-height:120px; resize:vertical;}

    footer{
      border-top:1px solid var(--line);
      padding:18px 0 26px;
      color:var(--muted);
      font-weight:650;
    }
    .footRow{
      display:flex; justify-content:space-between; align-items:center;
      gap:12px; flex-wrap:wrap;
    }
    .small{font-size:13px;}
  </style>
</head>

<body>
  <header>
    <div class="wrap">
      <div class="topbar">
        <a class="brand" href="#top" aria-label="Teton Summit Excavation home">
          <!-- Put your logo file in the same folder as index.html and name it logo.png -->
          <img src="logo.png" alt="Teton Summit Excavation logo" />
          <div class="name">
            <strong>Teton Summit Excavation</strong>
            <span>Victor, Idaho • Teton Valley</span>
          </div>
        </a>

        <nav aria-label="Primary navigation">
          <a href="#services">Services</a>
          <a href="#projects">Projects</a>
          <a href="#about">About</a>
          <a href="#contact">Contact</a>
        </nav>

        <div class="ctaRow">
          <a class="btn ghost" href="tel:3034831791">Call</a>
          <a class="btn primary" href="#contact">Get a Quote</a>
          <button class="btn ghost menuBtn" id="menuBtn" type="button" aria-expanded="false" aria-controls="mobileNav">Menu</button>
        </div>
      </div>

      <div class="mobileNav" id="mobileNav">
        <a href="#services">Services</a>
        <a href="#projects">Projects</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <div class="ctaRow">
          <a class="btn ghost" href="tel:3034831791">Call 303-483-1791</a>
          <a class="btn primary" href="#contact">Get a Quote</a>
        </div>
      </div>
    </div>
  </header>

  <main id="top">
    <!-- HERO -->
    <div class="wrap hero">
      <div class="heroGrid">
        <div class="heroCard">
          <div class="pill">Precision excavation • Clear communication • Quality work</div>
          <h1>Excavation done right — clean, efficient, and on schedule.</h1>
          <p class="sub">
            Teton Summit Excavation helps homeowners, builders, and developers in Victor / Driggs and the surrounding area
            with foundation digs, site prep, utilities, and final grading — with straightforward pricing and solid field communication.
          </p>

          <div class="heroActions">
            <a class="btn primary" href="#contact">Request a Quote</a>
            <a class="btn ghost" href="#services">View Services</a>
          </div>

          <div class="trustRow" aria-label="Trust highlights">
            <span>Owner-operator</span><span class="dot" aria-hidden="true"></span>
            <span>Professional results</span><span class="dot" aria-hidden="true"></span>
            <span>Local to Teton Valley</span>
          </div>
        </div>

        <aside class="logoPanel" aria-label="Brand panel">
          <div class="logoBig">
            <!-- Same logo as header -->
            <img src="logo.png" alt="Teton Summit Excavation logo large" />
          </div>
          <div class="quickFacts">
            <div class="fact"><span>Service Area</span> Victor • Driggs • Teton Valley</div>
            <div class="fact"><span>Phone</span> 303-483-1791</div>
            <div class="fact"><span>Email</span> Brycetetonsummit@gmail.com</div>
          </div>
        </aside>
      </div>
    </div>

    <!-- SERVICES -->
    <section id="services">
      <div class="wrap">
        <div class="sectionHead">
          <div>
            <h2>Services</h2>
            <p>Built around the work you actually need for residential and light commercial builds — done clean and professional.</p>
          </div>
        </div>

        <div class="grid3">
          <div class="card">
            <h3>Site Prep & Excavation</h3>
            <p>Foundation excavation and site prep with attention to grade, access, and efficiency.</p>
            <ul class="list">
              <li>Basement & crawl space excavation</li>
              <li>Footings / over-excavation / backfill</li>
              <li>Slab prep & import/export</li>
            </ul>
          </div>

          <div class="card">
            <h3>Utilities & Trenching</h3>
            <p>Trenching and coordination to keep the project moving and avoid surprises later.</p>
            <ul class="list">
              <li>Water / sewer / conduit trenches</li>
              <li>Utility connections & relocations</li>
              <li>Drainage solutions</li>
            </ul>
          </div>

          <div class="card">
            <h3>Grading & Finish Work</h3>
            <p>Final grading that looks right and performs — drainage, access, and clean finish.</p>
            <ul class="list">
              <li>Driveway prep</li>
              <li>Final grade & cleanup</li>
              <li>Material spreading & shaping</li>
            </ul>
          </div>
        </div>

        <div style="margin-top:14px" class="card">
          <h3>Project Management</h3>
          <p>
            If you want a single point of contact during the dirt phase, I can help coordinate schedule + subs,
            keep communication tight, and make sure the site is ready for the next trade.
          </p>
        </div>
      </div>
    </section>

    <!-- PROJECTS -->
    <section id="projects">
      <div class="wrap">
        <div class="sectionHead">
          <div>
            <h2>Recent work</h2>
            <p>Add your own project photos later — these are placeholder tiles for now.</p>
          </div>
        </div>

        <div class="projectGrid">
          <div class="project">
            <div class="ph" aria-hidden="true"></div>
            <div class="meta">
              <strong>Foundation & Site Prep</strong>
              <span>Excavation, haul off, and base prep</span>
            </div>
          </div>
          <div class="project">
            <div class="ph" aria-hidden="true"></div>
            <div class="meta">
              <strong>Utilities & Trenching</strong>
              <span>Water / sewer / conduit coordination</span>
            </div>
          </div>
          <div class="project">
            <div class="ph" aria-hidden="true"></div>
            <div class="meta">
              <strong>Final Grading</strong>
              <span>Drainage, shaping, and clean finish</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about">
      <div class="wrap">
        <div class="sectionHead">
          <div>
            <h2>About Teton Summit</h2>
            <p>Clear communication and quality work — that’s the whole point.</p>
          </div>
        </div>

        <div class="contactGrid">
          <div class="card">
            <h3>What you can expect</h3>
            <ul class="list">
              <li><strong>Good communication:</strong> updates when conditions change, not after.</li>
              <li><strong>Clean work:</strong> tidy site habits and respect for the property.</li>
              <li><strong>Reliable execution:</strong> efficient production without cutting corners.</li>
              <li><strong>Transparent pricing:</strong> clear scope and line items.</li>
            </ul>
          </div>

          <div class="card">
            <h3>Perfect fit for</h3>
            <ul class="list">
              <li>Custom home builders</li>
              <li>Homeowners building or remodeling</li>
              <li>Small developments / spec builds</li>
              <li>Time-sensitive schedules</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <div class="wrap">
        <div class="sectionHead">
          <div>
            <h2>Request a quote</h2>
            <p>Send a quick message with your address, timeline, and what you need. If you have plans, mention that too.</p>
          </div>
        </div>

        <div class="contactGrid">
          <div class="card">
            <h3>Contact</h3>
            <p style="margin-top:6px">
              <strong>Phone:</strong> <a href="tel:3034831791">303-483-1791</a><br/>
              <strong>Email:</strong> <a href="mailto:Brycetetonsummit@gmail.com">Brycetetonsummit@gmail.com</a><br/>
              <strong>Location:</strong> Victor, Idaho
            </p>
            <div style="margin-top:14px; display:flex; gap:10px; flex-wrap:wrap;">
              <a class="btn primary" href="tel:3034831791">Call Now</a>
              <a class="btn ghost" href="mailto:Brycetetonsummit@gmail.com?subject=Teton%20Summit%20Quote%20Request">Email</a>
            </div>
            <p class="small" style="margin-top:12px;">
              Prefer text? You can text the same number and I’ll respond as soon as I’m out of the machine.
            </p>
          </div>

          <div class="card">
            <h3>Quick form (opens your email)</h3>
            <form id="quoteForm">
              <label for="name">Name</label>
              <input id="name" name="name" autocomplete="name" required />

              <label for="phone">Phone</label>
              <input id="phone" name="phone" autocomplete="tel" />

              <label for="address">Job Address / Area</label>
              <input id="address" name="address" placeholder="Victor / Driggs / etc." required />

              <label for="service">Service Needed</label>
              <select id="service" name="service">
                <option>Site Prep & Excavation</option>
                <option>Utilities & Trenching</option>
                <option>Grading & Finish Work</option>
                <option>Driveway Prep</option>
                <option>Project Management</option>
                <option>Other</option>
              </select>

              <label for="details">Details</label>
              <textarea id="details" name="details" placeholder="Timeline, scope, soil conditions, access, and whether you have plans…"></textarea>

              <div style="margin-top:12px; display:flex; gap:10px; flex-wrap:wrap;">
                <button class="btn primary" type="submit">Send Request</button>
                <a class="btn ghost" href="mailto:Brycetetonsummit@gmail.com?subject=Teton%20Summit%20Quote%20Request">Email Instead</a>
              </div>

              <p class="small" style="margin-top:10px; color:var(--muted);">
                This form uses your email app (no website backend needed).
              </p>
            </form>
          </div>
        </div>
      </div>
    </section>

    <footer>
      <div class="wrap">
        <div class="footRow">
          <div class="small">© <span id="year"></span> Teton Summit Excavation • Victor, Idaho</div>
          <div class="small">Built for clarity • Blue/gray brand style • Fast + mobile friendly</div>
        </div>
      </div>
    </footer>
  </main>

  <script>
    // Mobile menu
    const btn = document.getElementById('menuBtn');
    const nav = document.getElementById('mobileNav');
    if (btn){
      btn.addEventListener('click', () => {
        const open = nav.style.display === 'block';
        nav.style.display = open ? 'none' : 'block';
        btn.setAttribute('aria-expanded', String(!open));
      });
    }

    // Footer year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Form -> mailto
    document.getElementById('quoteForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const phone = document.getElementById('phone').value.trim();
      const address = document.getElementById('address').value.trim();
      const service = document.getElementById('service').value;
      const details = document.getElementById('details').value.trim();

      const subject = encodeURIComponent(`Teton Summit Quote Request - ${service}`);
      const body = encodeURIComponent(
`Name: ${name}
Phone: ${phone}
Job Address/Area: ${address}
Service Needed: ${service}

Details:
${details}
`
      );

      window.location.href = `mailto:Brycetetonsummit@gmail.com?subject=${subject}&body=${body}`;
    });
  </script>
</body>
</html>
