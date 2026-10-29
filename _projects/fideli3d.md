---
layout: page
title: Fideli3D
img: assets/img/projects/thumbs/fideli3d.jpg
period: January 2026 - May 2026
description: A multi-agent framework for geometrically consistent 3D data storytelling.
importance: 4
category: Research
permalink: /projects/fideli3d/
---

**HKUST (GZ)** · Advisor: [Prof. Pan Hui](https://panhui.people.ust.hk/)  
January 2026 - May 2026

While generative AI has democratized visual content creation, ensuring geometric consistency and analytical faithfulness in 3D data storytelling remains a persistent challenge. End-to-end pixel-based generative models often lack the precise spatial control required for rigorous data communication, as stochastic hallucinations lead to inconsistent spatial proportions and "drifting" artifacts. We present Fideli3D, a multi-agent framework that transforms narrative text into immersive, geometrically consistent 3D data videos. Fideli3D operates through a specialized layered pipeline, which mainly includes: (1) a Semantic Layer that parses narrative intent into structured shot scripts; (2) an Asset Generation Layer that procedurally assembles 3D entities; (3) a Configuration Layer that maps high-level intent into Required Visual Properties (RVPs); and (4) an Optimization Layer that frames camera control as a Constraint Satisfaction Problem (CSP) and applies optimal search over the feasible set to derive camera trajectories. Fideli3D achieves a superior balance among narrative legibility, aesthetic composition, and temporal continuity. Quantitative benchmarks using VBench and user studies demonstrate that Fideli3D significantly outperforms state-of-the-art commercial models in background consistency and data faithfulness, establishing a robust paradigm for automated, high-fidelity data communication.

<div class="project-media">
  <h2>Framework</h2>
  <img class="project-figure" src="{{ '/assets/img/projects/fideli3d.jpg' | relative_url }}" alt="Fideli3D framework">
  <h2>Result</h2>
  <p>This video is a data storytelling piece about the world's ten tallest buildings.</p>
  <video class="project-video" controls playsinline preload="metadata" src="{{ '/assets/video/fideli3d.mp4' | relative_url }}"></video>
</div>
