---
layout: page
title: GlyphFix
img: assets/img/projects/thumbs/glyphfix.jpg
period: February 2026 - May 2026
description: An interactive agent for repairing garbled text in AI-generated video.
importance: 3
category: Research
permalink: /projects/glyphfix/
---

**HKUST (GZ)** · Advisor: [Prof. Pan Hui](https://panhui.people.ust.hk/)  
February 2026 - May 2026

AI-generated videos can have illegible or temporally unstable text when the scene remains usable. We present GlyphFix, a mixed-initiative workflow for localized text repair that separates semantic content, spatial behavior, and visual appearance. GlyphFix associates text regions across frames, generates revisable semantic proposals, stabilizes estimated trajectories, and supports bounded appearance editing. A formative study with five video creators informed the workflow; an offline technical characterization examined semantic proposal ranking and spatial processing; and a within-subject study with 16 participants evaluated execution of creator-known repairs. GlyphFix required 27.2% of the mean completion time of participant-selected conventional workflows. An assessment by five raters found high semantic correctness (M=6.00, SD=0.71), repair quality of M=4.60 (SD=1.14), and 80% practical-use acceptability, while visual integration remained limited. Interviews showed automation reduced repetitive frame-level work while redistributing creator control across repair layers. We articulate aesthetic decoupling as selectively preserving evidence from generated artifacts while re-authoring unstable properties.

<div class="project-media">
  <h2>Framework</h2>
  <img class="project-figure" src="{{ '/assets/img/projects/glyphfix.jpg' | relative_url }}" alt="GlyphFix framework">
  <h2>Result</h2>
  <p>These three videos are comparisons. In each clip, Original is the source video, and GlyphFix is the video after repair with our system.</p>
  <p class="project-video-label">Ratings</p>
  <video class="project-video" controls playsinline preload="metadata" src="{{ '/assets/video/glyphfix-ratings.mp4' | relative_url }}"></video>
  <p class="project-video-label">Building</p>
  <video class="project-video" controls playsinline preload="metadata" src="{{ '/assets/video/glyphfix-building.mp4' | relative_url }}"></video>
  <p class="project-video-label">Planet</p>
  <video class="project-video" controls playsinline preload="metadata" src="{{ '/assets/video/glyphfix-planet.mp4' | relative_url }}"></video>
</div>
