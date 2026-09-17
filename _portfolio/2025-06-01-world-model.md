---
title: Physics-grounded World Model from Videos/Images
date: 2025-06-01 00:00:00.000000000 +00:00
role: Research intern
organization: "<a href='https://www.a4x.io/'>A4x (Rightly Robotics)</a>, Hangzhou, China"
period: 2025.09 -- 2026.08
collection: portfolio
permalink: "/portfolio/world-model/"
---
<ul>
<li>Reconstruct, simulate, and generate physics-grounded 4D world models that encompass not only geometry, appearance, and temporal motion but also underlying physical attributes, governing dynamics laws, and causal interaction.</li>
<li><a href="https://can-lee.github.io/deformmaster-web/">DeformMaster</a>: an interactive physics-neural world model for deformable objects from videos.</li>
<li><a href="https://can-lee.github.io/deformsmith-web/">DeformSmith</a>: generate deformable assets from text or a single image with a hierarchy of agents for geometry, physical modeling, material behavior, and robot interaction.</li>
<li>Applications: high-fidelity data synthesis and robotic manipulation of deformable objects.</li>
</ul>

<div class="project-image-pair">
  <img src="{{ '/images/physics-grounded_wm_fig_1.jpg' | relative_url }}" alt="Multi-camera capture setup with deformable objects on a table" loading="lazy">
  <img src="{{ '/images/physics-grounded_wm_fig_2.jpg' | relative_url }}" alt="Robot manipulator lifting a cloth in the multi-camera setup" loading="lazy">
  <img src="{{ '/images/DeformMaster_robot_cloth_demo.gif' | relative_url }}" alt="DeformMaster robot cloth manipulation demo" width="640" height="480">
</div>

<div class="project-image-pair project-image-pair--demos">
  <video controls autoplay loop muted playsinline preload="metadata" aria-label="DeformSmith robot manipulation: full scene">
    <source src="{{ '/assets/videos/deformsmith-robot-scene.mp4' | relative_url }}" type="video/mp4">
  </video>
  <video controls autoplay loop muted playsinline preload="metadata" aria-label="DeformSmith robot manipulation: object close-up">
    <source src="{{ '/assets/videos/deformsmith-robot-closeup.mp4' | relative_url }}" type="video/mp4">
  </video>
</div>
