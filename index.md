<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Enterprise architecture portfolio, experience, and selected projects.">
  <title>Afzaal Shabbir | Enterprise Architect</title>

  <style>
    :root {
      color-scheme: light;
      --ink: #172033;
      --muted: #596579;
      --paper: #f5f7fb;
      --card: #ffffff;
      --accent: #176b87;
      --accent-dark: #10536a;
      --line: #dce3ec;
      --max-width: 1080px;
    }

    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      background: var(--paper);
      color: var(--ink);
      font: 16px/1.65 system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        sans-serif;
    }

    a { color: var(--accent); }

    a:hover { color: var(--accent-dark); }

    .wrap {
      width: min(var(--max-width), calc(100% - 2rem));
      margin-inline: auto;
    }

    header {
      background: var(--card);
      border-bottom: 1px solid var(--line);
    }

    .topbar {
      min-height: 68px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 1rem;
    }

    .brand {
      color: var(--ink);
      font-weight: 750;
      text-decoration: none;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 1.1rem;
    }

    nav a {
      color: var(--muted);
      font-size: .94rem;
      text-decoration: none;
    }

    nav a:hover { color: var(--accent); }

    .hero {
      padding: 5rem 0 4rem;
      background:
        radial-gradient(ellipse at 90% 10%, #d8edf2 0, transparent 38%),
        var(--paper);
    }

    .eyebrow {
      margin: 0 0 .6rem;
      color: var(--accent);
      font-size: .82rem;
      font-weight: 750;
      letter-spacing: .12em;
      text-transform: uppercase;
    }

    h1, h2, h3 { line-height: 1.2; }

    h1 {
      max-width: 780px;
      margin: 0;
      font-size: clamp(2.4rem, 6vw, 4.5rem);
      letter-spacing: -.045em;
    }

    .intro {
      max-width: 720px;
      margin: 1.25rem 0 1.7rem;
      color: var(--muted);
      font-size: 1.15rem;
    }

    .actions {
      display: flex;
      flex-wrap: wrap;
      gap: .8rem;
    }

    .button {
      display: inline-block;
      padding: .7rem 1rem;
      border: 1px solid var(--accent);
      border-radius: 8px;
      background: var(--accent);
      color: #fff;
      font-weight: 650;
      text-decoration: none;
    }

    .button:hover {
      background: var(--accent-dark);
      color: #fff;
    }

    .button.secondary {
      background: transparent;
      color: var(--accent);
    }

    section { padding: 3.5rem 0; }

    section h2 {
      margin: 0 0 .6rem;
      font-size: clamp(1.7rem, 3vw, 2.3rem);
      letter-spacing: -.025em;
    }

    .section-lead {
      max-width: 720px;
      margin: 0 0 1.6rem;
      color: var(--muted);
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 1rem;
    }

    .card {
      padding: 1.3rem;
      border: 1px solid var(--line);
      border-radius: 12px;
      background: var(--card);
    }

    .card h3 { margin: 0 0 .55rem; }

    .card p {
      margin: 0;
      color: var(--muted);
    }

    .project-meta {
      margin-bottom: .55rem;
      color: var(--accent);
      font-size: .83rem;
      font-weight: 700;
      letter-spacing: .04em;
      text-transform: uppercase;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: .55rem;
      padding: 0;
      list-style: none;
    }

    .skills li {
      padding: .38rem .7rem;
      border: 1px solid var(--line);
      border-radius: 999px;
      background: var(--card);
      color: var(--muted);
      font-size: .9rem;
    }

    .timeline {
      display: grid;
      gap: 1rem;
    }

    .role {
      padding: 0 0 1rem 1.1rem;
      border-left: 2px solid var(--line);
    }

    .role h3 { margin: 0; }

    .role .date {
      margin: .25rem 0 .5rem;
      color: var(--accent);
      font-size: .9rem;
      font-weight: 650;
    }

    .role p {
      max-width: 760px;
      margin: 0;
      color: var(--muted);
    }

    .contact {
      padding: 2rem;
      border-radius: 14px;
      background: #e6f1f4;
    }

    footer {
      padding: 1.5rem 0;
      border-top: 1px solid var(--line);
      color: var(--muted);
      font-size: .9rem;
    }

    @media (max-width: 680px) {
      .topbar {
        align-items: flex-start;
        flex-direction: column;
        padding: 1rem 0;
      }

      nav { gap: .6rem 1rem; }

      .hero { padding: 3.5rem 0; }

      .grid { grid-template-columns: 1fr; }

      section { padding: 2.5rem 0; }
    }
  </style>
</head>

<body>
  <header>
    <div class="wrap topbar">
      <a class="brand" href="#home">Afzaal Shabbir</a>
      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#expertise">Expertise</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="wrap">
        <p class="eyebrow">Enterprise Architecture · Strategy · Delivery</p>
        <h1>Connecting business strategy to technology that works.</h1>
        <p class="intro">
          I’m Afzaal Shabbir, an enterprise architect who helps organizations
          simplify complex technology landscapes, make confident decisions,
          and deliver change that creates measurable business value.
        </p>
        <div class="actions">
          <a class="button" href="#projects">View selected work</a>
          <a class="button secondary" href="mailto:afzaal01shabbir@gmail.com">Contact me</a>
        </div>
      </div>
    </section>

    <section id="about">
      <div class="wrap">
        <h2>About</h2>
        <p class="section-lead">
          I work with business and technology leaders to turn strategic goals
          into practical roadmaps, resilient architectures, and well-governed
          delivery. My approach balances long-term direction with outcomes teams
          can deliver incrementally.
        </p>
      </div>
    </section>

    <section id="expertise">
      <div class="wrap">
        <h2>Areas of expertise</h2>
        <p class="section-lead">A selection of the capabilities I bring to architecture work.</p>
        <ul class="skills">
          <li>Business alignment with Enterprise Architecture Strategy</li>
          <li>Application portfolio strategy</li>
          <li>Cloud and platform architecture</li>
          <li>Data and integration architecture</li>
          <li>Architecture governance</li>
          <li>Technology roadmaps</li>
          <li>Target operating models</li>
          <li>Stakeholder facilitation</li>
          <li>Agile delivery</li>
        </ul>
      </div>
    </section>

    <section id="projects">
      <div class="wrap">
        <h2>Led ZTNA Implementation in Public Sector</h2>
        <p class="section-lead">
          Replace these examples with work you can share publicly. Avoid including
          confidential client or company information.
        </p>

        <div class="grid">
          <article class="card">
            <div class="project-meta">Cloud transformation · 2024</div>
            <h3>Cloud adoption roadmap</h3>
            <p>
              Created a phased roadmap for moving priority workloads to cloud.
              Defined target principles, migration waves, governance, and
              decision criteria for platform teams.
            </p>
          </article>

          <article class="card">
            <div class="project-meta">Application strategy · 2023</div>
            <h3>Application portfolio rationalization</h3>
            <p>
              Assessed application capabilities, duplication, risk, and lifecycle.
              Helped business and technology leaders prioritize modernization
              and retirement opportunities.
            </p>
          </article>

          <article class="card">
            <div class="project-meta">Data and integration · 2022</div>
            <h3>Enterprise integration blueprint</h3>
            <p>
              Developed reusable integration patterns and governance guidance
              to improve interoperability, reduce point-to-point connections,
              and support future digital services.
            </p>
          </article>

          <article class="card">
            <div class="project-meta">Architecture governance · 2021</div>
            <h3>Architecture decision framework</h3>
            <p>
              Introduced lightweight review practices, decision records, and
              reference architectures to help delivery teams make consistent
              decisions without slowing delivery.
            </p>
          </article>
        </div>
      </div>
    </section>

    <section id="experience">
      <div class="wrap">
        <h2>Experience</h2>
        <div class="timeline">
          <article class="role">
            <h3>Enterprise Architect · Example Organization</h3>
            <p class="date">2021–Present</p>
            <p>
              Set architecture direction across business and technology
              initiatives; partnered with executives, product teams, and
              engineering leaders on roadmaps and solution decisions.
            </p>
          </article>

          <article class="role">
            <h3>Solution Architect · Previous Organization</h3>
            <p class="date">2017–2021</p>
            <p>
              Designed solutions for digital and operational programs,
              translating requirements into secure, supportable architectures
              and delivery plans.
            </p>
          </article>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="wrap">
        <div class="contact">
          <h2>Let’s connect</h2>
          <p class="section-lead">
            I’m open to conversations about enterprise architecture, cyber security, technology
            strategy, and transformation opportunities.
          </p>
          <div class="actions">
            <a class="button" href="mailto:afzaal01shabbir@gmail.com">Email me</a>
            <a class="button secondary"
               href="https://www.linkedin.com/in/afzaal-shabbir-84991822/"
               target="_blank" rel="noopener noreferrer">LinkedIn</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="wrap">
      © <span id="year"></span> Afzaal Shabbir · Enterprise Architect
    </div>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
