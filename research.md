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

.img-box{
  height: 220px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #fff;
}

.tile-title{
  color: #d14;             /* match your red/orange nav vibe */
  font-weight: 600;
  margin-bottom: 0.9rem;
}

.img-box img{
  max-height: 100%;
  max-width: 100%;
  height: auto;
  width: auto;
  object-fit: contain;
}

/* Responsive: 2 columns on tablets, 1 column on phones */
@media (max-width: 900px){
  .research-gallery{ grid-template-columns: repeat(2, 1fr); }
}
@media (max-width: 560px){
  .research-gallery{ grid-template-columns: 1fr; }
  .research-tile img{ width: 100%; height: auto; }
}

</style>

<!-- Research Description-->
<div class="research-body">
  <p> My research focuses on the modeling, simulation, and validation of dynamical systems for sustainable energy applications. I have been developing an acausal modeling and simulation framework for rapid aero–hydro coupled dynamic analysis of floating offshore wind turbines (FOWTs). My current research emphasizes structural fatigue load reduction using semi-active tuned mass dampers (TMDs) and the impact of wind–wave misalignment on controller performance. </p>
</div>

<!-- Research Image Gallery-->
<div class="research-gallery">

  <a class="img-box" href="{{ '/projects/' | relative_url }}">
    <div class="tile-title">FOWT</div>
    <img src="{{ '/assets/Images/fowt.png' | relative_url }}" alt="FOWT">
  </a>

  <a class="img-box" href="{{ '/projects/' | relative_url }}">
    <div class="tile-title">Hydrodynamics Framework</div>
    <img src="{{ '/assets/Images/hydrodynamics.png' | relative_url }}" alt="FOWT">
  </a>

</div>
