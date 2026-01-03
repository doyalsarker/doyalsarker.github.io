---
title: Projects
layout: page
aside: false
---

<style>
  
    .body-section {
      max-width: 1100px;
      margin: 0 auto;
    }
  
    .section-divider {
      border-top: 1px solid #FF00FF;
      padding-top: 0.75rem;
      margin-top: 2rem;
    }
  
    .body-item {
      display: grid;
      grid-template-columns: 1fr 1.2fr;
      gap: 2rem;
      align-items: center;
      padding: 1.0rem 0;
    }
  
    .body-image {
      text-align: center;
      margin-bottom: 1.5rem;
    }
    .body-image img {
       width: 400px;
       max-width: 100%;
       height: 220px;          /* keep uniform tile height */
       object-fit: contain;    /* ✅ no cropping */
       background: #fff;       /* optional: fill empty space */
       display: inline-block;
    }

    
    .caption {
      font-size: 0.85rem;
      text-align: center;
      margin-top: 0.5rem;
      color: #555;
    }
    
    .body-text{
      margin-top: 0;
      font-size: 1.0rem;
    }
    
    .body-text ul {
      padding-left: 1.2rem;
    }
    
    .body-text li {
      line-height: 1.25rem;
      margin-bottom: 0.5rem;
    }
    
    hr {
      border: none;
      border-top: 1px solid #ccc;
      margin: 1.5rem 0;
    }
    
    /* Responsive (mobile) */
    @media (max-width: 768px) {
      .research-item {
        grid-template-columns: 1fr;
      }
    }

</style>


<div class="body-section">

  <!-- Project 1 -->
  <div class="body-item" class="section-divider">
    <div class="body-image">
      <img src="{{ '/assets/Images/OC7Project.png' | relative_url }}">
    </div>

    <div class="body-text">
      <h6>Damping calibration for offshore platforms</h6>
      <ul>
        <li>Investigated sea-state-dependent hydrodynamic damping coefficients for offshore platform in the IEA OC7 Phase Ib collaboration</li>
        <li>Developed a regression-based model for a priori coefficient selection across untested sea states</li>
        <li>Validated results using in-house code (CRAFTS) maintaining ±15% modeling accuracy, and contributed to a joint publication</li>
      </ul>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="body-item" class="section-divider">
    <div class="body-image">
      <img src="{{ '/assets/Images/FC2Project.png' | relative_url }}">
    </div>

    <div class="body-text">
      <h6>Semi-submersible hull control using TMD</h6>
      <ul>
        <li>Participated in the FOCAL Campaign II study on semi-submersible hull control with TMD</li>
        <li>Validated CRAFTS simulations against experimental data, achieving close agreement in tower-bending response and identifying overprediction in pitch-motion damping for future model refinement.</li>
        <li>Demonstrated a fast and plug-and-play integration of controller e.g., tined mass damper (TMD) with main dynamical system, without relying on model reduction or explicit equation derivation</li>
      </ul>
    </div>
  </div>

</div>

