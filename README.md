# Awesome Physical AIGC Lists ![Awesome](https://awesome.re/badge.svg)

This repository provides a comprehensive investigation of advanced physical aware AIGC works.

<p align="center" style="font-size:20px;">
  <h2>Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC
  <a href="https://arxiv.org/abs/2502.07007"><img src='https://img.shields.io/badge/arXiv-PDF-red?style=flat&logo=arXiv&logoColor=red' alt='arXiv PDF'></a>
  </h2>
</p>
<p align="center">
  <a> Siwei Meng <sup>1</sup></a>,
  <a> Yawei Luo <sup>2</sup></a>,
  <a href="https://pinglmlcv.github.io/pingliu264/">Ping Liu<sup>1</sup></a>
</p>

<p align="center">
  <sup>1</sup><a href="https://www.unr.edu/cse">Department of Computer Science, University of Nevada, Reno</a><br>
  <sup>2</sup><a href="http://www.cst.zju.edu.cn/cstenglish/main.htm">School of Software Technology, Zhejiang University</a><br>
</p>

If you believe there are additional works that should be included in our list, please do not hesitate to send us an email (siweim@unr.edu, yaweiluo@zju.edu.cn, pino.pingliu@gmail.com) or raise an issue. Your suggestions and comments are invaluable to ensuring the completeness and accuracy of our resource.

## Content
---
- [Relevant Surveys](#relevant-surveys)
     - [AIGC Surveys](#aigc-surveys)
     - [Physical Aware AIGC Surveys](#physical-aware-aigc-surveys)
- [Static 3D Generation](#static-3d-generation)
     - [Single image-based 3D Generation](#single-image-based-3d-generation)
     - [Text-based 3D Generation](#text-based-3d-generation)
- [Dynamic 3D Generation](#dynamic-3d-generation)
     - [Vision-based Dynamic 3D Generation](#vison-based-dynamic-3d-generation)
     - [NeRF-based Dynamic 3D Generation](#nerf-based-dynamic-3d-generation)
     - [GS-based Dynamic 3D Generation](#gs-based-dynamic-3d-generation)
- [4D Generation](#4d-generation)
- [Others](#others)
     - [Segmentation](#segmentation)
     - [Recognition](#recognition)
     - [Editing](#editing)
---
## Relevant Surveys

### AIGC Surveys
\[arXiv 2023\] A comprehensive survey of ai-generated content (AIGC): A history of generative ai from GAN to ChatGPT [Paper](https://arxiv.org/abs/2303.04226)

\[arxiv 2024\] Advances in 3D generation: A survey [Paper](https://arxiv.org/abs/2401.17807)

\[arxiv 2024\] A comprehensive survey on 3D content generation [Paper](https://arxiv.org/abs/2402.01166)

### Physical Aware AIGC Surveys
\[ACM COMPUT SURV 2025\] Physics-informed computer vision: A review and perspectives [Paper](https://arxiv.org/abs/2305.18035)

\[arXiv 2025\] Generative physical ai in vision: A survey [Paper](https://arxiv.org/abs/2501.10928)

---
## Static 3D Generation
### Single image-based 3D Generation
1. \[NeurIPS 2024\] Physically Compatible 3D Object Modeling from a Single Image [Paper](https://arxiv.org/abs/2405.20510)
2. \[NeurIPS 2024\] PhyCAGE: Physically Plausible Compositional 3D Asset Generation from a Single Image [Paper](https://arxiv.org/abs/2411.18548)
### Text-based 3D Generation
1. \[arXiv 2024\] Atlas3D: Physically Constrained Self-Supporting Text-to-3D for Simulation and Fabrication [Paper](https://arxiv.org/abs/2405.18515)
2. \[arXiv 2025\] PhiP-G: Physics-Guided Text-to-3D Compositional Scene Generation [Paper](https://arxiv.org/abs/2502.00708)
3. \[arXiv 2025\] LAYOUTDREAMER: Physics-guided Layout for Text-to-3D Compositional Scene Generation [Paper](https://arxiv.org/abs/2502.01949)

---
## Dynamic 3D Generation
### Vision-based Dynamic 3D Generation
1. \[CVPR 2024\] Generative Image Dynamics [Paper](https://arxiv.org/abs/2309.07906) [Project](https://generative-dynamics.github.io/)
2. \[NeurIPS 2024\] MotionCraft: Physics-based Zero-Shot Video Generation [Paper](https://arxiv.org/abs/2401.13856) [Project](https://mezzelfo.github.io/MotionCraft/)
3. \[RAL 2023\] Physics 101: Learning Physical Object Properties from Unlabeled Videos [Paper](http://phys101.csail.mit.edu/papers/phys101_bmvc.pdf) [Project](http://phys101.csail.mit.edu/)
4. \[ECCV 2024\] PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation [Paper](https://arxiv.org/pdf/2409.18964) [Project](https://github.com/stevenlsw/physgen)
5. \[CVPR 2025\] PhyT2V: LLM-Guided Iterative Self-Refinement for Physics-Grounded Text-to-Video Generation [Paper](https://arxiv.org/abs/2412.00596) [Project](https://github.com/pittisl/PhyT2V)
### NeRF-based Dynamic 3D Generation
1. \[WACV 2024\] ParticleNeRF: A Particle-Based Encoding for Online Neural Radiance Fields [Paper](https://arxiv.org/abs/2211.04041) [Project](https://github.com/jc211/ParticleNeRF)
2. 
### GS-based Dynamic 3D Generation
1. \[ECCV 2024\] Reconstruction and Simulation of Elastic Objects with Spring-Mass 3D Gaussians [Paper](https://arxiv.org/abs/2403.09434) [Project](https://github.com/Colmar-zlicheng/Spring-Gaus)
2. 

---
## 4D Generation
1. \[arXiv 2025\] GC-ConsFlow: Leveraging Optical Flow Residuals and Global Context for Robust Deepfake Detection [Paper](https://arxiv.org/pdf/2501.13435)
2. \[ICASSP 2025\] AUDIO-VISUAL DEEPFAKEDETECTIONWITHLOCALTEMPORALINCONSISTENCIES [Paper](https://arxiv.org/pdf/2501.08137)
3. \[arXiv 2025\] Vulnerability-Aware Spatio-Temporal Learning for Generalizable and Interpretable Deepfake Video Detection [Paper](https://arxiv.org/pdf/2501.01184)

---
## Others
### Segmentation
1. \[CVPR 2024\] Rethinking the Up-Sampling Operations in CNN-based Generative Network for Generalizable Deepfake Detection [Paper](https://arxiv.org/abs/2312.10461)
2. \[CVPR 2024\] LAA-Net: Localized Artifact Attention Network for Quality-Agnostic and Generalizable Deepfake Detection [Paper](https://arxiv.org/abs/2401.13856)
3. \[arXiv 2024\] Data-Independent Operator: A Training-Free Artifact Representation Extractor for Generalizable Deepfake Detection [Paper](https://arxiv.org/abs/2403.06803)
4. \[arXiv 2024\] A Single Simple Patch is All You Need for AI-generated Image Detection [Paper](https://arxiv.org/abs/2402.01123)
### Recognition
1. \[arXiv 2025\] GC-ConsFlow: Leveraging Optical Flow Residuals and Global Context for Robust Deepfake Detection [Paper](https://arxiv.org/pdf/2501.13435)
2. \[ICASSP 2025\] AUDIO-VISUAL DEEPFAKEDETECTIONWITHLOCALTEMPORALINCONSISTENCIES [Paper](https://arxiv.org/pdf/2501.08137)
3. \[arXiv 2025\] Vulnerability-Aware Spatio-Temporal Learning for Generalizable and Interpretable Deepfake Video Detection [Paper](https://arxiv.org/pdf/2501.01184)
### Editing