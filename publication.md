---
title: Publications
layout: page
aside: false
---
<style>
.section-body {
  font-size: 1.00rem;   /* try 0.9rem if you want smaller */
  line-height: 0.5;
}

.section-gallery{
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 2.5rem 3.5rem;      /* row gap, column gap */
  margin-top: 1.5rem;
}

.section-tile{
  text-decoration: none;
  color: inherit;
  text-align: center;
}

.tile-title{
  color: #d14;             /* match your red/orange nav vibe */
  font-weight: 600;
  margin-bottom: 0.9rem;
}

.section-tile img{
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
  .section-gallery{ grid-template-columns: 1fr; }
  .section-tile img{ width: 100%; height: auto; }
}

.section-divider{
  border-top: 2px solid #FF00FF;
  padding-top: 0.75rem;
  margin-top: 2rem;
}

.pub-drop{
  border: 1px solid rgba(0,0,0,0.15);
  border-radius: 10px;
  padding: 0.6rem 0.9rem;
  margin: 0.8rem 0;
  background: #fff;
}

.pub-drop summary{
  cursor: pointer;
  font-weight: 700;
  list-style: none;
}

.pub-drop summary::-webkit-details-marker{
  display: none;
}

.pub-drop summary:before{
  content: "▸ ";
}

.pub-drop[open] summary:before{
  content: "▾ ";
}

.pub-list{
  margin: 0.7rem 0 0.2rem 1.1rem;
  font-size: 0.85rem;
}

.pub-list li{
  line-height: 1.25;        /* controls line spacing */
  margin-bottom: 0.5rem;   /* controls gap between items */
}

</style>

<div class="section-body">
<p>
  For an updated list of publications, please visit my <a href="https://scholar.google.com/citations?user=-waJLfwAAAAJ&hl=en" target="_blank"> Google Scholar</a> and <a href="https://www.researchgate.net/profile/Doyal-Kumar-Sarker?ev=hdr_xprf" target="_blank"> ResearchGate</a> profiles.
</p>
</div>

<details class="pub-drop">
  <summary>Journal Articles</summary>
  <ul class="pub-list">
    <li><b>Sarker, D.</b>, Ngo, T., & Das, T. (2025). Enhancement of hydrodynamics modeling for floating offshore wind turbines using multi-objective genetic algorithm. <em>Ocean Engineering</em>, 342, 122842. <a href="https://doi.org/10.1016/j.oceaneng.2025.122842" target="_blank"> doi.org/10.1016/j.oceaneng.2025.122842 </a> </li>
    <li><b>Author A</b>, Author C. “Paper title…”. <em>Journal Name</em>, 2024.</li>
  </ul>
</details>
