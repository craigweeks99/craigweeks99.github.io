---
title: Simulated Imaging in L-PBF Melt Pools
excerpt: Resolving thermal imaging artifacts using thermal+optical simulation
thumbnail: /assets/images/projects/reflections/GraphicalAbstract.jpg
date: 2025-01-15
permalink: /projects/cfd-rl-codesign/
layout: splash
---

# Simulated Imaging in L-PBF Melt Pools

<figure style="margin: 0 auto; display: flex; flex-direction: column; align-items: center; max-width: 600px;">
  <img src="/assets/images/projects/reflections/GraphicalAbstract.jpg"  
       alt="Simulated thermal imaging of L-PBF melt pool"  
       style="width: 100%; height: auto;">
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
    Simulated thermal imaging of L-PBF melt pool.
  </figcaption>
</figure>

In metal additive manufacturing, monitoring the temperatures reached by the metal is important for monitoring the process. However, due to complex physical interactions in the melt pool region, it is difficult to precicely obtain high temperatures in the material even with emissivity-independent ratiometric imaging. I developed a method to simulate thermal imaging on concave melt pool surfaces in Laser Powder Bed Fusion (L-PBF), accounting for high-temperature reflections that distort experimental temperature data. The method first solves for net radiosity emerging from the melt pool and then divides that energy up into bundles of rays that are traced through an optical lens to a detector. 

<div style="display: flex; justify-content: center; gap: 1em; flex-wrap: wrap; max-width: 1000px; margin: 0 auto;">
  <figure style="flex: 1; min-width: 280px; display: flex; flex-direction: column; align-items: center; text-align: center;">
    <div style="height: 300px; display: flex; align-items: center; justify-content: center;">
      <img src="/assets/images/projects/reflections/RHT.png"
           alt="Comparison of intensity without (left) and with (right) reflected radiation."
           style="max-height: 100%; width: auto;">
    </div>
    <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Comparison of intensity distribution across the melt pool surface without (left) and with (right) reflected radiation.
    </figcaption>
  </figure>

  <figure style="flex: 1; min-width: 280px; display: flex; flex-direction: column; align-items: center; text-align: center;">
    <div style="height: 300px; display: flex; align-items: center; justify-content: center;">
      <img src="/assets/images/projects/reflections/4bnew.png"
           alt="Planoconvex lens geometry used for ray tracing to image plane."
           style="max-height: 100%; width: auto;">
    </div>
    <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Planoconvex lens geometry used for ray tracing to image plane.
    </figcaption>
  </figure>
</div>

Validated on 316L stainless steel, the approach reproduces temperatures within 4–6% of experimental values and reveals conditions inside the vapor depression that drive keyhole porosity and alloying element evaporation. Findings suggest that longer imaging wavelengths decrease the impact of reflections during imaging and a probable emissivity of ~0.32 for liquid steel. The technique can aid in process monitoring and model validation, with broader applications in aerospace and renewable energy. 

Full manuscript coming soon!




