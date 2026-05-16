---
title: Experience
summary: Research, engineering, teaching, and leadership experience.
date: 2026-05-16
type: landing

sections:
  - block: markdown
    content:
      title:
      text: |
        <div class="experience-wrap">

        <div class="experience-hero">
          <p class="experience-kicker">Background</p>
          <h1>Experience</h1>
          <p class="experience-lede">
            Research, engineering, teaching, and leadership roles focused on robotics, controls, hardware integration, experimental systems, and technical communication.
          </p>
        </div>

        ## Research and Engineering

        <div class="experience-grid">

          <div class="experience-card">
            <p class="experience-kicker">Summer 2026 · Hawthorne, CA</p>
            <h3>Falcon Propulsion Engineering Intern</h3>
            <p class="experience-org">SpaceX</p>
            <p>
              Incoming engineering intern on the Falcon Propulsion team.
            </p>
          </div>

          <div class="experience-card">
            <p class="experience-kicker">2023–Present · Pasadena, CA</p>
            <h3>Undergraduate Researcher</h3>
            <p class="experience-org">Gharib Group / CAST / GALCIT, Caltech</p>
            <p>
              Long-term undergraduate researcher across aerial robotics, experimental hardware, sensing, and rapid prototyping projects.
            </p>
            <a class="experience-link" href="/projects/">View related projects</a>
          </div>

          <div class="experience-card">
            <p class="experience-kicker">June 2024–September 2024 · Pasadena, CA</p>
            <h3>Summer Undergraduate Research Fellow</h3>
            <p class="experience-org">Golwala Group, Caltech</p>
            <p>
              Worked on cryogenic detector instrumentation, detector hardware, resonator analysis, and experimental hardware preparation.
            </p>
            <a class="experience-link" href="/projects/cryogenic-detector-instrumentation/">View project</a>
          </div>

          <div class="experience-card">
            <p class="experience-kicker">January 2019–Present</p>
            <h3>Assembly Machine Management and Product Design Lead</h3>
            <p class="experience-org">Wellatex Inc.</p>
            <p>
              Supported machine assembly, product sizing, packaging design, process improvement, customer-facing documentation, and operations.
            </p>
            <a class="experience-link" href="/projects/packing-machine-product-design/">View project</a>
          </div>

        </div>

        ## Teaching and Leadership

        <div class="experience-grid leadership-grid">

          <div class="experience-card">
            <p class="experience-kicker">January 2025–March 2025 · Caltech</p>
            <h3>Teaching Assistant, Biomechanics</h3>
            <p class="experience-org">Prof. Michael Dickinson</p>
            <p>
              Prepared and graded exams, held office hours, and supported student understanding of solid/fluid mechanics and materials.
            </p>
          </div>

          <div class="experience-card">
            <p class="experience-kicker">May 2024–Present · Caltech</p>
            <h3>Professional Development Lead</h3>
            <p class="experience-org">Caltech Admissions Ambassador Program</p>
            <p>
              Lead campus tours, serve as a student panelist, and answer prospective-student questions about curriculum, research, and student life.
            </p>
          </div>

          <div class="experience-card">
            <p class="experience-kicker">Fall 2023–Winter 2024 · Caltech</p>
            <h3>NASA BIG Idea Challenge Finalist Team Member</h3>
            <p class="experience-org">Caltech Air and Outer Space Club</p>
            <p>
              Contributed to a finalist aerospace systems proposal through team design, technical writing, and lunar dust-modeling work.
            </p>
            <a class="experience-link" href="/projects/lunar-landing-shield/">View project</a>
          </div>

          <div class="experience-card">
            <p class="experience-kicker">2011–Present</p>
            <h3>Cellist</h3>
            <p class="experience-org">Caltech Orchestra and Chamber Music</p>
            <p>
              Play cello in orchestra and chamber music, including piano trio and chamber ensembles.
            </p>
          </div>

        </div>

        </div>

        <style>
        .experience-wrap {
          width: min(1260px, calc(100vw - 5rem)) !important;
          max-width: none !important;
          margin-left: 50% !important;
          transform: translateX(-50%) !important;
        }

        .experience-hero {
          margin-top: -1rem;
          margin-bottom: 2.5rem;
          max-width: 850px;
        }

        .experience-kicker {
          font-size: 0.82rem;
          font-weight: 700;
          letter-spacing: 0.05em;
          text-transform: uppercase;
          color: #4f46e5;
          margin-bottom: 0.45rem;
        }

        .experience-hero h1 {
          font-size: clamp(2rem, 4vw, 3.2rem);
          line-height: 1.1;
          margin: 0 0 0.8rem 0;
        }

        .experience-lede {
          font-size: 1.12rem;
          line-height: 1.65;
          color: #4b5563;
          max-width: 760px;
        }

        .experience-grid {
          display: grid;
          grid-template-columns: repeat(4, minmax(0, 1fr));
          gap: 1.1rem;
          margin-top: 1.2rem;
          margin-bottom: 2.7rem;
        }

        .experience-card {
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          background: #ffffff;
          box-shadow: 0 8px 24px rgba(0,0,0,0.05);
          padding: 1.15rem 1.2rem;
        }

        .experience-card h3 {
          margin-top: 0;
          margin-bottom: 0.35rem;
          line-height: 1.25;
          font-size: 1.1rem;
        }

        .experience-org {
          color: #4b5563;
          font-weight: 650;
          margin-bottom: 0.75rem;
        }

        .experience-card p {
          line-height: 1.55;
          font-size: 0.94rem;
        }

        .experience-link {
          display: inline-flex;
          align-items: center;
          border: 1px solid #dbe3ff;
          background: #f5f7ff;
          color: #27324a;
          border-radius: 12px;
          padding: 0.45rem 0.75rem;
          font-size: 0.86rem;
          font-weight: 700;
          text-decoration: none !important;
          margin-top: 0.4rem;
        }

        @media (max-width: 1100px) {
          .experience-wrap {
            width: min(1000px, calc(100vw - 3rem)) !important;
          }

          .experience-grid {
            grid-template-columns: repeat(2, minmax(0, 1fr));
          }
        }

        @media (max-width: 700px) {
          .experience-wrap {
            width: min(100%, calc(100vw - 2rem)) !important;
          }

          .experience-grid {
            grid-template-columns: 1fr;
          }
        }
        </style>
    design:
      columns: '1'
---
