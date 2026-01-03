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
       width: 800px;
       max-width: 100%;
       height: 220px;          /* keep uniform tile height */
       object-fit: contain;    /* ✅ no cropping */
       background: #fff;       /* optional: fill empty space */
       display: inline-block;
    }

    
    .caption {
      font-size: 0.85rem;
      text-align: center;
      margin-top: 0.1rem;
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
      <div class="caption">Image source <a href="https://iopscience.iop.org/article/10.1088/1742-6596/2626/1/012067" target="_blank"> here </a></div>
    </div>

    <div class="body-text">
      <h6>Semi-submersible hull control using TMD</h6>
      <ul>
        <li>Participated in the FOCAL Campaign II study on semi-submersible hull control with TMD</li>
        <li>Validated CRAFTS simulations against experimental data, achieving close agreement in tower-bending response and identifying overprediction in pitch-motion damping for future model refinement.</li>
        <li>Demonstrated a fast and plug-and-play integration of controller e.g., tuned mass damper (TMD) with main dynamical system, without relying on model reduction or explicit equation derivation</li>
      </ul>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="body-item" class="section-divider">
    <div class="body-image">
      <img src="{{ '/assets/Images/FEAProject.png' | relative_url }}">
    </div>

    <div class="body-text">
      <h6>FEM of wind turbine's tower</h6>
      <ul>
        <li>Conducted finite element modeling (FEM) and vibration analysis of land-based and floating wind turbine towers using ABAQUS</li>
        <li>Performed frequency analysis using different element formulations (B31, S4, S8R) for a land-based wind turbine; the B31 beam element showed the closest agreement with analytical solutions, outperforming both   shell (S4, S8R) elements</li>
        <li>Observed a reduction in the tower’s natural frequencies in the floating configuration compared to the land-based turbine</li>
      </ul>
    </div>
  </div>

  <!-- Project 4 -->
  <div class="body-item" class="section-divider">
    <div class="body-image">
      <img src="{{ '/assets/Images/CFDProject2.png' | relative_url }}">
    </div>

    <div class="body-text">
      <h6>CFD analysis in steady flow using STAR-CCM+</h6>
      <ul>
        <li>Conducted a computational fluid dynamics (CFD) study for a fixed, partially submerged horizontal cylinder in 2D steady flow using STAR-CCM+.</li>
        <li>A volume of fluid (VOF) method was applied to capture the interface between two incompressible fluids: air and water</li>
        <li>Mesh sensitivity study revealed that results are highly dependent on the grid size, however, with the finer grid resolution, the results were approaches to the asymptotic convergence region</li>
        <li>Drag coefficients for various velocities were found in well agreement with the experimental results, except for the critical Reynolds number</li>
      </ul>
    </div>
  </div>

</div>

