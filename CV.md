---
title: Curriculum Vitae (CV)
layout: page
aside: false
---


<style>
/* CV two-column layout (sidebar + content) */
.cv-grid{
  display: grid;
  grid-template-columns: 220px 1fr;
  gap: 2rem;
  align-items: start;
}
.cv-sidebar{
  position: sticky;
  top: 1.25rem;
  padding-right: 1rem;
  border-right: 1px solid rgba(0,0,0,0.15);
}
.cv-sidebar h2{
  margin-top: 0;
}
.cv-sidebar ul{
  margin: 0.5rem 0 0;
  padding-left: 1.1rem;
}
.cv-content h2:first-of-type{
  margin-top: 0;
}

/* Mobile: stack */
@media (max-width: 900px){
  .cv-grid{ grid-template-columns: 1fr; }
  .cv-sidebar{
    position: static;
    border-right: none;
    padding-right: 0;
    border-bottom: 1px solid rgba(0,0,0,0.15);
    padding-bottom: 1rem;
    margin-bottom: 1rem;
  }
}
</style>

<div class="cv-grid">

  <aside class="cv-sidebar">
    <a class="button" href="{{ '/assets/Files/CV_DoyalSarker.pdf' | relative_url }}" download>
      Download CV
    </a>

## Sections
- [Education](#education)
- [Experience](#experience)
- [Publications](#publications)
- [Skills](#skills)
  </aside>

  <main class="cv-content">

## Education

### University of Central Florida — PhD (Aug 2021 – Present)
- Location: Orlando, Florida, USA  
- Research: Multi-physics modeling, Dynamics & Control, Offshore Hydrodynamics, Ocean Wave modeling, Fluid-structure interaction  

