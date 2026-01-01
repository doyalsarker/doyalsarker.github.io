---
title: Research
layout: page
aside: false
---

<style>
.research-body {
  font-size: 1.00rem;   /* try 0.9rem if you want smaller */
  line-height: 0.5;
}

.research-gallery{
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 2.5rem 3.5rem;      /* row gap, column gap */
  margin-top: 1.5rem;
}

.research-tile{
  text-decoration: none;
  color: inherit;
  text-align: center;
}

.tile-title{
  color: #d14;             /* match your red/orange nav vibe */
  font-weight: 600;
  margin-bottom: 0.9rem;
}

.research-tile img{
  width: 400px;
  max-width: 100%;
  height: 220px;          /* keep uniform tile height */
  object-fit: contain;    /* ✅ no cropping */
  background: #fff;       /* optional: fill empty space */
  display: inline-block;
}

/* Responsive: 2 columns on tablets, 1 column on phones */
@media (max-width: 900px){
  .research-gallery{ grid-template-columns: repeat(2, 1fr); }
}
@media (max-width: 560px){
  .research-gallery{ grid-template-columns: 1fr; }
  .research-tile img{ width: 100%; height: auto; }
}

.section-divider{
  border-top: 2px solid #FF00FF;
  padding-top: 0.75rem;
  margin-top: 2rem;
}

</style>

<!-- Research Description-->
<div class="research-body">
  <p> My research focuses on the modeling, simulation, and validation of dynamical systems for sustainable energy applications. I have been developing an acausal modeling and simulation framework for rapid aero–hydro coupled dynamic analysis of floating offshore wind turbines (FOWTs). My current research emphasizes structural fatigue load reduction using semi-active tuned mass dampers (TMDs) and the impact of wind–wave misalignment on controller performance. </p>
</div>

<!-- Research Image Gallery-->
<div class="research-gallery">

  <a class="research-tile" href="https://ieeexplore.ieee.org/document/10678762">
    <div class="tile-title">FOWT Dynamics</div>
    <img src="{{ '/assets/Images/fowt.png' | relative_url }}" alt="FOWT Dynamics">
  </a>

  <a class="research-tile" href="https://ieeexplore.ieee.org/document/10678762">
    <div class="tile-title">Hydrodynamics Framework</div>
    <img src="{{ '/assets/Images/hydrodynamics.png' | relative_url }}" alt="Hydrodynamics Framework">
  </a>

  <a class="research-tile" href="https://www.sciencedirect.com/science/article/pii/S0029801825025259">
    <div class="tile-title">Parameter Optimization Workflow</div>
    <img src="{{ '/assets/Images/GAHydro.png' | relative_url }}" alt="Parameter Optimization Workflow">
  </a>

  <a class="research-tile" href="https://www.sciencedirect.com/science/article/pii/S0029801825025259">
    <div class="tile-title">Wave-Structure</div>
    <img src="{{ '/assets/Images/fixedcylinder.png' | relative_url }}" alt="Wave-Structure">
  </a>

</div>

<h6 class="section-divider">Publications</h6>
