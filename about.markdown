---
layout: splash
classes: narrow
title: ""
permalink: /about/

header:
  overlay_color: "#000000ff"
  overlay_filter: "0.0"
  overlay_image: /assets/images/IMG_2297.JPEG
  caption: "Tongariro National Park, NZ"
---

# About Me
<style>
  /* Page-scoped styles for about page layout */
  .about-grid { display:flex; justify-content:center; }
  .about-grid .about-inner { display:flex; gap:2rem; max-width:1400px; width:100%; align-items:flex-start; }
  .about-grid .about-text { flex:3; min-width:320px; }
  .about-grid .about-photo { flex:2; min-width:200px; display:flex; justify-content:center; }
  .about-grid .about-photo img { width:80%; height:auto; border-radius:6px; display:block; }

  /* Stack vertically on small screens so image does not overflow */
  @media (max-width: 760px) {
    .about-grid .about-inner { flex-direction:column; align-items:center; }
    .about-grid .about-text { order:2; width:100%; min-width:0; }
    .about-grid .about-photo { order:1; width:100%; }
    .about-grid .about-photo img { width:60%; }
  }
</style>

<div class="about-grid">
  <div class="about-inner">
    <div class="about-text">
      <p>Hi there! I’m a mechanical engineering PhD candidate at Carnegie Mellon, developing simulation and process monitoring tools to study laser-based additive manufacturing. I have a broad skillset that spans a wide range of engineering disciplines in both hardware and software.</p>
      <p>In my spare time, I enjoy building hardware and software projects, running, playing guitar and piano, traveling, and just being outside. In addition to these pursuits, I also love to talk about:</p>
      <ul>
        <li>My favorite running routes</li>
        <li>The history of spaceflight</li>
        <li>University of Oregon or Oregon State University athletics</li>
        <li>90s and 2000s Alt Rock</li>
        <li>The best Trader Joe’s snacks</li>
      </ul>
      <p>Learn more about my engineering journey in my <a href="/assets/files/Craig_Weeks_Resume.pdf" target="_blank" rel="noopener noreferrer">resume</a> or check out some of my <a href="/publications+projects/">projects</a>.</p>
    </div>
    <div class="about-photo">
      <img src="/assets/images/full_bio_photo.JPEG" alt="Craig Weeks">
    </div>
  </div>
</div>