---
layout: about
title: about
permalink: /
subtitle: MPhil Student, Computational Media and Arts · HKUST(GZ)

selected_papers: false
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

<style>
  .profile.float-left {
    margin-bottom: 1rem;
  }
  @media (min-width: 576px) {
    .profile.float-left {
      margin-right: 2.75rem;
      margin-bottom: 0.5rem;
    }
  }

  .soft-card {
    margin: 0 0 0.95rem;
    padding: 0.9rem 1.15rem 0.45rem;
    border: 1px solid color-mix(in srgb, var(--global-text-color) 12%, transparent);
    border-radius: 10px;
    background: color-mix(in srgb, var(--global-text-color) 3.5%, var(--global-bg-color));
  }
  .research-card {
    padding: 0.15rem 1.15rem 0.2rem;
  }
  .research-card h3 {
    margin-top: 0.85rem;
  }
  .intro-card {
    padding: 1.15rem 1.2rem 0.55rem;
  }
  .intro-card::after {
    content: "";
    display: block;
    clear: both;
  }
  .intro-card .more-info p {
    display: block;
  }
  .intro-card .profile-email {
    font-size: 0.78rem;
    line-height: 1.35;
    overflow-wrap: normal;
  }
  .prize-card {
    padding-top: 0.75rem;
    padding-bottom: 0.45rem;
  }
</style>

<div class="soft-card intro-card">
  <div class="profile float-left">
    <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Xiangze Meng" class="img-fluid z-depth-1 rounded" loading="eager">
    <div class="more-info">
      <p>MPhil Student</p>
      <p>Computational Media and Arts</p>
      <p><a href="https://www.hkust-gz.edu.cn/">HKUST(GZ)</a></p>
      <p>Advisor: <a href="https://panhui.people.ust.hk/">Prof. Pan Hui</a></p>
      <p class="profile-email">Email: <a href="mailto:xmeng560@connect.hkust-gz.edu.cn">xmeng560@<wbr>connect.hkust-gz.edu.cn</a></p>
    </div>
  </div>
  <p>Hi, everyone! My name is Xiangze Meng, and you can also call me Richard! Now I am an <strong>MPhil</strong> student in Computational Media and Arts at <strong>The Hong Kong University of Science and Technology (Guangzhou)</strong>, advised by <a href="https://panhui.people.ust.hk/">Prof. Pan Hui</a>. I received my B.Eng. in Intelligent Science and Technology from <strong>Shanghai University</strong> in 2025, where I was advised by <a href="https://cs.shu.edu.cn/info/1461/40551.htm">Prof. Liming Xin</a>.</p>
  <p>I study how people work with generative models. My research interests are <strong>human–AI interaction</strong>, <strong>video generation</strong>, <strong>agents</strong>, and <strong>computer vision</strong>.</p>
  <p>I enjoy swimming 🏊, badminton 🏸, basketball 🏀, and table tennis 🏓. In my spare time, I also love photography 📷. I often travel with my camera, even though it is really heavy!</p>
</div>

## Education

<div class="soft-card education-card" markdown="1">

**MPhil in Computational Media and Arts**, 2025–present  
HKUST (GZ)  
Advisor: [Prof. Pan Hui](https://panhui.people.ust.hk/)

**B.Eng. in Intelligent Science and Technology**, 2021–2025  
Shanghai University  
Advisor: [Prof. Liming Xin](https://cs.shu.edu.cn/info/1461/40551.htm)

</div>

## Research

<div class="soft-card research-card" markdown="1">

### [CultureLens]({{ '/projects/culturelens/' | relative_url }})

Steerable Human–AI Video Storytelling with Cultural Transcreation Strategies  
HKUST (GZ) · Advisor: [Prof. Pan Hui](https://panhui.people.ust.hk/) · June 2026 – September 2026

Short-form videos are essential for cross-cultural communication, yet general-purpose text-to-video AI tools can produce stereotypes or literal translations of cultural terms. However, little research has tackled this. Based on a formative study (N=8), we designed and implemented CultureLens, an interactive video generation workbench that supports creators in explicitly steering cross-cultural translation through four transcreation (translation and creation) modes—Literal, Analogy, Explanation, and Sensation—covering video narrative structure reconstruction, audiovisual presentation, and voice-over narration. Mixed-methods studies from creator (N=18) and audience (N=54) perspectives suggest that CultureLens reduces mental demand compared to a general-purpose LLM baseline while ensuring usability, and videos generated reduce stereotypical perception among Western audience. Findings further suggest translation is not merely textual substitution but a restructuring of the video's narrative framework. Moreover, the greater the cultural distance, the more translation choices affect audience comprehension. We discuss design implications for cross-cultural AI creative tools.

</div>

<div class="soft-card research-card" markdown="1">

### [RepoDirector]({{ '/projects/repodirector/' | relative_url }})

Decision-Carrying Storyboards for Repository-Grounded Generative Video Authoring  
HKUST (GZ) · Advisor: [Prof. Anyi Rao](https://anyirao.com) · March 2026 – May 2026

Creating promotional videos for open-source projects requires developers to translate repository content into audience-facing narratives while coordinating scripts, generated media, and editing across disconnected tools. We present RepoDirector, an integrated authoring system organized around a persistent, editable storyboard that carries scene-level narration, prompts, assets, ordering, and production status across stages. An offline validation showed that automatically constructed repository contexts were generally evidence-supported but incomplete in feature coverage. In a counterbalanced within-subjects study with 18 participants, the complete RepoDirector workflow reduced perceived workload across all NASA-TLX dimensions and increased mean SUS from 41.94 to 79.58 relative to a fragmented toolchain. Interaction logs showed scene-local intervention in 11 of 18 sessions, including direct editing, targeted regeneration, and cross-stage revisitation. Repository-owner judgments showed no consistent final-video quality advantage, distinguishing workflow-level coordination benefits from artifact quality.

</div>

<div class="soft-card research-card" markdown="1">

### [GlyphFix]({{ '/projects/glyphfix/' | relative_url }})

An Interactive Agent for Optimizing Garbled Text in AI-Generated Videos  
HKUST (GZ) · Advisor: [Prof. Pan Hui](https://panhui.people.ust.hk/) · February 2026 – May 2026

AI-generated videos can have illegible or temporally unstable text when the scene remains usable. We present GlyphFix, a mixed-initiative workflow for localized text repair that separates semantic content, spatial behavior, and visual appearance. GlyphFix associates text regions across frames, generates revisable semantic proposals, stabilizes estimated trajectories, and supports bounded appearance editing. A formative study with five video creators informed the workflow; an offline technical characterization examined semantic proposal ranking and spatial processing; and a within-subject study with 16 participants evaluated execution of creator-known repairs. GlyphFix required 27.2% of the mean completion time of participant-selected conventional workflows. An assessment by five raters found high semantic correctness (M=6.00, SD=0.71), repair quality of M=4.60 (SD=1.14), and 80% practical-use acceptability, while visual integration remained limited. Interviews showed automation reduced repetitive frame-level work while redistributing creator control across repair layers. We articulate aesthetic decoupling as selectively preserving evidence from generated artifacts while re-authoring unstable properties.

</div>

<div class="soft-card research-card" markdown="1">

### [Fideli3D]({{ '/projects/fideli3d/' | relative_url }})

A Multi-Agent Framework for Geometrically Consistent 3D Data Storytelling  
HKUST (GZ) · Advisor: [Prof. Pan Hui](https://panhui.people.ust.hk/) · January 2026 – May 2026

While generative AI has democratized visual content creation, ensuring geometric consistency and analytical faithfulness in 3D data storytelling remains a persistent challenge. End-to-end pixel-based generative models often lack the precise spatial control required for rigorous data communication, as stochastic hallucinations lead to inconsistent spatial proportions and "drifting" artifacts. We present Fideli3D, a multi-agent framework that transforms narrative text into immersive, geometrically consistent 3D data videos. Fideli3D operates through a specialized layered pipeline, which mainly includes: (1) a Semantic Layer that parses narrative intent into structured shot scripts; (2) an Asset Generation Layer that procedurally assembles 3D entities; (3) a Configuration Layer that maps high-level intent into Required Visual Properties (RVPs); and (4) an Optimization Layer that frames camera control as a Constraint Satisfaction Problem (CSP) and applies optimal search over the feasible set to derive camera trajectories. Fideli3D achieves a superior balance among narrative legibility, aesthetic composition, and temporal continuity. Quantitative benchmarks using VBench and user studies demonstrate that Fideli3D significantly outperforms state-of-the-art commercial models in background consistency and data faithfulness, establishing a robust paradigm for automated, high-fidelity data communication.

</div>

<div class="soft-card research-card" markdown="1">

### [Ink Symphony]({{ '/projects/ink-symphony/' | relative_url }})

A "Zhi Yin" Narrative from Calligraphy to Music in VR  
HKUST (GZ) · Advisor: [Prof. Kang Zhang](https://cma.hkust-gz.edu.cn/faculty-regular/kang-zhang/) · January 2026 – April 2026

For centuries, Chinese calligraphy has been seen mainly as a visual art. However, the musical qualities of brush movement, including speed and rhythm, remain largely unexplored in digital representations. This paper presents Ink Symphony, a VR approach that turns the act of writing into music. We draw on the classical Chinese story of "Zhi Yin," in which the listener Zhong Ziqi could hear Bo Ya's music and imagine mountains and rivers in his mind. In our approach, the user writes with a virtual brush in a digital landscape, taking the role of Bo Ya, while a computational listener responds like Zhong Ziqi with music. By treating "Zhi Yin" as a framework for cross-modal interaction, we present a culturally grounded way to connect calligraphic action with sound. The approach offers an additional auditory perspective on calligraphic movement and temporality, presented as a design exploration without formal evaluation.

</div>

<div class="soft-card research-card" markdown="1">

### [Human Preference Decoding]({{ '/projects/human-preference-decoding/' | relative_url }})

Human Preference Decoding via ERP Analysis  
Shanghai University · Advisor: [Prof. Huiran Zhang](https://cs.shu.edu.cn/info/1471/40951.htm) · July 2024 – December 2024

Human preference research is a significant domain in psychology and psychophysiology, with broad applications in psychiatric evaluation and daily life quality enhancement. This study explores the neural mechanisms of human preference judgments through the analysis of event-related potentials (ERPs), specifically focusing on the early N1 component and the late positive potential (LPP). Using a mixed-image dataset covering items such as hats, fruits, snacks, scarves, drinks, and pets, we elicited a range of emotional responses from participants while recording their brain activity via EEG. Our work innovatively combines the N1 and LPP components to reveal distinct patterns across different preference levels. The N1 component, particularly in frontal regions, showed increased amplitude for preferred items, indicating heightened early visual attention. Similarly, the LPP component exhibited larger amplitudes for both preferred and non-preferred items, reflecting deeper emotional engagement and cognitive evaluation. In addition, we introduced a relationship model that integrates these ERP components to assess the intensity and direction of preferences, providing a novel method for interpreting EEG data in the context of emotional responses. These findings offer valuable insights into the cognitive and emotional processes underlying human preferences and present new possibilities for brain-computer interface applications, personalized marketing, and product design. Preprint: [arXiv:2505.19879](https://arxiv.org/abs/2505.19879).

</div>

<div class="soft-card research-card" markdown="1">

### [Lake Water-Level Control]({{ '/projects/lake-water-level/' | relative_url }})

Neural Network Anti-Interference Controller for Lake Water Level Balance  
Shanghai University · Advisor: [Prof. Liming Xin](https://cs.shu.edu.cn/info/1461/40551.htm) · January 2024 – May 2024

Due to the complexity of hydrological characteristics in lake systems and their susceptibility to environmental changes, water level control in lake systems has always been a highly challenging issue. This paper proposes a water level equilibrium control scheme for lake systems based on an intelligent anti-interference architecture using neural networks. By analyzing the spatial distribution structure and historical hydrological data of the Great Lakes system, a mathematical model for water level equilibrium control is established. Subsequently, an intelligent controller structure based on neural networks is proposed. This controller can real-time perceive changes in lake system water levels and automatically adjust control strategies to maintain water levels fluctuating within appropriate ranges. Finally, the proposed method is applied to a simulator of the Great Lakes system in North America. The results indicate that the proposed method can achieve stable control of lake water levels under different environmental conditions, demonstrating good stability and robustness. Paper: [DOI:10.1117/12.3035322](https://doi.org/10.1117/12.3035322).

</div>
