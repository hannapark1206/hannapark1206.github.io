---
title:
summary:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |
        I work on robotic hardware systems, especially aerial and multi-modal platforms, through flight-control integration, mechanical prototyping, sensing, and experimental testing.
      button:
        text: Download CV
        url: uploads/resume.pdf
        icon: hero/arrow-down-tray
    design:
      css_class: homepage-hero

  - block: markdown
    content:
      title:
      text: |
        <div class="home-wrap">

        ## Awards

        <div class="home-card-grid">

          <div class="home-card">
            <p class="home-kicker">Caltech EAS · 2026</p>
            <h3>Henry Ford II Scholar Award</h3>
            <p>Awarded to engineering students with the strongest academic record at the end of their third year.</p>
          </div>

          <div class="home-card">
            <p class="home-kicker">Caltech · 2026</p>
            <h3>Jack E. Froehlich Memorial Award Nominee</h3>
            <p>Nominated from the top 5% GPA group, with selection based on academics and research.</p>
          </div>

          <div class="home-card">
            <p class="home-kicker">NASA BIG Idea Challenge · 2024</p>
            <h3>NASA BIG Idea Challenge Finalist</h3>
            <p>Contributed to a finalist proposal awarded $150,000 for inflatable lunar landing shield development.</p>
          </div>

        </div>

        ## Research Focus

        <div class="home-card wide">
          <p>
            I am a mechanical engineering student at Caltech interested in robotics and controls, especially aerial and multi-modal robot platforms.
          </p>
          <p>
            My work includes flight-control integration, embedded sensing, robot prototyping, aerodynamic testing, and experimental validation.
          </p>
        </div>

        ## Featured Projects

        <div class="home-card-grid two">

          <a class="home-card home-link-card" href="/projects/multi-modal-air-robot/">
            <p class="home-kicker">Senior Thesis · Robotics</p>
            <h3>Multi-Modal Air–Ground Robot Platform</h3>
            <p>Multi-modal robot prototyping, propulsion integration, deflector design, and bench testing.</p>
          </a>

          <a class="home-card home-link-card" href="/projects/fixed-wing-aerial-robot-sensing/">
            <p class="home-kicker">Aerial Robotics · Sensing</p>
            <h3>Flight-Ready Sensing for Fixed-Wing Aerial Robots</h3>
            <p>Five-hole Pitot probe hardware, embedded sensing, ROS/MAVLink workflows, and wind-tunnel calibration.</p>
          </a>

        </div>

        </div>

        <style>
        /* reduce huge blank homepage spacing */
        .home-section,
        section.home-section,
        .resume-biography {
          padding-top: 1rem !important;
          padding-bottom: 1rem !important;
          margin-top: 0 !important;
          margin-bottom: 0 !important;
        }

        .hero,
        .hero-body,
        section:first-of-type {
          min-height: auto !important;
          height: auto !important;
          padding-top: 1rem !important;
          padding-bottom: 1rem !important;
        }

        /* make the biography block wider too */
        .homepage-hero .container,
        .resume-biography .container,
        .resume-biography .row {
          max-width: 1180px !important;
        }

        /* make markdown homepage sections wider */
        .home-wrap {
          width: min(1180px, calc(100vw - 3rem)) !important;
          max-width: none !important;
          margin-left: 50% !important;
          transform: translateX(-50%) !important;
        }

        .home-card-grid {
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
          gap: 1.2rem;
          margin-top: 1.2rem;
          margin-bottom: 2.6rem;
        }

        .home-card-grid.two {
          grid-template-columns: repeat(auto-fit, minmax(360px, 1fr));
        }

        .home-card {
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          background: #ffffff;
          box-shadow: 0 8px 24px rgba(0,0,0,0.05);
          padding: 1.25rem 1.35rem;
        }

        .home-card.wide {
          max-width: 900px;
          margin-top: 1.2rem;
          margin-bottom: 2.6rem;
        }

        .home-link-card {
          display: block;
          text-decoration: none !important;
          color: inherit;
          transition: transform 0.15s ease, box-shadow 0.15s ease;
        }

        .home-link-card:hover {
          transform: translateY(-3px);
          box-shadow: 0 14px 34px rgba(0,0,0,0.09);
        }

        .home-kicker {
          font-size: 0.78rem;
          font-weight: 700;
          letter-spacing: 0.05em;
          text-transform: uppercase;
          color: #4f46e5;
          margin-bottom: 0.45rem;
        }

        .home-card h3 {
          margin-top: 0;
          margin-bottom: 0.55rem;
          line-height: 1.25;
          font-size: 1.15rem;
        }

        .home-card p {
          color: #4b5563;
          line-height: 1.6;
          margin-bottom: 0;
        }

        .home-wrap h2 {
          margin-top: 1.4rem !important;
          margin-bottom: 0.8rem !important;
        }
        </style>
    design:
      columns: '1'
---
