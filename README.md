<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<meta name="description" content="Daniel Vu — Underwriter at Lloyd's of London, exploring AI in insurance."/>
<title>Daniel Vu — Underwriter, Lloyd's of London</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@400;500&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet"/>
<link rel="stylesheet" href="/css/style.css"/>
</head>
<body>
<div class="site">

  <nav>
    <span class="nav-name">D. Vu</span>
    <div class="nav-links">
      <a href="#projects">Projects</a>
      <a href="#uses">AI &amp; Work</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <section class="hero">
    <div class="hero-top">
      <div class="avatar">
        <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="40" cy="28" r="14" fill="#1a1a18"/>
          <ellipse cx="40" cy="62" rx="22" ry="14" fill="#1a1a18"/>
        </svg>
      </div>
      <div class="hero-meta">
        <h1>Daniel Vu</h1>
        <p class="role">Underwriter · Lloyd's of London</p>
      </div>
    </div>
    <p class="hero-bio">
      I specialise in complex risk assessment at Lloyd's, with a focus on
      <em>marine, property, and specialty lines.</em> Alongside my underwriting work,
      I'm exploring how AI tools can sharpen risk modelling, streamline submission triage,
      and surface insights buried in dense policy documents — without losing the human
      judgement that good underwriting demands.
    </p>
  </section>

  <section class="section" id="projects">
    <p class="section-label">Projects</p>
    <div class="projects">

      <div class="project-item">
        <div>
          <p class="project-title">Submission Triage Assistant</p>
          <p class="project-desc">An LLM-powered tool that reads inbound broker submissions and flags priority risks, coverage gaps, and suggested follow-up questions — cutting triage time from hours to minutes.</p>
        </div>
        <span class="project-tag">NLP · Claude API</span>
      </div>

      <div class="project-item">
        <div>
          <p class="project-title">Policy Document Summariser</p>
          <p class="project-desc">A lightweight tool that distils dense policy wordings and endorsements into structured summaries, highlighting key exclusions, sublimits, and conditions at a glance.</p>
        </div>
        <span class="project-tag">RAG · Document AI</span>
      </div>

      <div class="project-item">
        <div>
          <p class="project-title">Risk Benchmarking Dashboard</p>
          <p class="project-desc">A data visualisation prototype comparing exposure metrics across a book of specialty risks, helping identify pricing outliers and accumulation hotspots in real time.</p>
        </div>
        <span class="project-tag">Python · Dashboards</span>
      </div>

      <div class="project-item">
        <div>
          <p class="project-title">Wordings Clause Library</p>
          <p class="project-desc">An AI-searchable index of Lloyd's market clauses, allowing underwriters to find, compare, and adapt standard and bespoke wordings across lines of business.</p>
        </div>
        <span class="project-tag">Vector Search</span>
      </div>

    </div>
  </section>

  <section class="section" id="uses">
    <p class="section-label">AI in my workflow</p>
    <div class="uses-list">
      <div class="use-item">
        <span class="use-dot"></span>
        <div class="use-text">
          <strong>Submission analysis</strong>
          <span>Using LLMs to extract structured risk data from unstructured broker submissions, COPE data, and underwriting questionnaires.</span>
        </div>
      </div>
      <div class="use-item">
        <span class="use-dot"></span>
        <div class="use-text">
          <strong>Regulatory &amp; wordings research</strong>
          <span>Querying Lloyd's market bulletins, TSB guidance, and policy wordings with semantic search rather than keyword hunts.</span>
        </div>
      </div>
      <div class="use-item">
        <span class="use-dot"></span>
        <div class="use-text">
          <strong>Catastrophe &amp; exposure modelling</strong>
          <span>Exploring AI-augmented approaches to interpreting cat model outputs and communicating probable maximum loss scenarios clearly.</span>
        </div>
      </div>
      <div class="use-item">
        <span class="use-dot"></span>
        <div class="use-text">
          <strong>Peer learning &amp; writing</strong>
          <span>Drafting internal notes, thought pieces, and exploring ideas around responsible AI adoption in the Lloyd's market.</span>
        </div>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <p class="section-label">Get in touch</p>
    <div class="contact-form" id="contact-form">
      <div class="field-row">
        <div class="field">
          <label for="f-name">Name</label>
          <input type="text" id="f-name" name="name" placeholder="Your name" required/>
        </div>
        <div class="field">
          <label for="f-company">Company</label>
          <input type="text" id="f-company" name="company" placeholder="Lloyd's, broker, etc."/>
        </div>
      </div>
      <div class="field">
        <label for="f-email">Email</label>
        <input type="email" id="f-email" name="email" placeholder="you@example.com" required/>
      </div>
      <div class="field">
        <label for="f-subject">Subject</label>
        <select id="f-subject" name="subject">
          <option value="">Select a topic…</option>
          <option>AI in underwriting — collaboration</option>
          <option>Project feedback or ideas</option>
          <option>Speaking or writing</option>
          <option>General enquiry</option>
        </select>
      </div>
      <div class="field">
        <label for="f-msg">Message</label>
        <textarea id="f-msg" name="message" placeholder="What's on your mind?" required></textarea>
      </div>
      <div class="form-footer">
        <span class="form-note" id="form-status">Replies within 2–3 business days.</span>
        <button class="btn-send" id="btn-send" type="button" onclick="submitForm()">Send message →</button>
      </div>
    </div>
    <p class="success-msg" id="success-msg">Thanks — message received. I'll be in touch shortly.</p>
  </section>

  <footer>
    <p>© 2026 Daniel Vu</p>
    <div class="footer-links">
      <a href="#">LinkedIn</a>
      <a href="https://github.com/danieldatvu" target="_blank" rel="noopener">GitHub</a>
      <a href="mailto:daniel@example.com">Email</a>
    </div>
  </footer>

</div>
<script src="/js/main.js"></script>
</body>
</html>
