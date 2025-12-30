---
title: Curriculum Vitae (CV)
aside: false
---
<a class="button" href="{{ '/assets/Files/CV_DoyalSarker.pdf' | relative_url }}" download>
  Download CV
</a>

<style>
/* Make CV layout use full available width */
.cv-grid{
  width: 100%;
  max-width: 100%;
  display: grid;
  grid-template-columns: 260px minmax(0, 1fr); /* wider sidebar, content fills remaining */
  gap: 2rem;
  align-items: start;
}

/* Prevent content from overflowing and causing weird spacing */
.cv-content{
  min-width: 0;
}

/* Sidebar styling */
.cv-sidebar{
  position: sticky;
  top: 1.25rem;
  padding-right: 1rem;
  border-right: 1px solid rgba(0,0,0,0.15);
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


    <h3>Index</h3>
    <ul>
      <li><a href="#education">Education</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#publications">Publications</a></li>
      <li><a href="#skills">Skills</a></li>
    </ul>
  </aside>

  <main class="cv-content">

<h3 id="education">Education</h3>

<h4>University of Central Florida — PhD (Aug 2021 – Present)</h4>
<ul>
  <li>Location: Orlando, Florida, USA</li>
  <li>Research: Multi-physics modeling, Dynamics & Control, Offshore Hydrodynamics, FSI</li>
</ul>

<h4>University of Central Florida — PhD (Aug 2021 – Present)</h4>
<ul>
  <li>Location: Orlando, Florida, USA</li>
  <li>Research: Multi-physics modeling, Dynamics & Control, Offshore Hydrodynamics, Ocean Wave modeling, Fluid-structure interaction</li>
</ul>

<h3 id="experience">Experience</h3>
<h3 id="publications">Publications</h3>
<h3 id="skills">Skills</h3>


  </main>
</div>
