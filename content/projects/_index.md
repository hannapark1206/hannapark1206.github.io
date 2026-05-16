---
title: Projects
summary: Robotics, controls, experimental systems, and design projects.
date: 2026-05-16
type: page
---

<p class="projects-intro">
Selected research, class, and hardware projects in aerial robotics, controls, experimental systems, rapid prototyping, and instrumentation.
</p>

## Lab and Field Robotic Systems

<div class="project-grid">

<a class="project-card" href="/projects/multi-modal-air-ground-robot/">
  <div class="project-image">
    <img src="/projects/multi-modal-air-ground-robot/featured.jpg" alt="Multi-modal air-ground robot project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Robotics · Hardware · CFD</div>
    <h3>Multi-Modal Air–Ground Robot Platform</h3>
    <p>Aerial hardware integration, propulsion/avionics integration, thrust-biasing deflector design, CFD checks, and bench testing.</p>
  </div>
</a>

<a class="project-card" href="/projects/fixed-wing-aerial-robot-sensing/">
  <div class="project-image">
    <img src="/projects/fixed-wing-aerial-robot-sensing/featured.jpg" alt="Fixed-wing aerial robot sensing project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Aerial Robotics · Controls · Sensing</div>
    <h3>Fixed-Wing Aerial Robot Sensing and Flight-Control Integration</h3>
    <p>Flight-control integration, ROS/MAVLink data workflows, five-hole Pitot probe hardware, and wind-tunnel calibration.</p>
  </div>
</a>

<a class="project-card" href="/projects/compact-water-tunnel-flow-facility/">
  <div class="project-image">
    <img src="/projects/compact-water-tunnel-flow-facility/featured.jpg" alt="Compact water tunnel flow facility project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Experimental Fluids · Hardware · Control</div>
    <h3>Compact Water-Tunnel Flow Facility</h3>
    <p>Water-tunnel hardware, turbine-array fixtures, electronics, power configuration, Arduino/PWM control, and PIV/dye-flow validation.</p>
  </div>
</a>

<a class="project-card" href="/projects/firefighting-hardware-prototype/">
  <div class="project-image placeholder"></div>
  <div class="project-body">
    <div class="project-tag">Rapid Prototyping · Assembly · Field Systems</div>
    <h3>Firefighting Hardware Prototype</h3>
    <p>Rapid prototyping, mechanical assembly, hardware modification, and test-preparation support for a firefighting-related system.</p>
  </div>
</a>

</div>

## Instrumentation and Detector Systems

<div class="project-grid">

<a class="project-card" href="/projects/cryogenic-detector-instrumentation/">
  <div class="project-image">
    <img src="/projects/cryogenic-detector-instrumentation/featured.jpg" alt="Cryogenic detector instrumentation project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Cryogenics · Instrumentation · Python</div>
    <h3>Cryogenic Detector Instrumentation</h3>
    <p>KID detector modifications, phonon guides, CAD mounting, wire-bonded assembly, and Python resonance fitting.</p>
  </div>
</a>

</div>

## Class and Design Projects

<div class="project-grid">

<a class="project-card" href="/projects/transmission-gearbox/">
  <div class="project-image">
    <img src="/projects/transmission-gearbox/featured.jpg" alt="Transmission gearbox project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Class Project · Mechanical Design</div>
    <h3>ME14 Transmission Gearbox</h3>
    <p>Multi-stage gearbox design with MATLAB performance modeling, SolidWorks CAD, keyed shafts, bearings, machining, and design reviews.</p>
  </div>
</a>

<a class="project-card" href="/projects/vision-motion-control/">
  <div class="project-image">
    <img src="/projects/vision-motion-control/featured.jpg" alt="Vision and motion control project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Class Project · Vision · Controls</div>
    <h3>Real-Time Vision and Motion Control</h3>
    <p>Python/OpenCV target detection and HEBI actuator control for real-time pan–tilt tracking.</p>
  </div>
</a>

<a class="project-card" href="/projects/lunar-landing-shield/">
  <div class="project-image placeholder"></div>
  <div class="project-body">
    <div class="project-tag">Team Project · Aerospace Concept</div>
    <h3>PILLARS Lunar Landing Shield</h3>
    <p>NASA BIG Idea finalist concept for a plume-deployed inflatable landing shield to reduce lunar regolith disturbance during landing.</p>
  </div>
</a>

</div>

## Earlier Research and Applied Systems

<div class="project-grid">

<a class="project-card" href="/projects/visual-decision-data-analysis/">
  <div class="project-image placeholder"></div>
  <div class="project-body">
    <div class="project-tag">Early Research · Data Analysis</div>
    <h3>Visual Decision Data Analysis</h3>
    <p>Python and regression analysis for a visual search and choice project in the Rangel Neuroeconomics Lab.</p>
  </div>
</a>

<a class="project-card" href="/projects/packing-machine-product-design/">
  <div class="project-image placeholder"></div>
  <div class="project-body">
    <div class="project-tag">Industry · Hardware · Operations</div>
    <h3>Packing Machine and Product Design</h3>
    <p>Industrial packing machinery assembly, product sizing, packaging design, machine settings, and operations support.</p>
  </div>
</a>

</div>

<style>
.projects-intro {
  max-width: 850px;
  font-size: 1.05rem;
  line-height: 1.65;
  margin-top: -1.5rem;
  margin-bottom: 2.5rem;
  color: #4b5563;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(285px, 1fr));
  gap: 1.4rem;
  margin-top: 1.2rem;
  margin-bottom: 3rem;
}

.project-card {
  display: block;
  overflow: hidden;
  border: 1px solid #e5e7eb;
  border-radius: 20px;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(0,0,0,0.05);
  text-decoration: none !important;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 14px 34px rgba(0,0,0,0.09);
}

.project-image {
  width: 100%;
  aspect-ratio: 16 / 9;
  background: linear-gradient(135deg, #ede9fe, #fbcfe8);
  display: flex;
  align-items: center;
  justify-content: center;
}

.project-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.project-image.placeholder::after {
  content: "image coming soon";
  color: #ffffff;
  font-size: 0.95rem;
  letter-spacing: 0.04em;
}

.project-body {
  padding: 1.15rem 1.25rem 1.3rem;
}

.project-tag {
  display: inline-block;
  font-size: 0.76rem;
  font-weight: 600;
  color: #4f46e5;
  background: #eef2ff;
  border-radius: 999px;
  padding: 0.25rem 0.62rem;
  margin-bottom: 0.55rem;
}

.project-card h3 {
  font-size: 1.18rem;
  line-height: 1.25;
  margin: 0 0 0.55rem 0;
}

.project-card p {
  font-size: 0.93rem;
  line-height: 1.55;
  color: #4b5563;
  margin: 0;
}
</style>
