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
    .section-divider{
      border-top: 2px solid #FF00FF;
      padding-top: 0.75rem;
      margin-top: 2rem;
      }
  
    .body-item {
      display: grid;
      grid-template-columns: 1fr 1.2fr;
      gap: 2rem;
      align-items: center;
      padding: 2rem 0;
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
    
    .body-text h3 {
      margin-top: 0;
      font-size: 1.25rem;
    }
    
    .body-text ul {
      padding-left: 1.2rem;
    }
    
    .body-text li {
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
  <div class="body-item">
    <div class="body-image">
      <img src="{{ '/assets/Images/OC7Project.png' | relative_url }}">
    </div>

    <div class="body-text">
      <h6>OC7 Phase Ib: Viscous drag calibration</h6>
      <ul>
        <li>Hydrodynamic drag</li>

      </ul>
    </div>

  </div>

</div>

