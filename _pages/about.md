---
layout: about
title: about
permalink: /
subtitle: MPhil Student, Computational Media and Arts · HKUST (Guangzhou)

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>MPhil Student</p>
    <p>Computational Media and Arts</p>
    <p><a href="https://www.hkust-gz.edu.cn/">HKUST (Guangzhou)</a></p>
    <p>Advisor: <a href="https://panhui.people.ust.hk/">Prof. Pan Hui</a></p>

selected_papers: false
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

I am an MPhil student in Computational Media and Arts at The Hong Kong University of Science and Technology (Guangzhou), advised by [Prof. Pan Hui](https://panhui.people.ust.hk/). I received my B.Eng. in Intelligent Science and Technology from Shanghai University in 2025 (GPA 87.03/100, major ranking 9/58), where I was advised by [Prof. Liming Xin](https://cs.shu.edu.cn/info/1461/40551.htm).

I study how people work with generative models. My research interests are human–AI interaction, video generation, agents, and computer vision.

## Education

**MPhil in Computational Media and Arts**, 2025–present  
The Hong Kong University of Science and Technology (Guangzhou)  
Advisor: [Prof. Pan Hui](https://panhui.people.ust.hk/)

**B.Eng. in Intelligent Science and Technology**, 2021–2025  
Shanghai University · GPA 87.03/100 · Major ranking 9/58  
Advisor: [Prof. Liming Xin](https://cs.shu.edu.cn/info/1461/40551.htm)

## Research

### [CultureLens]({{ '/projects/culturelens/' | relative_url }})

Steerable Human–AI Video Storytelling with Cultural Transcreation Strategies  
HKUST (Guangzhou) · Advisor: Prof. Pan Hui · June 2026 – September 2026

CultureLens is an interactive video generation workbench that supports cross-cultural translation through four transcreation modes: Literal, Analogy, Explanation, and Sensation. The modes cover narrative restructuring, audiovisual presentation, and voice-over. Based on a formative study (N=8), mixed-methods studies from creator (N=18) and audience (N=54) perspectives show that it reduces mental demand versus a general-purpose LLM baseline, maintains usability, and reduces stereotypical perception among Western audiences.

### [RepoDirector]({{ '/projects/repodirector/' | relative_url }})

Decision-Carrying Storyboards for Repository-Grounded Generative Video Authoring  
HKUST (Guangzhou) · Advisor: Prof. Anyi Rao · March 2026 – May 2026

RepoDirector is an integrated authoring system for open-source promotional videos, centered on a persistent editable storyboard carrying scene-level narration, prompts, assets, ordering, and production status across stages. Offline validation found repository contexts generally evidence-supported but incomplete. In a within-subjects study (N=18), it reduced all NASA-TLX workload dimensions and raised SUS from 41.94 to 79.58 versus a fragmented toolchain, with scene-local interventions in 11/18 sessions, though owner judgments showed no consistent final-video quality advantage.

### [GlyphFix]({{ '/projects/glyphfix/' | relative_url }})

An Interactive Agent for Optimizing Garbled Text in AI-Generated Videos  
HKUST (Guangzhou) · Advisor: Prof. Pan Hui · February 2026 – May 2026

GlyphFix is an interactive multimodal agent that repairs garbled text in AI-generated videos via aesthetic decoupling, separating semantic restoration from generative artifacts. It employs a cascading pipeline with LLMs and VLMs for semantic inference and computer vision for spatiotemporal tracking, plus a mixed-initiative workspace that automates tracking while reserving typographic control for users.

### [Fideli3D]({{ '/projects/fideli3d/' | relative_url }})

A Multi-Agent Framework for Geometrically Consistent 3D Data Storytelling  
HKUST (Guangzhou) · Advisor: Prof. Pan Hui · January 2026 – May 2026

Fideli3D is a multi-agent framework that transforms narrative text into 3D data videos via a layered pipeline. A Semantic Layer parses narrative intent into shot scripts. An Asset Layer procedurally assembles 3D entities. A Configuration Layer maps high-level intent to required visual properties. An Optimization Layer formulates camera control as a constraint satisfaction problem to derive optimal trajectories.

### [Ink Symphony]({{ '/projects/ink-symphony/' | relative_url }})

A “Zhi Yin” Narrative from Calligraphy to Music in VR  
HKUST (Guangzhou) · Advisor: Prof. Kang Zhang · January 2026 – April 2026

Ink Symphony is a VR system that lets users practice calligraphy in a traditional Chinese landscape. The system captures brushstrokes, analyzes stroke speed and pressure, and generates real-time traditional Chinese music. Tempo adapts to writing speed, while music type and intensity respond to stroke weight. The final output is a synchronized calligraphy video with a context-aware melody that matches the writing process.

### [Human Preference Decoding]({{ '/projects/human-preference-decoding/' | relative_url }})

Human Preference Decoding via ERP Analysis  
Shanghai University · Advisor: Prof. Huiran Zhang · July 2024 – December 2024

This project investigated neural correlates of human preference using event-related potentials, focusing on early N1 and late positive potential components. EEG data were analyzed from participants viewing a mixed-image dataset. N1 amplitude in frontal regions increased for preferred items, while LPP amplitude was larger for both preferred and non-preferred items. The work proposes an integrated model combining N1 and LPP to quantify preference intensity and direction. Preprint: [arXiv:2505.19879](https://arxiv.org/abs/2505.19879).

### [Lake Water-Level Control]({{ '/projects/lake-water-level/' | relative_url }})

Neural Network Anti-Interference Controller for Lake Water Level Balance  
Shanghai University · Advisor: Prof. Liming Xin · January 2024 – May 2024

This project proposed a neural-network anti-interference architecture for lake water-level control, enabling real-time sensing of water-level changes and automatic adjustment to maintain stability. It analyzed the spatial distribution and historical hydrological data of the lake area, established the mathematical model for water-level balance control, and designed the neural-network controller structure. Paper: [DOI:10.1117/12.3035322](https://doi.org/10.1117/12.3035322).

### [Multimodal Depression Recognition]({{ '/projects/multimodal-depression-recognition/' | relative_url }})

Personality Measurement via Intelligent Interview  
Shanghai University · Advisor: Prof. Xing Wu · July 2023 – December 2023

This project developed a Transformer-based multimodal model combining speech and facial recognition to assess depression severity through AI-driven interviews. My part was facial-feature preprocessing and detection with OpenCV, followed by feature extraction and analysis with YOLOv8. The extracted features were transformed into signal representations and passed to a large model for the final evaluation.

### [Welding Defect Detection]({{ '/projects/welding-defect-detection/' | relative_url }})

Shanghai University · Advisor: Prof. Xing Wu · March 2023 – September 2023

This project developed a YOLOv5-based defect detection system for industrial welding inspection. A factory-provided image dataset was curated and labeled into four defect categories: crack, rust, bubble, and impurity. The model was trained and validated on real production-line data. The system achieved a 34.31% reduction in manual inspection time and a 15.63% improvement in detection accuracy compared with existing baseline methods.

### [Aviation Safety Risk Analysis]({{ '/projects/aviation-safety/' | relative_url }})

Risk Analysis and Flight Technical Assessment Based on Aviation Safety Data  
Shanghai University · Advisor: Prof. Xing Wu · February 2023 – May 2023

This project collected and cleaned Quick Access Recorder data, exceedance data, and flight operation data from the Civil Aviation Administration of China website. A random forest classifier identified key environmental factors affecting aviation safety. A real-time automated early-warning mechanism was built with an Extra Trees classification model.
