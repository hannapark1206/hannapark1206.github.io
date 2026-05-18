---
title: Coursework
summary: Academic background and selected coursework.
type: landing

sections:
  - block: markdown
    content:
      title:
      text: |
        <div class="coursework-wrap">

        <div class="course-hero">
          <p class="course-kicker">Academic Background</p>
          <h1>Coursework</h1>
          <p class="course-lede">
            Selected coursework supporting my interests in robotics, controls, aerial systems, experimental hardware, and engineering analysis.
          </p>
        </div>

        <div class="edu-grid">

          <div class="edu-card">
            <p class="course-kicker">California Institute of Technology</p>
            <h2>B.S. Mechanical Engineering</h2>
            <p class="edu-subtitle">Expected 2027 · GPA 4.3/4.0</p>
            <p>
              Coursework focused on robotics, controls, mechanical design, experimental systems, and engineering analysis.
            </p>
          </div>

          <div class="edu-card cambridge-card">
            <p class="course-kicker">University of Cambridge · St John's College</p>
            <h2>Engineering Study Abroad</h2>
            <p class="edu-subtitle">Michaelmas Term · Sept–Dec 2025</p>
            <p>
              Study abroad term in Engineering, with coursework in aircraft aerodynamics and design, aircraft stability and control, nuclear reactor engineering, and management of technology.
            </p>
            <div class="highlight-chip">Cambridge engineering courses</div>
          </div>

        </div>

        ## Selected Coursework

        <div class="course-grid">

          <div class="course-card">
            <h3>Robotics, Controls, and Machine Learning</h3>
            <div class="chip-row">
              <span class="course-chip">Robotics</span>
              <span class="course-chip">Dynamics & Control</span>
              <span class="course-chip">Linear Systems & Control</span>
              <span class="course-chip">Machine Learning</span>
              <span class="course-chip">Data-Driven Modeling</span>
            </div>
          </div>

          <div class="course-card">
            <h3>Aeronautics and Fluids</h3>
            <div class="chip-row">
              <span class="course-chip">Fluid Mechanics</span>
              <span class="course-chip">Advanced Fluid Mechanics</span>
              <span class="course-chip">CFD</span>
              <span class="course-chip">Aircraft Aerodynamics & Design</span>
              <span class="course-chip">Aircraft Stability & Control</span>
            </div>
          </div>

          <div class="course-card">
            <h3>Design, Fabrication, and Experimental Systems</h3>
            <div class="chip-row">
              <span class="course-chip">Mechanical Prototyping</span>
              <span class="course-chip">Design & Fabrication</span>
              <span class="course-chip">Statics and Dynamics</span>
              <span class="course-chip">Thermodynamics</span>
              <span class="course-chip">Transport</span>
              <span class="course-chip">Biomechanics</span>
            </div>
          </div>

          <div class="course-card">
            <h3>Mathematics and Computation</h3>
            <div class="chip-row">
              <span class="course-chip">Differential Equations</span>
              <span class="course-chip">Transform Methods</span>
              <span class="course-chip">Complex Analysis</span>
              <span class="course-chip">Linear Algebra</span>
              <span class="course-chip">Multivariable Calculus</span>
              <span class="course-chip">Data Structures</span>
            </div>
          </div>

          <div class="course-card cambridge-course-card">
            <h3>Cambridge Graduate Coursework</h3>
            <p class="course-note">
              Engineering study abroad coursework completed during Michaelmas Term.
            </p>
            <div class="chip-row">
              <span class="course-chip">Aircraft Aerodynamics & Design</span>
              <span class="course-chip">Aircraft Stability & Control</span>
              <span class="course-chip">Nuclear Reactor Engineering</span>
              <span class="course-chip">Management of Technology</span>
            </div>
          </div>

        </div>

        </div>

        <style>
        .coursework-wrap {
          width: min(1120px, calc(100vw - 3rem)) !important;
          max-width: none !important;
          margin-left: 50% !important;
          transform: translateX(-50%) !important;
        }

        .course-hero {
          margin-top: -1rem;
          margin-bottom: 2.3rem;
          max-width: 850px;
        }

        .course-kicker {
          font-size: 0.82rem;
          font-weight: 700;
          letter-spacing: 0.05em;
          text-transform: uppercase;
          color: #4f46e5;
          margin-bottom: 0.45rem;
        }

        .course-hero h1 {
          font-size: clamp(2rem, 4vw, 3.2rem);
          line-height: 1.1;
          margin: 0 0 0.8rem 0;
        }

        .course-lede {
          font-size: 1.12rem;
          line-height: 1.65;
          color: #4b5563;
          max-width: 760px;
        }

        .edu-grid {
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(310px, 1fr));
          gap: 1.2rem;
          margin-bottom: 2.6rem;
        }

        .edu-card,
        .course-card {
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          background: #ffffff;
          box-shadow: 0 8px 24px rgba(0,0,0,0.05);
          padding: 1.25rem 1.35rem;
        }

        .cambridge-card,
        .cambridge-course-card {
          border-color: #c7d2fe;
          background: linear-gradient(180deg, #ffffff 0%, #f8f9ff 100%);
        }

        .edu-card h2,
        .course-card h3 {
          margin-top: 0;
          margin-bottom: 0.55rem;
          line-height: 1.25;
        }

        .edu-subtitle {
          color: #4b5563;
          font-weight: 600;
          margin-bottom: 0.8rem;
        }

        .highlight-chip {
          display: inline-flex;
          align-items: center;
          border: 1px solid #c7d2fe;
          background: #eef2ff;
          color: #3730a3;
          border-radius: 12px;
          padding: 0.42rem 0.72rem;
          font-size: 0.86rem;
          font-weight: 700;
          margin-top: 0.6rem;
        }

        .course-grid {
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(310px, 1fr));
          gap: 1.2rem;
          margin-top: 1.2rem;
          margin-bottom: 2.5rem;
        }

        .course-note {
          color: #4b5563;
          line-height: 1.55;
          margin-bottom: 0.9rem;
        }

        .chip-row {
          display: flex;
          flex-wrap: wrap;
          gap: 0.55rem;
          margin-top: 0.8rem;
        }

        .course-chip {
          display: inline-flex;
          align-items: center;
          border: 1px solid #dbe3ff;
          background: #f5f7ff;
          color: #27324a;
          border-radius: 12px;
          padding: 0.42rem 0.72rem;
          font-size: 0.88rem;
          font-weight: 600;
          line-height: 1.2;
        }
        </style>
    design:
      columns: '1'
---
