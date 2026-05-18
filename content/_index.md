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
        Excited about robotic hardware systems, especially aerial and multi-modal platforms, through flight-control integration, mechanical prototyping, sensing, and experimental testing.
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
        /* overall homepage hero spacing */
        .resume-biography,
        .homepage-hero {
          padding-top: 2rem !important;
          padding-bottom: 2.5rem !important;
          margin-top: 0 !important;
          margin-bottom: 0 !important;
        }

        .hero,
        .hero-body,
        section:first-of-type {
          min-height: auto !important;
          height: auto !important;
          padding-top: 1.5rem !important;
          padding-bottom: 1.5rem !important;
        }

        /* main profile section width */
        .resume-biography .container,
        .homepage-hero .container {
          max-width: 1160px !important;
          margin-left: auto !important;
          margin-right: auto !important;
        }

        /* center the two columns vertically */
        .resume-biography .row,
        .homepage-hero .row {
          display: flex !important;
          align-items: center !important;
          justify-content: center !important;
          gap: 3rem !important;
          padding-top: 0 !important;
          padding-bottom: 0 !important;
        }

        /* move the photo/profile side slightly down */
        .resume-biography .col-lg-4,
        .homepage-hero .col-lg-4 {
          transform: translateY(1.4rem) !important;
        }

        /* keep right summary vertically centered */
        .resume-biography .col-lg-8,
        .homepage-hero .col-lg-8 {
          display: flex !important;
          flex-direction: column !important;
          justify-content: center !important;
          align-items: flex-start !important;
          min-height: 430px !important;
          padding-top: 0 !important;
          padding-bottom: 0 !important;
        }

        /* center summary text block within right side */
        .resume-biography .biography,
        .resume-biography .bio-text,
        .resume-biography .section-subheading,
        .resume-biography .article-style,
        .homepage-hero .biography,
        .homepage-hero .bio-text,
        .homepage-hero .section-subheading,
        .homepage-hero .article-style {
          max-width: 640px !important;
          margin-left: auto !important;
          margin-right: auto !important;
        }

        /* reduce weird side padding */
        .resume-biography .col-12,
        .resume-biography .col-lg-4,
        .resume-biography .col-lg-8,
        .homepage-hero .col-12,
        .homepage-hero .col-lg-4,
        .homepage-hero .col-lg-8 {
          padding-left: 1.25rem !important;
          padding-right: 1.25rem !important;
        }

        /* homepage sections below hero */
        .home-section,
        section.home-section {
          padding-top: 1.25rem !important;
          padding-bottom: 1.25rem !important;
          margin-top: 0 !important;
          margin-bottom: 0 !important;
        }

        .home-wrap {
          width: min(1120px, calc(100vw - 4rem)) !important;
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

        @media (max-width: 900px) {
          .resume-biography .row,
          .homepage-hero .row {
            flex-direction: column !important;
            gap: 1.5rem !important;
          }

          .resume-biography .col-lg-4,
          .homepage-hero .col-lg-4 {
            transform: none !important;
          }

          .resume-biography .col-lg-8,
          .homepage-hero .col-lg-8 {
            min-height: auto !important;
            align-items: center !important;
            text-align: center !important;
          }

          .home-wrap {
            width: min(100%, calc(100vw - 2rem)) !important;
          }
        }
        </style>
    design:
      columns: '1'
---
