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

### News
- May 2025: Our work **"MAGIC: Motion-Aware Generative Inference via Confidence-Guided LLM"** [[arXiv](https://arxiv.org/pdf/2505.16456)] is posted online.
- Apr 2025: Our work **"Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC"** [[arXiv](https://arxiv.org/abs/2502.07007)] has been accepted by **IJCAI 2025 Survey Track**. The final version will be released soon.


## Content
---
- [Relevant Surveys](#relevant-surveys)
     - [AIGC Surveys](#aigc-surveys)
     - [Physical Aware AIGC Surveys](#physical-aware-aigc-surveys)
- [Datasets](#datasets)
     - [Synthetic Datasets](#synthetic-datasets)
     - [Real-world Datasets](#real-world-datasets)
- [Benchmark](#benchmark)
- [Static 3D Generation](#static-3d-generation)
     - [Single Image-based 3D Generation](#single-image-based-3d-generation)
     - [Text-based 3D Generation](#text-based-3d-generation)
- [Dynamic 3D Generation](#dynamic-3d-generation)
     - [Vision-based Dynamic 3D Generation](#vison-based-dynamic-3d-generation)
     - [NeRF-based Dynamic 3D Generation](#nerf-based-dynamic-3d-generation)
     - [GS-based Dynamic 3D Generation](#gs-based-dynamic-3d-generation)
- [4D Generation](#4d-generation)
- [Video Generation](#video-generation)
- [Others](#others)
     - [Fluids](#fluids)
---
## Relevant Surveys

### AIGC Surveys
1. \[arXiv 2023\] A comprehensive survey of ai-generated content (AIGC): A history of generative ai from GAN to ChatGPT [Paper](https://arxiv.org/abs/2303.04226)
2. \[arxiv 2024\] Advances in 3D generation: A survey [Paper](https://arxiv.org/abs/2401.17807)
3. \[arxiv 2024\] A comprehensive survey on 3D content generation [Paper](https://arxiv.org/abs/2402.01166)
4. \[arxiv 2025\] Advances in 4D Generation: A Survey [Paper](https://arxiv.org/abs/2503.14501)
### Physical Aware AIGC Surveys
1. \[arXiv 2025\] Exploring the Evolution of Physics Cognition in Video Generation: A Survey [Paper](https://arxiv.org/pdf/2503.21765)
2. \[ACM COMPUT SURV 2025\] Physics-informed computer vision: A review and perspectives [Paper](https://arxiv.org/abs/2305.18035)
3. \[arXiv 2025\] Generative physical ai in vision: A survey [Paper](https://arxiv.org/abs/2501.10928)
4. \[IJCAI 2025\] Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC [Paper](https://arxiv.org/abs/2502.07007)
5. \[arXiv 2025\] Exploring the Evolution of Physics Cognition in Video Generation: A Survey [Paper](https://arxiv.org/abs/2503.21765)


---
## Datasets

### Synthetic Datasets
1. \[PAC-NeRF\] PAC-NeRF: Physics Augmented Continuum Neural Radiance Fields for Geometry-Agnostic System Identification [Paper](https://arxiv.org/abs/2303.05512) [Project](https://github.com/xuan-li/PAC-NeRF)
2. \[Spring-Gaus\] Reconstruction and Simulation of Elastic Objects with Spring-Mass 3D Gaussians [Paper](https://arxiv.org/abs/2403.09434) [Project](https://github.com/Colmar-zlicheng/Spring-Gaus)
### Real-world Datasets
1. \[VIDEOPHY\] VIDEOPHY: Evaluating Physical Commonsense for Video Generation [Paper](https://arxiv.org/pdf/2406.03520) [Project](https://github.com/Hritikbansal/videophy)
2. \[Physics 101\] Physics 101: Learning Physical Object Properties from Unlabeled Videos [Paper](http://phys101.csail.mit.edu/papers/phys101_bmvc.pdf) [Project](http://phys101.csail.mit.edu/)
3. \[Physics IQ Benchmark\] Physics IQ Benchmark: Do generative video models understand physical principles? [Paper](https://arxiv.org/abs/2501.09038) [Project](https://physics-iq.github.io/)
4. \[WISA-80K\] WISA: World Simulator Assistant for Physics-Aware Text-to-Video Generation [Paper](https://arxiv.org/pdf/2503.08153) [Project](https://360cvgroup.github.io/WISA/)

---
## Benchmark

1. \[PhysUniBench\] PhysUniBench: An Undergraduate-Level Physics Reasoning Benchmark for Multimodal Models [Paper](https://arxiv.org/abs/2506.17667) [Project](https://prismax-team.github.io/PhysUniBenchmark/)
2. \[UGPhysics\] UGPhysics: A Comprehensive Benchmark for Undergraduate Physics Reasoning with Large Language Models [Paper](https://arxiv.org/abs/2502.00334) [Code](https://github.com/YangLabHKUST/UGPhysics)
---
## Static 3D Generation
### Single Image-based 3D Generation
1. \[NeurIPS 2024\] Physically Compatible 3D Object Modeling from a Single Image [Paper](https://arxiv.org/abs/2405.20510)
2. \[NeurIPS 2024\] PhyCAGE: Physically Plausible Compositional 3D Asset Generation from a Single Image [Paper](https://arxiv.org/abs/2411.18548)
3. \[arXiv 2025\] DSO: Aligning 3D Generators with Simulation Feedback for Physical Soundness [Paper](https://ruiningli.com/dso)
4. \[arXiv 2025\] LLM-to-Phy3D: Physically Conform Online 3D Object Generation with LLMs [Paper](https://arxiv.org/pdf/2506.11148)
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
2. \[ICLR 2023\] PAC-NeRF: Physics Augmented Continuum Neural Radiance Fields for Geometry-Agnostic System Identification [Paper](https://arxiv.org/abs/2303.05512) [Project](https://github.com/xuan-li/PAC-NeRF)
3. \[CVPR 2024\] Improving Physics-Augmented Continuum Neural Radiance Field-Based Geometry-Agnostic System Identification with Lagrangian Particle Optimization [Paper](https://arxiv.org/abs/2406.04155)
4. \[CVPR 2024\] PIE-NeRF: Physics-based Interactive Elastodynamics with NeRF [Paper](https://arxiv.org/abs/2311.13099) [Project](https://fytalon.github.io/pienerf/)
### GS-based Dynamic 3D Generation
1. \[ECCV 2024\] Reconstruction and Simulation of Elastic Objects with Spring-Mass 3D Gaussians [Paper](https://arxiv.org/abs/2403.09434) [Project](https://github.com/Colmar-zlicheng/Spring-Gaus)
2. \[ECCV 2024\] PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation [Paper](https://arxiv.org/abs/2404.13026) [Project](https://physdreamer.github.io/)
3. \[arXiv 2024\] Physics3D: Learning Physical Properties of 3D Gaussians via Video Diffusion [Paper](https://arxiv.org/abs/2406.04338) [Project](https://liuff19.github.io/Physics3D/)
4. \[arXiv 2024\] PhysMotion: Physics-Grounded Dynamics From a Single Image [Paper](https://arxiv.org/abs/2411.17189) [Project](https://supertan0204.github.io/physmotion_website/)
5. \[arXiv 2024\] Gaussian Splashing: Unified Particles for Versatile Motion Synthesis and Rendering [Paper](https://arxiv.org/abs/2401.15318)
6. \[arXiv 2024\] Gaussian Splashing: Direct Volumetric Rendering Underwater [Paper](https://arxiv.org/abs/2411.19588)
7. \[AAAI 2025\] DreamPhysics: Learning Physics-Based 3D Dynamics with Video Diffusion Priors [Paper](https://arxiv.org/abs/2406.01476) [Project](https://github.com/tyhuang0428/DreamPhysics)
8. \[CVPR 2024\] PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics [Paper](https://arxiv.org/abs/2311.12198) [Project](https://xpandora.github.io/PhysGaussian/)
9. \[ICLR 2025\] OmniPhysGS: 3D Constitutive Gaussians for General Physics-Based Dynamics Generation [Paper](https://arxiv.org/abs/2501.18982) [Project](https://wgsxm.github.io/projects/omniphysgs/)
10. \[NeurIPS 2024\] NeuMA: Neural Material Adaptor for Visual Grounding of Intrinsic Dynamics [Paper](https://arxiv.org/abs/2410.08257) [Project](https://xjay18.github.io/projects/neuma.html)
11. \[NeurIPS 2024\] Gaussian-Informed Continuum for Physical Property Identification and Simulation [Paper](https://arxiv.org/pdf/2406.14927) [Project](https://jukgei.github.io/project/gic/)
12. \[arXiv 2025\] MAGIC: Motion-Aware Generative Inference via Confidence-Guided LLM [Paper](https://arxiv.org/pdf/2505.16456)
13. \[arXiv 2025\] ParticleGS: Particle-Based Dynamics Modeling of 3D Gaussians for Prior-free Motion Extrapolation [Paper](https://arxiv.org/pdf2505.20270) [Project](https://github.com/QuanJinSheng/ParticleGS)
14 \[arXiv 2025\] PIG: Physically-based Multi-Material Interaction with 3D Gaussians [Paper](https://arxiv.org/pdf/2506.07657)


---
## 4D Generation
1. \[arXiv 2024\] Phy124: Fast Physics-Driven 4D Content Generation from a Single Image [Paper](https://arxiv.org/pdf/2409.07179)
2. \[arXiv 2024\] GASP: Gaussian Splatting for Physic-Based Simulations [Paper](https://arxiv.org/abs/2409.05819) [Project](https://waczjoan.github.io/GASP/)
3. \[arXiv 2024\] Phys4DGen: A Physics-Driven Framework for Controllable and Efficient 4D Content Generation from a Single Image [Paper](https://arxiv.org/abs/2411.16800) [Project](https://github.com/JiajingLin/Phys4DGen)
4. \[arXiv 2024\] Trans4D: Realistic Geometry-Aware Transition for Compositional Text-to-4D Synthesis [Paper](https://arxiv.org/abs/2410.07155)
5. \[arXiv 2024\] Unleashing the Potential of Multi-modal Foundation Models and Video Diffusion for 4D Dynamic Physical Scene Simulation [Paper](https://arxiv.org/abs/2411.14423)
6. \[ICLR 2025\] Compositional 4D Dynamic Scenes Understanding with Physics Priors for Video Question Answering [Paper](https://arxiv.org/abs/2406.00622)


---
## Video Generation
1. \[arXiv 2025\] WISA: World Simulator Assistant for Physics-Aware Text-to-Video Generation [Paper](https://arxiv.org/abs/2503.08153)
2. \[arXiv 2025\] Think Before You Diffuse: LLMs-Guided Physics-Aware Video Generation [Paper](https://arxiv.org/abs/2505.21653)
3. \[CVPR 2025\] PhyT2V: LLM-Guided Iterative Self-Refinement for Physics-Grounded Text-to-Video Generation [Paper](https://arxiv.org/abs/2412.00596)


---
## Others
### Fluids
1. \[arXiv 2025\] RainyGS: Efficient Rain Synthesis with Physically-Based Gaussian Splatting [Paper](https://arxiv.org/pdf/2503.21442)
2. \[arXiv 2025\] Vid2Fluid: 3D Dynamic Fluid Assets from Single-View Videos with Generative Gaussian Splatting [Paper](https://arxiv.org/pdf/2503.00868)
3. \[CVPR 2025\] FluidNexus: 3D Fluid Reconstruction and Prediction from a Single Video [Paper](https://arxiv.org/abs/2503.04720)
4. \[arXiv 2025\] RDPO: Real Data Preference Optimization for Physics Consistency Video Generation [Paper](https://arxiv.org/abs/2506.18655)
