# Awesome Physical AIGC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of **physics-aware AI-generated content (AIGC)**: generative models whose outputs (3D assets, 4D scenes, videos, images, audio) must obey physical dynamics, and the benchmarks and analyses that test them. This repository accompanies our IJCAI 2025 survey.

<p align="center"><img src="teaser_1.png" width="100%" alt="Taxonomy of physics-aware AIGC with paper counts per category and venue"></p>

<p align="center">
  <h2 align="center">Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC
  <a href="https://arxiv.org/abs/2502.07007"><img src='https://img.shields.io/badge/arXiv-PDF-red?style=flat&logo=arXiv&logoColor=red' alt='arXiv PDF'></a>
  </h2>
</p>
<p align="center">
  <a>Siwei Meng<sup>1</sup></a>,
  <a>Yawei Luo<sup>2</sup></a>,
  <a href="https://pinglmlcv.github.io/pingliu264/">Ping Liu<sup>1</sup></a>
</p>
<p align="center">
  <sup>1</sup><a href="https://www.unr.edu/cse">Department of Computer Science and Engineering, University of Nevada, Reno</a><br>
  <sup>2</sup><a href="http://www.cst.zju.edu.cn/cstenglish/main.htm">School of Software Technology, Zhejiang University</a>
</p>

If you know of work that should be listed, or a preprint that has since been accepted, please open an issue or a pull request, or email us (siweim@unr.edu, yaweiluo@zju.edu.cn, pingl@unr.edu).

## News

* [2026.11] 🏆 Our paper [When Physical Preferences Meet Semantic Constraints: Physical and Semantic Direct Preference Optimization for Text-to-Video Generation](https://arxiv.org/abs/2607.16947) (PSDPO) received the **Outstanding Paper Award** at ACM MM 2026 (Multimedia Generative and Foundation Models track).
* [2026.11] 📌 Added: [PhysLoop: Harnessing LLMs' Physics Awareness for Self-Improving Video Generation Models](https://arxiv.org/abs/2611.16748) (arXiv 2026), by Yuxuan Chen, Xiaojie Li, Hao Chen, Juncheng Ma, Kewei Zhang, Zhongjing Du, Guoqiang Wei, Fangfang Wang, Zhen Dong, Zhiyang Dou, Liming Zhao, Yan Zeng, Jianwei Zhang, Daquan Zhou.
* [2026.11] 📌 Added: [K2V: Generative Keyframing For Physically Plausible Video Generation](https://arxiv.org/abs/2611.17324) (arXiv 2026), by Felix O'Mahony, Daniel Olmeda Reino, Roberto Cipolla, Ayush Tewari.
* [2026.11] 📌 Added: [VDAWorld: World Modelling via VLM-Directed Abstraction and Simulation](https://arxiv.org/abs/2512.11061) (SIGGRAPH Asia 2026), by Felix O'Mahony, Roberto Cipolla, Ayush Tewari.
* [2026.11] 📌 Added: [Physics-IQ Verified](https://arxiv.org/abs/2606.18943) (arXiv 2026), by Tim Rädsch, Yuki M Asano, Hilde Kuehne, Stefan Bauer, Priyank Jaini, Robert Geirhos, Carsten T. Lüth.
* [2026.11] 🔥 The list has been reorganized around a new taxonomy and now covers **288** papers, **188** of them published at top venues (2024 to 2026).
* [2025.04] 🔥 Our survey **Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC** has been accepted by the IJCAI 2025 Survey Track.

## Our Work

Our own papers on physics-aware generation. Each one also appears in its category below, marked with ⭐ **Ours**.

- ![IJCAI 2025](https://img.shields.io/badge/IJCAI%202025-1f6feb?style=flat-square) 🔥 **Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC** [[Paper]](https://arxiv.org/abs/2502.07007)<br>
  *Siwei Meng, Yawei Luo, Ping Liu*<br>Survey of how physical priors enter 3D, 4D and video generation, organized by task and by 3D representation.
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhyMAGIC: Physical Motion-Aware Generative Inference with Confidence-guided VLM** [[Paper]](https://arxiv.org/abs/2505.16456)<br>
  *Siwei Meng, Yawei Luo, Ping Liu*<br>Generates physically plausible motion from a single image, with a confidence-guided VLM reasoning about the physical process.
- ![ACM MM 2026](https://img.shields.io/badge/ACM%20MM%202026-1f6feb?style=flat-square) 🔥 **When Physical Preferences Meet Semantic Constraints: Physical and Semantic Direct Preference Optimization for Text-to-Video Generation** *(Oral, Outstanding Paper Award)* [[Paper]](https://arxiv.org/abs/2607.16947)<br>
  *Siwei Meng, Yawei Luo, Shu Zhang, Ping Liu*<br>Aligns text-to-video models with physical preferences while keeping prompt semantics, through physical and semantic DPO.
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **PhyMetric: Diagnosing Physical Plausibility in Text-to-Video Generation via Scene-Level QA** [[Paper]](https://neurips.cc/virtual/2026/poster/139124)<br>
  *Siwei Meng, Xuerou Cai, Rui Hu, Ping Liu*<br>Diagnoses the physical plausibility of text-to-video outputs with scene-level question answering.

## Scope and Inclusion

- **In scope:** generation whose output must respect physical dynamics or mechanics (motion, forces, materials, contact, fluids), the evaluation of such generation, and analyses of what video and world models know about physics.
- **Out of scope:** physically-based rendering and relighting, scientific machine learning (PDE solvers, neural operators), physics-based character control, and LLM-only physics question answering.
- **Inclusion:** papers published at top venues from 2024 to 2026, plus arXiv preprints (2024 to 2026). Blue badges mark peer-reviewed venues, gray badges mark workshops, posters and findings tracks, and red badges mark preprints. Within each category, papers are sorted by venue tier and then by year (newest first).

## Contents

- [Surveys](#surveys)
- [Physics-Aware Static 3D Generation](#physics-aware-static-3d-generation)
  - [Physically Valid and Simulation-Ready Assets](#physically-valid-and-simulation-ready-assets)
  - [Physically Plausible Scene and Layout Generation](#physically-plausible-scene-and-layout-generation)
- [Physics-Grounded 3D and 4D Dynamics](#physics-grounded-3d-and-4d-dynamics)
  - [Simulation-Integrated 3D Representations](#simulation-integrated-3d-representations)
  - [Physical Property Estimation from Videos](#physical-property-estimation-from-videos)
  - [Physics Distilled from Generative Priors](#physics-distilled-from-generative-priors)
  - [Physics-Aware 4D Scene Generation](#physics-aware-4d-scene-generation)
  - [Fluids, Fire, Weather and Other Phenomena](#fluids-fire-weather-and-other-phenomena)
- [Physics-Aware Video Generation](#physics-aware-video-generation)
  - [Simulation-in-the-Loop and Explicit Dynamics](#simulation-in-the-loop-and-explicit-dynamics)
  - [Physical Control Signals](#physical-control-signals)
  - [LLM/VLM Reasoning and Agentic Planning](#llmvlm-reasoning-and-agentic-planning)
  - [Physics-Aware Representations, Objectives and Data](#physics-aware-representations-objectives-and-data)
  - [Post-Training with Physics Rewards, Preferences and RL](#post-training-with-physics-rewards-preferences-and-rl)
  - [Inference-Time Guidance and Refinement](#inference-time-guidance-and-refinement)
  - [Embodied, Driving and Human-Object Interaction World Models](#embodied-driving-and-human-object-interaction-world-models)
- [Physics-Aware Image Generation and Editing](#physics-aware-image-generation-and-editing)
- [Physics-Aware Audio Generation](#physics-aware-audio-generation)
- [Evaluation](#evaluation)
  - [Benchmarks](#benchmarks)
  - [Automatic Evaluators, Critics and Detectors](#automatic-evaluators-critics-and-detectors)
  - [Datasets](#datasets)
- [Physical Understanding in Video and World Models](#physical-understanding-in-video-and-world-models)
- [Related Awesome Lists](#related-awesome-lists)
- [Citation](#citation)

### Taxonomy at a Glance

| Section | Sub-category | Papers |
|:--|:--|--:|
| Surveys | | 7 |
| Physics-Aware Static 3D Generation | Physically Valid and Simulation-Ready Assets | 16 |
|  | Physically Plausible Scene and Layout Generation | 10 |
| Physics-Grounded 3D and 4D Dynamics | Simulation-Integrated 3D Representations | 21 |
|  | Physical Property Estimation from Videos | 31 |
|  | Physics Distilled from Generative Priors | 9 |
|  | Physics-Aware 4D Scene Generation | 10 |
|  | Fluids, Fire, Weather and Other Phenomena | 6 |
| Physics-Aware Video Generation | Simulation-in-the-Loop and Explicit Dynamics | 20 |
|  | Physical Control Signals | 7 |
|  | LLM/VLM Reasoning and Agentic Planning | 21 |
|  | Physics-Aware Representations, Objectives and Data | 25 |
|  | Post-Training with Physics Rewards, Preferences and RL | 15 |
|  | Inference-Time Guidance and Refinement | 6 |
|  | Embodied, Driving and Human-Object Interaction World Models | 10 |
| Physics-Aware Image Generation and Editing | | 9 |
| Physics-Aware Audio Generation | | 5 |
| Evaluation | Benchmarks | 31 |
|  | Automatic Evaluators, Critics and Detectors | 8 |
|  | Datasets | 3 |
| Physical Understanding in Video and World Models | | 18 |

---

## Surveys

- ![IJCAI 2025](https://img.shields.io/badge/IJCAI%202025-1f6feb?style=flat-square) 🔥 **Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC** ⭐ **Ours** [[Paper]](https://arxiv.org/abs/2502.07007)<br>
  *Siwei Meng, Yawei Luo, Ping Liu*
- ![ACM CSUR 2024](https://img.shields.io/badge/ACM%20CSUR%202024-1f6feb?style=flat-square) 🔥 **Physics-Informed Computer Vision: A Review and Perspectives** [[Paper]](https://arxiv.org/abs/2305.18035)<br>
  *Chayan Banerjee, Kien Nguyen, Clinton Fookes, George Karniadakis*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Advances in 4D Generation: A Survey** [[Paper]](https://arxiv.org/abs/2503.14501)<br>
  *Qiaowei Miao, Kehan Li, Jinsheng Quan, Zhiyuan Min, Shaojie Ma, Yichao Xu, Yi Yang, Ping Liu, Yawei Luo*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Aligning Perception, Reasoning, Modeling and Interaction: A Survey on Physical AI** [[Paper]](https://arxiv.org/abs/2510.04978)<br>
  *Kun Xiang, Terry Jingchen Zhang, Yinya Huang, Jixi He, Zirong Liu, Yueling Tang, Ruizhe Zhou, Lijing Luo, Youpeng Wen, Xiuwei Chen, Bingqian Lin, Jianhua Han, Hang Xu, Hanhui Li, Bin Dong, Xiaodan Liang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Exploring the Evolution of Physics Cognition in Video Generation: A Survey** [[Paper]](https://arxiv.org/abs/2503.21765)<br>
  *Minghui Lin, Xiang Wang, Yishan Wang, Shu Wang, Fengqi Dai, Pengxiang Ding, Cunxiang Wang, Zhengrong Zuo, Nong Sang, Siteng Huang, Donglin Wang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Generative Physical AI in Vision: A Survey** [[Paper]](https://arxiv.org/abs/2501.10928)<br>
  *Daochang Liu, Junyu Zhang, Anh-Dung Dinh, Eunbyung Park, Shichao Zhang, Ajmal Mian, Mubarak Shah, Chang Xu*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Simulating the Visual World with Artificial Intelligence: A Roadmap** [[Paper]](https://arxiv.org/abs/2511.08585)<br>
  *Jingtong Yue, Ziqi Huang, Zhaoxi Chen, Xintao Wang, Pengfei Wan, Ziwei Liu*

[⬆ Back to top](#contents)

## Physics-Aware Static 3D Generation

Assets and scenes that must stand, assemble, or be simulated: physical validity is a constraint on the generated geometry.

### Physically Valid and Simulation-Ready Assets

Single objects whose geometry or material is optimized or checked for stability, buildability, or simulation readiness.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhysGen: Physically Grounded 3D Shape Generation for Industrial Design** [[Paper]](https://arxiv.org/abs/2512.00422) [[Code]](https://github.com/kasvii/PhysGen)<br>
  *Yingxuan You, Chen Zhao, Hantao Zhang, Ming Xu, Pascal Fua*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhysX-Anything: Simulation-Ready Physical 3D Assets from Single Image** [[Paper]](https://arxiv.org/abs/2511.13648)<br>
  *Ziang Cao, Fangzhou Hong, Zhaoxi Chen, Liang Pan, Ziwei Liu*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **AutoPhyX: Automatic Text-Condition Physics Property Generation** [[Paper]](https://radiancefields.com/papers/autophyx-automatic-text-condition-physics-property-generation)<br>
  *Bei Huang, Yixin Chen, Hongbin Zha, Yuru Pei, Siyuan Huang*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **PhysForge: Generating Physics-Grounded 3D Assets for Interactive Virtual World** [[Paper]](https://openreview.net/forum?id=BBIcqAryty)<br>
  *Yunhan Yang, Chunshi Wang, Junliang Ye, Yang Li, Zanxin Chen, Zehuan Huang, Yao Mu, Zhuo Chen, Chunchao Guo, Xihui Liu*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **DSO: Aligning 3D Generators with Simulation Feedback for Physical Soundness** [[Paper]](https://arxiv.org/abs/2503.22677)<br>
  *Ruining Li, Chuanxia Zheng, Christian Rupprecht, Andrea Vedaldi*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **Generating Physically Stable and Buildable Brick Structures from Text** [[Paper]](https://arxiv.org/abs/2505.05469)<br>
  *Ava Pun, Kangle Deng, Ruixuan Liu, Deva Ramanan, Changliu Liu, Jun-Yan Zhu*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **Guiding Diffusion-Based Articulated Object Generation by Partial Point Cloud Alignment and Physical Plausibility Constraints** [[Paper]](https://arxiv.org/abs/2508.00558)<br>
  *Jens U. Kreber, Joerg Stueckler*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **Generating Physically Sound Designs from Text and a Set of Physical Constraints** [[Paper]](https://openreview.net/forum?id=eZIqkDf8m2)<br>
  *Gregory Barber, Todd Henry, Mulugeta A Haile*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **PhysX-3D: Physical-Grounded 3D Asset Generation** *(Spotlight)* [[Paper]](https://openreview.net/forum?id=hLJLP3CmHR)<br>
  *Ziang Cao, Zhaoxi Chen, Liang Pan, Ziwei Liu*
- ![SIGGRAPH 2025](https://img.shields.io/badge/SIGGRAPH%202025-1f6feb?style=flat-square) 🔥 **Dress-1-to-3: Single Image to Simulation-Ready 3D Outfit with Diffusion Prior and Differentiable Physics** [[Paper]](https://arxiv.org/abs/2502.03449)<br>
  *Xuan Li, Chang Yu, Wenxin Du, Ying Jiang, Tianyi Xie, Yunuo Chen, Yin Yang, Chenfanfu Jiang*
- ![CVPR 2024](https://img.shields.io/badge/CVPR%202024-1f6feb?style=flat-square) 🔥 **GPLD3D: Latent Diffusion of 3D Shape Generative Models by Enforcing Geometric and Physical Priors** [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Dong_GPLD3D_Latent_Diffusion_of_3D_Shape_Generative_Models_by_Enforcing_CVPR_2024_paper.html)<br>
  *Yuan Dong, Qi Zuo, Xiaodong Gu, Weihao Yuan, Zhengyi Zhao, Zilong Dong, Liefeng Bo, Qixing Huang*
- ![ECCV 2024](https://img.shields.io/badge/ECCV%202024-1f6feb?style=flat-square) 🔥 **Tree-D Fusion: Simulation-Ready Tree Dataset from Single Images with Diffusion Priors** [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/5802_ECCV_2024_paper.php)<br>
  *Jae Joong Lee, Bosheng Li, Sara M Beery, Jonathan Huang, Songlin Fei, Raymond A. Yeh, Bedrich Benes*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **Atlas3D: Physically Constrained Self-Supporting Text-to-3D for Simulation and Fabrication** [[Paper]](https://arxiv.org/abs/2405.18515)<br>
  *Yunuo Chen, Tianyi Xie, Zeshun Zong, Xuan Li, Feng Gao, Yin Yang, Ying Nian Wu, Chenfanfu Jiang*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **Physically Compatible 3D Object Modeling from a Single Image** *(Spotlight)* [[Paper]](https://arxiv.org/abs/2405.20510)<br>
  *Minghao Guo, Bohan Wang, Pingchuan Ma, Tianyuan Zhang, Crystal Elaine Owens, Chuang Gan, Joshua B. Tenenbaum, Kaiming He, Wojciech Matusik*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **LLM-to-Phy3D: Physically Conform Online 3D Object Generation with LLMs** [[Paper]](https://arxiv.org/abs/2506.11148)<br>
  *Melvin Wong, Yueming Lyu, Thiago Rios, Stefan Menzel, Yew-Soon Ong*
- ![arXiv 2024](https://img.shields.io/badge/arXiv%202024-b31b1b?style=flat-square) 🔥 **PhyCAGE: Physically Plausible Compositional 3D Asset Generation from a Single Image** [[Paper]](https://arxiv.org/abs/2411.18548)<br>
  *Han Yan, Mingrui Zhang, Yang Li, Chao Ma, Pan Ji*

### Physically Plausible Scene and Layout Generation

Multi-object scenes and layouts with contact, support, and collision constraints.

- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **Inclusive Interactive Collisions for Multi-View Consistent Compositional 3D Generation** [[Paper]](https://arxiv.org/abs/2606.24206)<br>
  *Chang Liu, Mingwen Shao, Xiang Lv, Xinyuan Chen, Lingzhuang Meng, Qiao Zhang, Zhengyi Gong, Jinghao Hu*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **PAT3D: Physics-Augmented Text-to-3D Scene Generation** [[Paper]](https://openreview.net/forum?id=iIRxFkeCuY)<br>
  *Guying Lin, Kemeng Huang, Michael Liu, Ruihan Gao, Hanke Chen, Lyuhao Chen, Beijia Lu, Taku Komura, Yuan Liu, Jun-Yan Zhu, Minchen Li*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **PhyScensis: Physics-Augmented LLM Agents for Complex Physical Scene Arrangement** [[Paper]](https://openreview.net/forum?id=aCVfhY4Qen)<br>
  *Yian Wang, Han Yang, Minghao Guo, Xiaowen Qiu, Tsun-Hsuan Wang, Wojciech Matusik, Joshua B. Tenenbaum, Chuang Gan*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **PhyScene3D: Physically Consistent 3D Interactive Tabletop Scene Generation** [[Paper]](https://openreview.net/forum?id=T4A2aYyaq9)<br>
  *Weixing Chen, Zhuoqian Feng, Yang Liu, Yexin Zhang, Yifan Wen, Yinghong Liao, Weichao Qiu, Guanbin Li, Liang Lin*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **SceneSmith: Agentic Generation of Simulation-Ready Indoor Scenes** *(Spotlight)* [[Paper]](https://openreview.net/forum?id=WwS8CTpUA6)<br>
  *Nicholas Pfaff, Thomas Cohn, Sergey Zakharov, Rick Cory, Russ Tedrake*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **STABLE: Simulation-Ready Tabletop Layout Generation via a Semantics-Physics Dual System** [[Paper]](https://openreview.net/forum?id=pGpEGZhL7Y)<br>
  *Zhen Luo, Yixuan Yang, Xudong XU, Jinkun Hao, Zhaoyang Lyu, Feng Zheng, Jiangmiao Pang, Yanwei Fu*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **HoloScene: Simulation-Ready Interactive 3D Worlds from a Single Video** [[Paper]](https://openreview.net/forum?id=BOwPpmRgmW)<br>
  *Hongchi Xia, Chih-Hao Lin, Hao-Yu Hsu, Quentin Leboutet, Katelyn Gao, Michael Paulitsch, Benjamin Ummenhofer, Shenlong Wang*
- ![CVPR 2024](https://img.shields.io/badge/CVPR%202024-1f6feb?style=flat-square) 🔥 **PhyScene: Physically Interactable 3D Scene Synthesis for Embodied AI** *(Highlight)* [[Paper]](https://arxiv.org/abs/2404.09465) [[Code]](https://physcene.github.io)<br>
  *Yandan Yang, Baoxiong Jia, Peiyuan Zhi, Siyuan Huang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **LayoutDreamer: Physics-guided Layout for Text-to-3D Compositional Scene Generation** [[Paper]](https://arxiv.org/abs/2502.01949)<br>
  *Yang Zhou, Zongjin He, Qixuan Li, Chao Wang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **PhiP-G: Physics-Guided Text-to-3D Compositional Scene Generation** [[Paper]](https://arxiv.org/abs/2502.00708)<br>
  *Qixuan Li, Chao Wang, Zongjin He, Yan Peng*

[⬆ Back to top](#contents)

## Physics-Grounded 3D and 4D Dynamics

A 3D representation is coupled with a physical model so that it moves under forces. Sub-categories follow where the physical parameters come from.

### Simulation-Integrated 3D Representations

Gaussians, NeRFs, or meshes driven by a physics solver (MPM, PBD, FEM, spring-mass) with user- or text-specified materials.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **GaussianFluent: Gaussian Simulation for Dynamic Scenes with Mixed Materials** [[Paper]](https://arxiv.org/abs/2601.09265)<br>
  *Bei Huang, Yixin Chen, Ruijie Lu, Gang Zeng, Hongbin Zha, Yuru Pei, Siyuan Huang*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Perceptual 3D Simulation with Physical World Modeling** [[Paper]](https://arxiv.org/abs/2606.27575)<br>
  *Wanhee Lee, Klemen Kotar, Rahul Mysore Venkatesh, Jared Watrous, Daniel L. K. Yamins*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **Boba: Batched Simulation for Physics-Based Gaussian Digital Twins** [[Paper]](https://link.springer.com/chapter/10.1007/978-3-032-37553-7_12) [[Code]](https://github.com/jianxiapyh/Boba-Public)<br>
  *Yihan Pang, Hanxiao Jiang, Sushant Kondguli, Sarita Adve, Shenlong Wang*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **MeGAS: Thermomechanical Dynamic Gaussian Splatting for Thermophysical Scene Editing** [[Paper]](https://arxiv.org/abs/2606.23455) [[Project]](https://zju3dv.github.io/MeGAS/)<br>
  *Zesong Yang, Yuanhang Lei, Liyuan Cui, Yihang Chen, Jiaer Huang, Boming Zhao, Peter Yichen Chen, Hujun Bao, Zhaopeng Cui*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **Efficient and Robust Physical 3DGS-MPM Simulation via Interior Filling and Text-Physics Optimization** [[Paper]](https://neurips.cc/virtual/2026/poster/149910)<br>
  *Yikun Ma, Yiqing Li, Jingwen Ye, Zhongkai Wu, Weidong Zhang, Lin Gao, Zhi Jin*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **Fracture-GS: Dynamic Fracture Simulation with Physics-Integrated Gaussian Splatting** [[Paper]](https://openreview.net/forum?id=zcAwK50ft0)<br>
  *Xiaogang Wang, Hongyu Wu, Wenfeng Song, Kai Xu*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **DecoupledGaussian: Object-Scene Decoupling for Physics-Based Interaction** [[Paper]](https://arxiv.org/abs/2503.05484) [[Code]](https://wangmiaowei.github.io/DecoupledGaussian.github.io/)<br>
  *Miaowei Wang, Yibo Zhang, Weiwei Xu, Rui Ma, Changqing Zou, Daniel Morris*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **Gaussian Splashing: Unified Particles for Versatile Motion Synthesis and Rendering** [[Paper]](https://arxiv.org/abs/2401.15318)<br>
  *Yutao Feng, Xiang Feng, Yintong Shang, Ying Jiang, Chang Yu, Zeshun Zong, Tianjia Shao, Hongzhi Wu, Kun Zhou, Chenfanfu Jiang, Yin Yang*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **GausSim: Foreseeing Reality by Gaussian Simulator for Elastic Objects** [[Paper]](https://arxiv.org/abs/2412.17804)<br>
  *Yidi Shao, Mu Huang, Chen Change Loy, Bo Dai*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **MaGS: Reconstructing and Simulating Dynamic 3D Objects with Mesh-adsorbed Gaussian Splatting** [[Paper]](https://arxiv.org/abs/2406.01593)<br>
  *Shaojie Ma, Yawei Luo, Wei Yang, Yi Yang*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **PhysSplat: Efficient Physics Simulation for 3D Scenes via MLLM-Guided Gaussian Splatting** [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Zhao_PhysSplat_Efficient_Physics_Simulation_for_3D_Scenes_via_MLLM-Guided_Gaussian_ICCV_2025_paper.html)<br>
  *Haoyu Zhao, Hao Wang, Xingyue Zhao, Hao Fei, Hongqiu Wang, Chengjiang Long, Hua Zou*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **MPMAvatar: Learning 3D Gaussian Avatars with Accurate and Robust Physics-Based Dynamics** [[Paper]](https://openreview.net/forum?id=Qr0YbuilFb)<br>
  *Changmin Lee, Jihyun Lee, Tae-Kyun Kim*
- ![CVPR 2024](https://img.shields.io/badge/CVPR%202024-1f6feb?style=flat-square) 🔥 **PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics** *(Highlight)* [[Paper]](https://arxiv.org/abs/2311.12198)<br>
  *Tianyi Xie, Zeshun Zong, Yuxing Qiu, Xuan Li, Yutao Feng, Yin Yang, Chenfanfu Jiang*
- ![CVPR 2024](https://img.shields.io/badge/CVPR%202024-1f6feb?style=flat-square) 🔥 **PIE-NeRF: Physics-based Interactive Elastodynamics with NeRF** [[Paper]](https://arxiv.org/abs/2311.13099)<br>
  *Yutao Feng, Yintong Shang, Xuan Li, Tianjia Shao, Chenfanfu Jiang, Yin Yang*
- ![ECCV 2024](https://img.shields.io/badge/ECCV%202024-1f6feb?style=flat-square) 🔥 **Language-Driven Physics-Based Scene Synthesis and Editing via Feature Splatting** [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/5788_ECCV_2024_paper.php)<br>
  *Ri-Zhao Qiu, Ge Yang, Weijia Zeng, Xiaolong Wang*
- ![ECCV 2024](https://img.shields.io/badge/ECCV%202024-1f6feb?style=flat-square) 🔥 **PhysAvatar: Learning the Physics of Dressed 3D Avatars from Visual Observations** [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/5446_ECCV_2024_paper.php)<br>
  *Yang Zheng, Qingqing Zhao, Guandao Yang, Wang Yifan, Donglai Xiang, Florian Dubost, Dmitry Lagun, Thabo Beeler, Federico Tombari, Leonidas Guibas, Gordon Wetzstein*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **LiveScene: Language Embedding Interactive Radiance Fields for Physical Scene Control and Rendering** [[Paper]](https://neurips.cc/virtual/2024/poster/95700)<br>
  *Delin Qu, Qizhi Chen, Pingrui Zhang, Xianqiang Gao, Bin Zhao, Zhigang Wang, Dong Wang, Xuelong Li*
- ![SIGGRAPH 2024](https://img.shields.io/badge/SIGGRAPH%202024-1f6feb?style=flat-square) 🔥 **VR-GS: A Physical Dynamics-aware Interactive Gaussian Splatting System in Virtual Reality** [[Paper]](https://arxiv.org/abs/2401.16663)<br>
  *Ying Jiang, Chang Yu, Tianyi Xie, Xuan Li, Yutao Feng, Huamin Wang, Minchen Li, Henry Lau, Feng Gao, Yin Yang, Chenfanfu Jiang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **PhysTalk: Language-driven Real-time Physics in 3D Gaussian Scenes** [[Paper]](https://arxiv.org/abs/2512.24986)<br>
  *Luca Collorone, Mert Kiray, Indro Spinelli, Fabio Galasso, Benjamin Busam*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **PIG: Physically-based Multi-Material Interaction with 3D Gaussians** [[Paper]](https://arxiv.org/abs/2506.07657)<br>
  *Zeyu Xiao, Zhenyi Wu, Mingyang Sun, Qipeng Yan, Yufan Guo, Zhuoer Liang, Lihua Zhang*
- ![arXiv 2024](https://img.shields.io/badge/arXiv%202024-b31b1b?style=flat-square) 🔥 **GASP: Gaussian Splatting for Physic-Based Simulations** [[Paper]](https://arxiv.org/abs/2409.05819) [[Project]](https://waczjoan.github.io/GASP/)<br>
  *Piotr Borycki, Weronika Smolak, Joanna Waczyńska, Marcin Mazur, Sławomir Tadeja, Przemysław Spurek*

### Physical Property Estimation from Videos

System identification: material parameters, constitutive laws, or learned simulators are recovered from observed videos.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **GenMatter: Perceiving Physical Objects with Generative Matter Models** [[Paper]](https://arxiv.org/abs/2604.22160)<br>
  *Eric Li, Arijit Dasgupta, Yoni Friedman, Mathieu Huot, Vikash Mansinghka, Thomas O'Connell, William T. Freeman, Joshua B. Tenenbaum*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **ParticleGS: Learning Neural Gaussian Particle Dynamics from Videos for Prior-free Physical Motion Extrapolation** [[Paper]](https://arxiv.org/abs/2505.20270)<br>
  *Jinsheng Quan, Qiaowei Miao, Yichao Xu, Zizhuo Lin, Ying Li, Wei Yang, Zhihui Li, Yawei Luo*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhysHO: Physics-Based Dynamic 3D Gaussian Human and Object from Monocular Video** [[Paper]](https://suezjiang.github.io/physho/)<br>
  *Suyi Jiang, Gim Hee Lee*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **UniPixie: Unified and Probabilistic 3D Physics Learning via Flow Matching** [[Paper]](https://arxiv.org/abs/2606.05399) [[Project]](https://unipixie.github.io/)<br>
  *Qilin Huang, Quynh Anh Huynh, Long Le, Chen Wang, Chuhao Chen, Ryan Lucas, Eric Eaton, Lingjie Liu*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **NeuIDO: Neural Intrinsic Dynamics Operator for Physics-Informed 4D World Models** [[Paper]](https://arxiv.org/abs/2609.24313)<br>
  *Jiajing Lin, Xin Zhang, Jianhua Sun*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhysConvex: Physics-Informed Dynamic Convex Fields for Reconstruction and Simulation** [[Paper]](https://arxiv.org/abs/2602.18886)<br>
  *Dan Wang, Xinrui Cui, Serge Belongie, Ravi Ramamoorthi*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **ReconPhys: Reconstruct Appearance and Physical Attributes from Single Video** [[Paper]](https://arxiv.org/abs/2604.07882)<br>
  *Boyuan Wang, Xiaofeng Wang, Yongkang Li, Zheng Zhu, Yifan Chang, Angen Ye, Guosheng Zhao, Chaojun Ni, Guan Huang, Yijie Ren, Yueqi Duan, Xingang Wang*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **MonoPhysics: Estimating Geometry, Appearance, and Physical Parameters from Monocular Videos** [[Paper]](https://neurips.cc/virtual/2026/poster/151413)<br>
  *Daniel Rho, Jun M Choi, Matthew Thornton, Biswadip Dey, Roni Sengupta*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **NEXUS: Neural Energy Fields for Physically Consistent Contact-Rich 3D Object Dynamics** [[Paper]](https://arxiv.org/abs/2606.15015)<br>
  *Qizhen Ying, Guangming Wang, Yangchen Pan, Victor Adrian Prisacariu, Brian Sheil, Yixiong Jing*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **PhyMo: Learning Physical Dynamics with Accurate and Continuous Motion from Multi-View Videos** [[Paper]](https://neurips.cc/virtual/2026/poster/154704)<br>
  *Shangjia Liu, Jinxi Li, Siyuan Zhou, Bo Yang, Bing Wang*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **PhysFormer: Learning to Simulate Mechanics in World Space** [[Paper]](https://neurips.cc/virtual/2026/poster/155354)<br>
  *Yiming Chen, Yushi Lan, Andrea Vedaldi*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions** [[Paper]](https://openreview.net/forum?id=Wj5qJnS1zW)<br>
  *Yu-Liang Zhan, Jian Li, Wenbing Huang, Yang Liu, Hao Sun*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **DiffWind: Physics-Informed Differentiable Modeling of Wind-Driven Object Dynamics** [[Paper]](https://openreview.net/forum?id=vKVzihkbQo)<br>
  *Yuanhang Lei, Boming Zhao, Zesong Yang, Xingxuan Li, Tao Cheng, Haocheng Peng, Ru Zhang, Yang Yang, Siyuan Huang, Yujun Shen, Ruizhen Hu, Hujun Bao, Zhaopeng Cui*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **Learning Physics-Grounded 4D Dynamics with Neural Gaussian Force Fields** [[Paper]](https://arxiv.org/abs/2602.00148)<br>
  *Shiqian Li, Ruihong Shen, Junfeng Ni, Chang Pan, Chi Zhang, Yixin Zhu*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **Learning 3D-Gaussian Simulators from RGB Videos** [[Paper]](https://openreview.net/forum?id=Icj19tWHI1)<br>
  *Mikel Zhobro, Andreas René Geist, Georg Martius*
- ![AAAI 2026](https://img.shields.io/badge/AAAI%202026-1f6feb?style=flat-square) 🔥 **Physics-Informed Deformable Gaussian Splatting: Towards Unified Constitutive Laws for Time-Evolving Material Field** [[Paper]](https://arxiv.org/abs/2511.06299)<br>
  *Haoqin Hong, Ding Fan, Fubin Dou, Zhi-Li Zhou, Haoran Sun, Congcong Zhu, Jingrun Chen*
- ![TMLR 2026](https://img.shields.io/badge/TMLR%202026-1f6feb?style=flat-square) 🔥 **Seeing is Simulating: Differentiable Physics for Interaction-Aware Material Estimation** [[Paper]](https://arxiv.org/abs/2603.06022)<br>
  *Chunjiang Liu, Xiaoyuan Wang, Qingran Lin, Albert Xiao, Haoyu Chen, Shizheng Wen, Hao Zhang, Lu Qi, Ming-Hsuan Yang, Laszlo A. Jeni, Min Xu, Yizhou Zhao*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **FreeGave: 3D Physics Learning from Dynamic Videos by Gaussian Velocity** [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_FreeGave_3D_Physics_Learning_from_Dynamic_Videos_by_Gaussian_Velocity_CVPR_2025_paper.html)<br>
  *Jinxi Li, Ziyang Song, Siyuan Zhou, Bo Yang*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **Vid2Sim: Generalizable, Video-based Reconstruction of Appearance, Geometry and Physics for Mesh-free Simulation** [[Paper]](https://arxiv.org/abs/2506.06440) [[Code]](https://czzzzh.github.io/Vid2Sim)<br>
  *Chuhao Chen, Zhiyang Dou, Chen Wang, Yiming Huang, Anjun Chen, Qiao Feng, Jiatao Gu, Lingjie Liu*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **PhysTwin: Physics-Informed Reconstruction and Simulation of Deformable Objects from Videos** [[Paper]](https://arxiv.org/abs/2503.17973)<br>
  *Hanxiao Jiang, Hao-Yu Hsu, Kaifeng Zhang, Hsin-Ni Yu, Shenlong Wang, Yunzhu Li*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **TRACE: Learning 3D Gaussian Physical Dynamics from Multi-view Videos** [[Paper]](https://arxiv.org/abs/2508.09811)<br>
  *Jinxi Li, Ziyang Song, Bo Yang*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **Gaussian-Augmented Physics Simulation and System Identification with Complex Colliders** [[Paper]](https://openreview.net/forum?id=hvykiwFiF8)<br>
  *Federico Vasile, Ri-Zhao Qiu, Lorenzo Natale, Xiaolong Wang*
- ![CVPR 2024](https://img.shields.io/badge/CVPR%202024-1f6feb?style=flat-square) 🔥 **Improving Physics-Augmented Continuum Neural Radiance Field-Based Geometry-Agnostic System Identification with Lagrangian Particle Optimization** [[Paper]](https://arxiv.org/abs/2406.04155)<br>
  *Takuhiro Kaneko*
- ![ECCV 2024](https://img.shields.io/badge/ECCV%202024-1f6feb?style=flat-square) 🔥 **Reconstruction and Simulation of Elastic Objects with Spring-Mass 3D Gaussians** [[Paper]](https://arxiv.org/abs/2403.09434)<br>
  *Licheng Zhong, Hong-Xing Yu, Jiajun Wu, Yunzhu Li*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **Gaussian-Informed Continuum for Physical Property Identification and Simulation** *(Oral)* [[Paper]](https://arxiv.org/abs/2406.14927)<br>
  *Junhao Cai, Yuji Yang, Weihao Yuan, Yisheng He, Zilong Dong, Liefeng Bo, Hui Cheng, Qifeng Chen*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **NeuMA: Neural Material Adaptor for Visual Grounding of Intrinsic Dynamics** [[Paper]](https://arxiv.org/abs/2410.08257)<br>
  *Junyi Cao, Shanyan Guan, Yanhao Ge, Wei Li, Xiaokang Yang, Chao Ma*
- ![CVPR 2026 Findings](https://img.shields.io/badge/CVPR%202026%20Findings-6c757d?style=flat-square) 🔥 **M-PhyGs: Multi-Material Object Dynamics from Video** [[Paper]](https://arxiv.org/abs/2512.16885)<br>
  *Norika Wada, Kohei Yamashita, Ryo Kawahara, Ko Nishino*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Analytic Dynamics: Learning Physics-Grounded Representation for Fast Intrinsic Dynamics Inference from Monocular Videos** [[Paper]](https://arxiv.org/abs/2608.31025)<br>
  *Jailing Lin, Jikuan Zhang, Jianhua Sun*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Learning Physics-Guided Residual Dynamics for Deformable Object Simulation** [[Paper]](https://arxiv.org/abs/2607.13451) [[Project]](https://pgrd-robot.github.io/)<br>
  *Shivansh Patel, Kaifeng Zhang, Sanjay Pokkali, Svetlana Lazebnik, Yunzhu Li*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysCoRe: Physics-Corrected Residual World Models for Material-Aware Deformable Dynamics** [[Paper]](https://arxiv.org/abs/2607.20653)<br>
  *Haocheng Yin, Shuohan Tao, Yongsheng Chen, Lu Gan*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **PhysWorld: From Real Videos to World Models of Deformable Objects via Physics-Aware Demonstration Synthesis** [[Paper]](https://arxiv.org/abs/2510.21447)<br>
  *Yu Yang, Zhilu Zhang, Xiang Zhang, Yihan Zeng, Hui Li, Wangmeng Zuo*

### Physics Distilled from Generative Priors

Material and motion are supplied by video diffusion models, LLMs, or VLMs instead of observed dynamics.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhysGM: Large Physical Gaussian Model for Feed-Forward 4D Synthesis** [[Paper]](https://arxiv.org/abs/2508.13911)<br>
  *Chunji Lv, Zequn Chen, Donglin Di, Weinan Zhang, Hao Li, Wei Chen, Yinjie Lei, Changsheng Li*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **Unleashing the Potential of Multi-modal Foundation Models and Video Diffusion for 4D Dynamic Physical Scene Simulation** [[Paper]](https://arxiv.org/abs/2411.14423) [[Code]](https://zhuomanliu.github.io/PhysFlow)<br>
  *Zhuoman Liu, Weicai Ye, Yan Luximon, Pengfei Wan, Di Zhang*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **GaussianProperty: Integrating Physical Properties to 3D Gaussians with LMMs** [[Paper]](https://arxiv.org/abs/2412.11258)<br>
  *Xinli Xu, Wenhang Ge, Dicong Qiu, ZhiFei Chen, Dongyu Yan, Zhuoyun Liu, Haoyu Zhao, Hanfeng Zhao, Shunsi Zhang, Junwei Liang, Ying-Cong Chen*
- ![ICLR 2025](https://img.shields.io/badge/ICLR%202025-1f6feb?style=flat-square) 🔥 **OmniPhysGS: 3D Constitutive Gaussians for General Physics-Based Dynamics Generation** [[Paper]](https://arxiv.org/abs/2501.18982)<br>
  *Yuchen Lin, Chenguo Lin, Jianjin Xu, Yadong MU*
- ![AAAI 2025](https://img.shields.io/badge/AAAI%202025-1f6feb?style=flat-square) 🔥 **DreamPhysics: Learning Physics-Based 3D Dynamics with Video Diffusion Priors** [[Paper]](https://arxiv.org/abs/2406.01476) [[Code]](https://github.com/tyhuang0428/DreamPhysics)<br>
  *Tianyu Huang, Haoze Zhang, Yihan Zeng, Zhilu Zhang, Hui Li, Wangmeng Zuo, Rynson W. H. Lau*
- ![ECCV 2024](https://img.shields.io/badge/ECCV%202024-1f6feb?style=flat-square) 🔥 **PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation** *(Oral)* [[Paper]](https://arxiv.org/abs/2404.13026)<br>
  *Tianyuan Zhang, Hong-Xing Yu, Rundi Wu, Brandon Y Feng, Changxi Zheng, Noah Snavely, Jiajun Wu, William T. Freeman*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **AgentDreamer: Agentic 3D Motion Reasoning for Text-Controllable Physics Simulation** [[Paper]](https://arxiv.org/abs/2610.30679) [[Code]](https://github.com/mjmjeong/AgentDreamer)<br>
  *Mijeong Kim, Suho Park, Junha Park, Bohyung Han*
- ![arXiv 2024](https://img.shields.io/badge/arXiv%202024-b31b1b?style=flat-square) 🔥 **Physics3D: Learning Physical Properties of 3D Gaussians via Video Diffusion** [[Paper]](https://arxiv.org/abs/2406.04338) [[Project]](https://liuff19.github.io/Physics3D/)<br>
  *Fangfu Liu, Hanyang Wang, Shunyu Yao, Shengjun Zhang, Jie Zhou, Yueqi Duan*
- ![arXiv 2024](https://img.shields.io/badge/arXiv%202024-b31b1b?style=flat-square) 🔥 **PhysMotion: Physics-Grounded Dynamics From a Single Image** [[Paper]](https://arxiv.org/abs/2411.17189) [[Project]](https://supertan0204.github.io/physmotion_website/)<br>
  *Xiyang Tan, Ying Jiang, Xuan Li, Zeshun Zong, Tianyi Xie, Yin Yang, Chenfanfu Jiang*

### Physics-Aware 4D Scene Generation

Generation of dynamic 3D scenes (multi-object, long-horizon, or action-conditioned) with physical interaction.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Choreographing a World of Dynamic Objects** [[Paper]](https://arxiv.org/abs/2601.04194)<br>
  *Yanzhe Lyu, Chen Geng, Karthik Dharmarajan, Yunzhi Zhang, Hadi Alzayer, Shangzhe Wu, Jiajun Wu*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PerpetualWonder: Long-horizon Action-conditioned 4D Scene Generation** [[Paper]](https://arxiv.org/abs/2602.04876)<br>
  *Jiahao Zhan, Zizhang Li, Hong-Xing Yu, Jiajun Wu*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **SeeU: Seeing the Unseen World via 4D Dynamics-aware Generation** [[Paper]](https://arxiv.org/abs/2512.03350)<br>
  *Yu Yuan, Tharindu Wickremasinghe, Zeeshan Nadir, Xijun Wang, Yiheng Chi, Stanley H. Chan*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **CP4D: Compositional Physics-aware 4D Scene Generation** [[Paper]](https://arxiv.org/abs/2606.09187)<br>
  *Hanxin Zhu, Cong Wang, Tianyu He, Long Chen, Xin Jin, Chen Gao, Zhibo Chen*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **GS-Agent: Creating 4D Physical Worlds With Generative Simulation** [[Paper]](https://arxiv.org/abs/2607.21522)<br>
  *Hongxin Zhang, Chunru Lin, Junyan Li, Zhou Xian, Tsun-Hsuan Wang, Chuang Gan*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Phys4D: Fine-Grained Physics-Consistent 4D Modeling from Video Diffusion** [[Paper]](https://arxiv.org/abs/2603.03485)<br>
  *Haoran Lu, Shang Wu, Songling Liu, Jianshu Zhang, Maojiang Su, Guo Ye, Chenwei Xu, Lie Lu, Pranav Maneriker, Fan Du, Zhaoran Wang, Han Liu*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Resonance4D: Frequency-Domain Motion Supervision for Preset-Free Physical Parameter Learning in 4D Dynamic Physical Scene Simulation** [[Paper]](https://arxiv.org/abs/2604.01994)<br>
  *Changshe Zhang, Jie Feng, Siyu Chen, Guanbin Li, Ronghua Shang, Junpeng Zhang*
- ![arXiv 2024](https://img.shields.io/badge/arXiv%202024-b31b1b?style=flat-square) 🔥 **Phy124: Fast Physics-Driven 4D Content Generation from a Single Image** [[Paper]](https://arxiv.org/abs/2409.07179)<br>
  *Jiajing Lin, Zhenzhong Wang, Yongjie Hou, Yuzhou Tang, Min Jiang*
- ![arXiv 2024](https://img.shields.io/badge/arXiv%202024-b31b1b?style=flat-square) 🔥 **Phys4DGen: A Physics-Driven Framework for Controllable and Efficient 4D Content Generation from a Single Image** [[Paper]](https://arxiv.org/abs/2411.16800) [[Code]](https://github.com/JiajingLin/Phys4DGen)<br>
  *Jiajing Lin, Zhenzhong Wang, Dejun Xu, Shu Jiang, YunPeng Gong, Min Jiang*
- ![arXiv 2024](https://img.shields.io/badge/arXiv%202024-b31b1b?style=flat-square) 🔥 **Trans4D: Realistic Geometry-Aware Transition for Compositional Text-to-4D Synthesis** [[Paper]](https://arxiv.org/abs/2410.07155)<br>
  *Bohan Zeng, Ling Yang, Siyu Li, Jiaming Liu, Zixiang Zhang, Juanxi Tian, Kaixin Zhu, Yongzhen Guo, Fu-Yun Wang, Minkai Xu, Stefano Ermon, Wentao Zhang*

### Fluids, Fire, Weather and Other Phenomena

Natural phenomena that require dedicated solvers or priors.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Let it Snow! Animating 3D Gaussian Scenes with Dynamic Weather Effects via Physics-Guided Score Distillation** [[Paper]](https://arxiv.org/abs/2504.05296)<br>
  *Gal Fiebelman, Hadar Averbuch-Elor, Sagie Benaim*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **SmokeSVD: Smoke Reconstruction from A Single View via Progressive Novel View Synthesis and Refinement with Diffusion Models** *(Oral)* [[Paper]](https://arxiv.org/abs/2507.12156)<br>
  *Chen Li, Shanshan Dong, Sheng Qiu, Jianmin Han, Yibo Zhao, Zan Gao, Taku Komura, Kemeng Huang*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **FieryGS: In-the-Wild Fire Synthesis with Physics-Integrated Gaussian Splatting** [[Paper]](https://openreview.net/forum?id=ziKFH7whvy)<br>
  *Qianfan Shen, Ningxiao Tao, Qiyu Dai, Tianle Chen, Minghan Qin, Yongjie Zhang, Mengyu Chu, Wenzheng Chen, Baoquan Chen*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **FluidNexus: 3D Fluid Reconstruction and Prediction from a Single Video** [[Paper]](https://arxiv.org/abs/2503.04720)<br>
  *Yue Gao, Hong-Xing Yu, Bo Zhu, Jiajun Wu*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **RainyGS: Efficient Rain Synthesis with Physically-Based Gaussian Splatting** [[Paper]](https://arxiv.org/abs/2503.21442)<br>
  *Qiyu Dai, Xingyu Ni, Qianfan Shen, Wenzheng Chen, Baoquan Chen, Mengyu Chu*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Vid2Fluid: 3D Dynamic Fluid Assets from Single-View Videos with Generative Gaussian Splatting** [[Paper]](https://arxiv.org/abs/2503.00868)<br>
  *Zhiwei Zhao, Yin Zhao, Minchen Li, Yixin Hu*

[⬆ Back to top](#contents)

## Physics-Aware Video Generation

Organized by how physics enters the video generator.

### Simulation-in-the-Loop and Explicit Dynamics

An explicit simulator or a learned dynamics module produces the motion, and the video model renders it.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **NS-Diff: Fluid Navier-Stokes Guided Video Diffusion via Reinforcement Learning** [[Paper]](https://cvpr.thecvf.com/virtual/2026/poster/36346)<br>
  *Zijun Deng, Yuxin Peng*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Physical Simulator In-the-Loop Video Generation** [[Paper]](https://arxiv.org/abs/2603.06408)<br>
  *Lin Geng Foo, Mark He Huang, Alexandros Lattas, Stylianos Moschoglou, Thabo Beeler, Christian Theobalt*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **KineMask: Learning to Generate Rigid Body Interactions with Video Diffusion Models** [[Paper]](https://arxiv.org/abs/2510.02284) [[Project]](https://daromog.github.io/KineMask)<br>
  *David Romero, Ariana Bermudez, Viacheslav Iablochnikov, Hao Li, Fabio Pizzati, Ivan Laptev*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhysChoreo: Physics-Controllable Video Generation with Part-Aware Semantic Grounding** [[Paper]](https://arxiv.org/abs/2511.20562)<br>
  *Haoze Zhang, Tianyu Huang, Zichen Wan, Xiaowei Jin, Hongzhi Zhang, Hui Li, Wangmeng Zuo*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **NewtonGen: Physics-consistent and Controllable Text-to-Video Generation via Neural Newtonian Dynamics** [[Paper]](https://arxiv.org/abs/2509.21309)<br>
  *Yu Yuan, Xijun Wang, Tharindu Wickremasinghe, Zeeshan Nadir, Bole Ma, Stanley H. Chan*
- ![SIGGRAPH Asia 2026](https://img.shields.io/badge/SIGGRAPH%20Asia%202026-1f6feb?style=flat-square) 🔥 **VDAWorld: World Modelling via VLM-Directed Abstraction and Simulation** [[Paper]](https://arxiv.org/abs/2512.11061) [[Project]](https://felixomahony.github.io/vdaworld/) [[Code]](https://github.com/ayushtewari/VDAWorld)<br>
  *Felix O'Mahony, Roberto Cipolla, Ayush Tewari*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **PhysAnimator: Physics-Guided Generative Cartoon Animation** [[Paper]](https://arxiv.org/abs/2501.16550)<br>
  *Tianyi Xie, Yiwei Zhao, Ying Jiang, Chenfanfu Jiang*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **Learning an Implicit Physics Model for Image-based Fluid Simulation** [[Paper]](https://arxiv.org/abs/2508.08254)<br>
  *Emily Yue-Ting Jia, Jiageng Mao, Zhiyuan Gao, Yajie Zhao, Yue Wang*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **PhysCtrl: Generative Physics for Controllable and Physics-Grounded Video Generation** [[Paper]](https://arxiv.org/abs/2509.20358)<br>
  *Chen Wang, Chuhao Chen, Yiming Huang, Zhiyang Dou, Yuan Liu, Jiatao Gu, Lingjie Liu*
- ![CVPR 2024](https://img.shields.io/badge/CVPR%202024-1f6feb?style=flat-square) 🔥 **Generative Image Dynamics** [[Paper]](https://arxiv.org/abs/2309.07906)<br>
  *Zhengqi Li, Richard Tucker, Noah Snavely, Aleksander Holynski*
- ![ECCV 2024](https://img.shields.io/badge/ECCV%202024-1f6feb?style=flat-square) 🔥 **PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation** [[Paper]](https://arxiv.org/abs/2409.18964)<br>
  *Shaowei Liu, Zhongzheng Ren, Saurabh Gupta, Shenlong Wang*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **MotionCraft: Physics-Based Zero-Shot Video Generation** [[Paper]](https://arxiv.org/abs/2405.13557)<br>
  *Antonio Montanaro, Luca Savant Aira, Emanuele Aiello, Diego Valsesia, Enrico Magli*
- ![ACM MM 2024](https://img.shields.io/badge/ACM%20MM%202024-1f6feb?style=flat-square) 🔥 **ANFluid: Animate Natural Fluid Photos base on Physics-Aware Simulation and Dual-Flow Texture Learning** [[Paper]](https://initialmoon.github.io/publications/anfluid/)<br>
  *Xiangcheng Zhai, Yingqi Jie, Xueguang Xie, Aimin Hao, Na Jiang, Yang Gao*
- ![SIGGRAPH 2025 Poster](https://img.shields.io/badge/SIGGRAPH%202025%20Poster-6c757d?style=flat-square) 🔥 **Sketch-based Fluid Video Generation Using Motion-Guided Diffusion Models in Still Landscape Images** [[Paper]](https://arxiv.org/abs/2510.15874)<br>
  *Hao Jin, Haoran Xie*
- ![Preprint 2026](https://img.shields.io/badge/Preprint%202026-b31b1b?style=flat-square) 🔥 **Counterfactual Simulation-Guided Physical Reasoning for Physics-Based Video Generation** [[Paper]](https://scholar.google.com/scholar?q=%22Counterfactual+Simulation-Guided+Physical+Reasoning+for+Physics-Based+Video+Generation%22)<br>
  *Authors not yet public*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **IMPACT: Image-Conditioned Motion with Physics-Aware Collision and Trajectory Guidance for Video Generation** [[Paper]](https://arxiv.org/abs/2611.01372)<br>
  *Shiwei Yang, Yunlong Yu, Zhao Wang, Jungong Han*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhyRPR: Training-Free Physics-Constrained Video Generation** [[Paper]](https://arxiv.org/abs/2601.09255)<br>
  *Yibo Zhao, Hengjia Li, Xiaofei He, Boxi Wu*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysLoop: Harnessing LLMs' Physics Awareness for Self-Improving Video Generation Models** [[Paper]](https://arxiv.org/abs/2611.16748) [[Project]](https://chenyx24.github.io/PhysLoop-site/) [[Code]](https://github.com/DAGroup-PKU/PhysLoop)<br>
  *Yuxuan Chen, Xiaojie Li, Hao Chen, Juncheng Ma, Kewei Zhang, Zhongjing Du, Guoqiang Wei, Fangfang Wang, Zhen Dong, Zhiyang Dou, Liming Zhao, Yan Zeng, Jianwei Zhang, Daquan Zhou*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **RealWonder: Real-Time Physical Action-Conditioned Video Generation** [[Paper]](https://arxiv.org/abs/2603.05449)<br>
  *Wei Liu, Ziyu Chen, Zizhang Li, Yue Wang, Hong-Xing Yu, Jiajun Wu*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Physics-Grounded Motion Forecasting via Equation Discovery for Trajectory-Guided Image-to-Video Generation** [[Paper]](https://arxiv.org/abs/2507.06830)<br>
  *Tao Feng, Xianbing Zhao, Zhenhua Chen, Tien Tsin Wong, Hamid Rezatofighi, Gholamreza Haffari, Lizhen Qu*

### Physical Control Signals

The generator is conditioned on forces, physical parameters, or physics-derived flow.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **GoalForce: Teaching Video Models to Accomplish Physics-Conditioned Goals** [[Paper]](https://arxiv.org/abs/2601.05848)<br>
  *Nate Gillman, Yinghua Zhou, Zitian Tang, Evan Luo, Arjan Chakravarthy, Daksh Aggarwal, Michael Freeman, Charles Herrmann, Chen Sun*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhyCo: Learning Controllable Physical Priors for Generative Motion** [[Paper]](https://arxiv.org/abs/2604.28169)<br>
  *Sriram Narayanan, Ziyu Jiang, Srinivasa Narasimhan, Manmohan Chandraker*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **Force Prompting: Video Generation Models Can Learn and Generalize Physics-based Control Signals** [[Paper]](https://arxiv.org/abs/2505.19386)<br>
  *Nate Gillman, Charles Herrmann, Michael Freeman, Daksh Aggarwal, Evan Luo, Deqing Sun, Chen Sun*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Learning Explicit Physical Parameter Control and Benchmarking for Video Generation** [[Paper]](https://arxiv.org/abs/2607.18924)<br>
  *Yanxun Li, Hao Wen, Bingze Song, Jiashu Zhu, Aiming Hao, Chubin Chen, Jintao Chen, Jiahong Wu, Xiangxiang Chu, Miao Wang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysFlow: Physics-Aware Optical Flow for Motion Controllable Video Generation** [[Paper]](https://arxiv.org/abs/2609.08215)<br>
  *Cong Wang, Hanxin Zhu, Yonglin Tian, Jiayi Luo, Ruiqi Song, Boyi Sun, Long Chen, Zhibo Chen*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysStream: Streaming Physics-Grounded Video Generation with Structured Scene Memory and Fine-Grained Motion Control** [[Paper]](https://arxiv.org/abs/2609.17521)<br>
  *Chuhao Chen, Peter Wonka, Chaoyang Wang, Chen Wang, Qiao Feng, Sergey Tulyakov, Lingjie Liu*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **StreamForce: Streaming Video Generation with Streaming Force Control** [[Paper]](https://arxiv.org/abs/2606.07508) [[Project]](https://neu-vi.github.io/StreamForce/)<br>
  *Hanhui Wang, Yiming Xie, Haiwen Feng, Zhaoyang Lv, Shenlong Wang, Huaizu Jiang*

### LLM/VLM Reasoning and Agentic Planning

A language or vision-language model reasons about the physical process (plans, keyframes, trajectories, retrieved exemplars, code) before or during generation.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Chain of Event-Centric Causal Thought for Physically Plausible Video Generation** [[Paper]](https://arxiv.org/abs/2603.09094)<br>
  *Zixuan Wang, Yixin Hu, Haolan Wang, Feng Chen, Yan Liu, Wen Li, Yinjie Lei*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **MoReGen: Multi-Agent Motion-Reasoning Engine for Code-based Text-to-Video Synthesis** [[Paper]](https://arxiv.org/abs/2512.04221)<br>
  *Xiangyu Bai, He Liang, Bishoy Galoaa, Utsav Nandi, Shayda Moezzi, Yuhang He, Sarah Ostadabbas*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **DeforM: Reasoning-Guided Physics-Aware Video Generation via Spatial-Temporal Masking** [[Paper]](https://arxiv.org/abs/2607.18664)<br>
  *Yunyi Li, Yu Qiao, Yaohui Wang, Xinyuan Chen*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhyMAGIC: Physical Motion-Aware Generative Inference with Confidence-guided VLM** ⭐ **Ours** [[Paper]](https://arxiv.org/abs/2505.16456)<br>
  *Siwei Meng, Yawei Luo, Ping Liu*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhysRAG: Enhancing Physics-Awareness in Video Generation via Retrieval-Augmented Generation** [[Paper]](https://arxiv.org/abs/2606.26916)<br>
  *Kexu Cheng, Zicheng Liu, Mingju Gao, Chunhe Song, Hao Tang*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **PhyT2V: LLM-Guided Iterative Self-Refinement for Physics-Grounded Text-to-Video Generation** [[Paper]](https://arxiv.org/abs/2412.00596)<br>
  *Qiyao Xue, Xiangyu Yin, Boyuan Yang, Wei Gao*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **VLIPP: Towards Physically Plausible Video Generation with Vision and Language Informed Physical Prior** [[Paper]](https://arxiv.org/abs/2503.23368)<br>
  *Xindi Yang, Baolu Li, Yiming Zhang, Zhenfei Yin, Lei Bai, Liqian Ma, Zhiyong Wang, Jianfei Cai, Tien-Tsin Wong, Huchuan Lu, Xu Jia*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Agentic Physics-Grounded Video Generation via Memory-Augmented In-Context Reasoning** [[Paper]](https://arxiv.org/abs/2610.23677) [[Code]](https://github.com/xxkkxxx/PhysRepair)<br>
  *Xikang Guan, Shaocong Yang, Yanqi Bao, Can Wang, Zheng Gu, Zhengqing Chen, Kai Chen, Jing Huo, Yang Gao*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **CausalMotion: Structured Physical Reasoning as Keyframe and Trajectory Guidance for Training-Free Video Generation** [[Paper]](https://arxiv.org/abs/2606.14317) [[Project]](https://zhuangsh0713.github.io/CausalMotion/)<br>
  *Sihan Zhuang, Xinyuan Chen, Tianfan Xue, Yaohui Wang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **K2V: Generative Keyframing For Physically Plausible Video Generation** [[Paper]](https://arxiv.org/abs/2611.17324)<br>
  *Felix O'Mahony, Daniel Olmeda Reino, Roberto Cipolla, Ayush Tewari*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **NEWTON: Agentic Planning for Physically Grounded Video Generation** [[Paper]](https://arxiv.org/abs/2605.18396)<br>
  *Yuxiang Feng, Juncheng Wang, Chao Xu, Yijie Qian, Huihan Wang, Wenlong Hou, Yang Liu, Baigui Sun, Yong Liu, Shujun Wang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhyEvolve: Multi-Agent State-Evolution Planning for Physics-Aware Video Generation** [[Paper]](https://arxiv.org/abs/2610.30717) [[Code]](https://github.com/PhyEvolve/PhyEvolve)<br>
  *Yang-Hao Zhou, Lixing Tan, Zhiqi Li, Guang Yang, Xiao Yang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhyPrompt: RL-based Prompt Refinement for Physically Plausible Text-to-Video Generation** [[Paper]](https://arxiv.org/abs/2603.03505)<br>
  *Shang Wu, Chenwei Xu, Zhuofan Xia, Weijian Li, Lie Lu, Pranav Maneriker, Fan Du, Manling Li, Han Liu*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysAgent: Reflective Agentic Physics Control for Physically Plausible Video Generation** [[Paper]](https://arxiv.org/abs/2607.16355)<br>
  *Qirui Li, Jinkun Hao, Yibo Li, Ran Yi, Paul L. Rosin, Yu-Kun Lai*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Physics-Aware Video Generation via Agentic Planning and Graph-Guided Optimization** [[Paper]](https://arxiv.org/abs/2609.13006)<br>
  *Minh-Loi Nguyen, Xuan-Vu Le, Trung-Nghia Le, Tam V. Nguyen, Minh-Triet Tran, Thanh-Toan Do*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysMRV: Physical Memory Retrieval and Verification for Physics Plausibility Reasoning** [[Paper]](https://arxiv.org/abs/2607.10190)<br>
  *Wenyuan Wang, Lianyu Hu, Hao Wang, Yang Liu*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **VideoCoCo: Code-as-CoT for Physically-Consistent Video Generation via an Agentic Dual-Engine System** [[Paper]](https://arxiv.org/abs/2607.27380)<br>
  *Haodong Li, Tianfei Ren, Xiaoxiao Ma, Chunmei Qing, Zhen Fang, Sipeng He, Ziyu Guo, Haoyu Wu, Juanxi Tian, Yihang Zou, Ruichuan An, Dongzhi Jiang, Boxue Yang, Ji Xie, Xu Huang, Wenhao Yan, Jialv Zou, Zhengrong Yue, Yaxin Luo, Xiaotong Li, Yuzhu Wang, Junyan Ye, Jinjing Zhao, Zehui Chen, Lin Chen, Renye Yan, Feng Zhao, Pheng-Ann Heng*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **VIPER: Visual In-Context Physics Reasoning for Physically Plausible Video Generation** [[Paper]](https://arxiv.org/abs/2607.23472)<br>
  *Tianxiao Chen, Hanmo Chen, Huajin Chen, Bo Li, Qi Ye, Peng-Tao Jiang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Enhancing Physical Plausibility in Video Generation by Reasoning the Implausibility** [[Paper]](https://arxiv.org/abs/2509.24702)<br>
  *Yutong Hao, Chen Chen, Ajmal Saeed Mian, Chang Xu, Daochang Liu*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Planning with Sketch-Guided Verification for Physics-Aware Video Generation** [[Paper]](https://arxiv.org/abs/2511.17450)<br>
  *Yidong Huang, Zun Wang, Han Lin, Dong-Ki Kim, Shayegan Omidshafiei, Jaehong Yoon, Yue Zhang, Mohit Bansal*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Think Before You Diffuse: LLMs-Guided Physics-Aware Video Generation** [[Paper]](https://arxiv.org/abs/2505.21653)<br>
  *Ke Zhang, Cihan Xiao, Jiacong Xu, Yiqun Mei, Vishal M. Patel*

### Physics-Aware Representations, Objectives and Data

The generator itself is trained with physics-related representation alignment, auxiliary modalities, losses, or synthetic data.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Phantom: Physics-Infused Video Generation via Joint Modeling of Visual and Latent Physical Dynamics** [[Paper]](https://arxiv.org/abs/2604.08503)<br>
  *Ying Shen, Jerry Xiong, Tianjiao Yu, Ismini Lourentzou*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhysVid: Physics Aware Local Conditioning for Generative Video Models** [[Paper]](https://arxiv.org/abs/2603.26285)<br>
  *Saurabh Pathak, Elahe Arani, Mykola Pechenizkiy, Bahram Zonooz*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **ProPhy: Progressive Physical Alignment for Dynamic World Simulation** [[Paper]](https://arxiv.org/abs/2512.05564)<br>
  *Zijun Wang, Panwen Hu, Jing Wang, Terry Jingchen Zhang, Yuhao Cheng, Long Chen, Yiqiang Yan, Zutao Jiang, Hanhui Li, Xiaodan Liang*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **UnityVideo: Unified Multi-Modal Multi-Task Learning for Enhancing World-Aware Video Generation** [[Paper]](https://arxiv.org/abs/2512.07831)<br>
  *Jiehui Huang, Yuechen Zhang, Xu He, Yuan Gao, Zhi Cen, Bin Xia, Yan Zhou, Xin Tao, Pengfei Wan, Jiaya Jia*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhysAlign: Learning Physical Priors for Dynamical Event-Driven Video Generation via Representation Alignment** [[Paper]](https://link.springer.com/chapter/10.1007/978-3-032-37464-6_28) [[Code]](https://github.com/FanQi-AI/PhysAlign)<br>
  *Mengxian Li, Zhan Wang, Fan Qi, Changsheng Xu*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **Predictive Structure Improves Video Diffusion Dynamics** [[Paper]](https://vision.cs.utexas.edu/projects/ldo)<br>
  *Romy Mi Luo, Yujia Chen, Alex Dimakis, Kristen Grauman, Wen-Sheng Chu, Du Tran*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **HiPhy: Hierarchical Alignment for Physically-Plausible Multi-Principle Video Generation** [[Paper]](https://neurips.cc/virtual/2026/poster/150284)<br>
  *Tahira Kazimi, Shubhankar Borse, Munawar Hayat, Fatih Porikli, Pinar Yanardag*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **Physics-Informed Video Generation via Mixture-of-Experts Latent Alignment** [[Paper]](https://neurips.cc/virtual/2026/poster/155222)<br>
  *Cong Wang, Hanxin Zhu, Jiayi Luo, Yonglin Tian, Xiaoqian Cheng, Peiyan Tu, Xin Jin, Long Chen, Zhibo Chen*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **Seeing the Unseen: Unified Visible-Invisible Motion for Physically Consistent Video Generation** [[Paper]](https://neurips.cc/virtual/2026/poster/149881)<br>
  *Mingyang Bao, Fangda Ye, Xihao Chen, Bobo Li, Xiangtai Li, Shengqiong Wu*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **Physics-Guided Motion Loss for Video Generation Model** [[Paper]](https://arxiv.org/abs/2506.02244)<br>
  *Bowen Xue, Giuseppe Claudio Guarnera, Shuang Zhao, Zahra Montazeri*
- ![ICCV 2025](https://img.shields.io/badge/ICCV%202025-1f6feb?style=flat-square) 🔥 **Synthetic Video Enhances Physical Fidelity in Video Synthesis** [[Paper]](https://arxiv.org/abs/2503.20822)<br>
  *Qi Zhao, Xingyu Ni, Ziyu Wang, Feng Cheng, Ziyan Yang, Lu Jiang, Bohan Wang*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **GeoVideo: Introducing Geometric Regularization into Video Generation Model** [[Paper]](https://openreview.net/forum?id=be6u40gq0Y)<br>
  *Yunpeng Bai, Shaoheng Fang, Chaohui Yu, Fan Wang, Qixing Huang*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **Towards Physical Understanding in Video Generation: A 3D Point Regularization Approach** [[Paper]](https://arxiv.org/abs/2502.03639)<br>
  *Yunuo Chen, Junli Cao, Vidit Goel, Sergei Korolev, Chenfanfu Jiang, Jian Ren, Sergey Tulyakov, Anil Kag*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **VideoREPA: Learning Physics for Video Generation through Relational Alignment with Foundation Models** [[Paper]](https://arxiv.org/abs/2505.23656)<br>
  *Xiangdong Zhang, Jiaqi Liao, Shaofeng Zhang, Fanqing Meng, Xiangpeng Wan, Junchi Yan, Yu Cheng*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **WISA: World Simulator Assistant for Physics-Aware Text-to-Video Generation** *(Spotlight)* [[Paper]](https://arxiv.org/abs/2503.08153)<br>
  *Jing Wang, Ao Ma, Ke Cao, Jun Zheng, Jiasong Feng, Zhanjie Zhang, Wanyuan Pang, Xiaodan Liang*
- ![ICML 2025](https://img.shields.io/badge/ICML%202025-1f6feb?style=flat-square) 🔥 **VideoJAM: Joint Appearance-Motion Representations for Enhanced Motion Generation in Video Models** *(Oral)* [[Paper]](https://arxiv.org/abs/2502.02492)<br>
  *Hila Chefer, Uriel Singer, Amit Zohar, Yuval Kirstain, Adam Polyak, Yaniv Taigman, Lior Wolf, Shelly Sheynin*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **CompAdapt: Adaptable Composite Motion Modeling for Physics-Consistent Text-to-Video Generation** [[Paper]](https://arxiv.org/abs/2609.21455)<br>
  *Haoran Qin, Renlong Wu, Tianyu Huang, Yukang Ding, Hui Li, Wangmeng Zuo*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Enhancing Video Physical Consistency via Role-aware Joint Training and Modality-decoupled Denoising** [[Paper]](https://arxiv.org/abs/2607.04653)<br>
  *Guangting Zheng, Haojing Chen, Hao Li, Jingtao Zhang, Zhen Yang, Xiaosong Jia, Xue Yang, Shaofeng Zhang, Yanyong Zhang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **LaMo: Self-Supervised Latent Motion Priors for Physical Realism in Video Generation** [[Paper]](https://arxiv.org/abs/2605.23878) [[Project]](https://lamo-ai.github.io/)<br>
  *Bo Jiang, Depu Meng, Yihan Hu, Yichen Xie, Tianshuo Xu, Wei Zhan*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **MiMaAlign: Hierarchical Micro-Macro Alignment for Physically Plausible Video Generation** [[Paper]](https://arxiv.org/abs/2610.16482)<br>
  *Yansong Liu, Litong Gong, Weijie Li, Tiezheng Ge, Ming Zeng*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **MMPhysVideo: Physically Plausible Video Generation Through Joint RGB-Perception Modeling** [[Paper]](https://arxiv.org/abs/2604.02817)<br>
  *Shubo Lin, Xuanyang Zhang, Wei Cheng, Weiming Hu, Gang Yu, Jin Gao*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Phase-Aware Video Generation for Physics-Grounded Dynamics and Interactions** [[Paper]](https://arxiv.org/abs/2610.11791)<br>
  *Jingfeng Ou, Kun Wang, Rui Zhao, Jingwei Guan, Limin Wang, Chao Dong, Xingyu Zeng*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysAlign: Physics-Coherent Image-to-Video Generation through Feature and 3D Representation Alignment** [[Paper]](https://arxiv.org/abs/2603.13770)<br>
  *Zhexiao Xiong, Yizhi Song, Liu He, Wei Xiong, Yu Yuan, Feng Qiao, Nathan Jacobs*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysVideo: Physically Plausible Video Generation with Cross-View Geometry Guidance** [[Paper]](https://arxiv.org/abs/2603.18639)<br>
  *Cong Wang, Hanxin Zhu, Xiao Tang, Jiayi Luo, Xin Jin, Long Chen, Zhibo Chen*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Tempered Self-Similarity Alignment for Physically Plausible Video Generation** [[Paper]](https://arxiv.org/abs/2605.24962)<br>
  *Manjin Kim, Suha Kwak, Minsu Cho*

### Post-Training with Physics Rewards, Preferences and RL

Fine-tuning with physics-aware rewards, preference optimization (DPO and variants), or reinforcement learning.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **DynamicsBoost: Dynamic Plausible Video Generation via Annotation-Free Continuation Preference Optimization** [[Paper]](https://cvpr.thecvf.com/virtual/2026/poster/38615)<br>
  *Jiaxing Li, Jiepeng Wang, Junyao Gao, Yang Liu, Eric Li, Bo An, Hao-Xiang Guo*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhyGDPO: Physics-Aware Groupwise Direct Preference Optimization for Physically Consistent Text-to-Video Generation** [[Paper]](https://arxiv.org/abs/2512.24551)<br>
  *Yuanhao Cai, Kunpeng Li, Menglin Jia, Jialiang Wang, Junzhe Sun, Feng Liang, Weifeng Chen, Felix Juefei-Xu, Chu Wang, Ali Thabet, Xiaoliang Dai, Xuan Ju, Alan Yuille, Ji Hou*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhysPO: Physics-Aware Local Preference Optimization for Physically Consistent Video Generation** [[Paper]](https://shanpoyang654.github.io/PhysPO/page.html)<br>
  *Authors not yet public*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhysRVG: Physics-Aware Unified Reinforcement Learning for Video Generative Models** [[Paper]](https://arxiv.org/abs/2601.11087)<br>
  *Qiyuan Zhang, Biao Gong, Shuai Tan, Zheng Zhang, Yujun Shen, Xing Zhu, Yuyuan Li, Kelu Yao, Chunhua Shen, Changqing Zou*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **SIFT: Self-Imagination Fine-Tuning for Physically Plausible Motion in Video Diffusion Models** [[Paper]](https://arxiv.org/abs/2606.27741)<br>
  *Ruoyu Wang, Jialun Liu, Huayang Huang, Haibin Huang, Jiepeng Wang, Chi Zhang, Xuelong Li, Yu Wu*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **PhyMotion: Structured 3D Motion Reward for Physics-Grounded Human Video Generation** [[Paper]](https://neurips.cc/virtual/2026/poster/149085)<br>
  *Yidong Huang, Zun Wang, Han Lin, Dong-Ki Kim, Shayegan Omidshafiei, Jaehong Yoon, Jaemin Cho, Yue Zhang, Mohit Bansal*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **World-R1: Reinforcing 3D Constraints for Text-to-Video Generation** [[Paper]](https://openreview.net/forum?id=lh0I4rB0I5)<br>
  *Weijie Wang, Xiaoxuan He, Youping Gu, Yifan Yang, Zeyu Zhang, Yefei He, Yanbo Ding, Xirui Hu, Donny Y. Chen, Zhiyuan He, Yuqing Yang, Bohan Zhuang*
- ![ACM MM 2026](https://img.shields.io/badge/ACM%20MM%202026-1f6feb?style=flat-square) 🔥 **When Physical Preferences Meet Semantic Constraints: Physical and Semantic Direct Preference Optimization for Text-to-Video Generation** *(Oral, Outstanding Paper Award)* ⭐ **Ours** [[Paper]](https://arxiv.org/abs/2607.16947)<br>
  *Siwei Meng, Yawei Luo, Shu Zhang, Ping Liu*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **Hierarchical Fine-grained Preference Optimization for Physically Plausible Video Generation** [[Paper]](https://arxiv.org/abs/2508.10858)<br>
  *Harold Haodong Chen, Haojian Huang, Qifeng Chen, Harry Yang, Ser-Nam Lim*
- ![ICML 2025](https://img.shields.io/badge/ICML%202025-1f6feb?style=flat-square) 🔥 **PISA Experiments: Exploring Physics Post-Training for Video Diffusion Models by Watching Stuff Drop** [[Paper]](https://arxiv.org/abs/2503.09595)<br>
  *Chenyu Li, Oscar Michel, Xichen Pan, Sainan Liu, Mike Roberts, Saining Xie*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **DiReCT: Disentangled Regularization of Contrastive Trajectories for Physics-Refined Video Generation** [[Paper]](https://arxiv.org/abs/2603.25931)<br>
  *Abolfazl Meyarian, Amin Karimi Monsefi, Rajiv Ramnath, Ser-Nam Lim*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **PhysCorr: Dual-Reward DPO for Physics-Constrained Text-to-Video Generation with Automated Preference Selection** [[Paper]](https://arxiv.org/abs/2511.03997)<br>
  *Peiyao Wang, Weining Wang, Qi Li*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **PhysMaster: Mastering Physical Representation for Video Generation via Reinforcement Learning** [[Paper]](https://arxiv.org/abs/2510.13809)<br>
  *Sihui Ji, Xi Chen, Xin Tao, Pengfei Wan, Hengshuang Zhao*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **RDPO: Real Data Preference Optimization for Physics Consistency Video Generation** [[Paper]](https://arxiv.org/abs/2506.18655)<br>
  *Wenxu Qian, Chaoyue Wang, Hou Peng, Zhiyu Tan, Hao Li, Anxiang Zeng*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Reasoning Physical Video Generation with Diffusion Timestep Tokens via Reinforcement Learning** [[Paper]](https://arxiv.org/abs/2504.15932)<br>
  *Wang Lin, Liyu Jia, Wentao Hu, Kaihang Pan, Zhongqi Yue, Wei Zhao, Jingyuan Chen, Fei Wu, Hanwang Zhang*

### Inference-Time Guidance and Refinement

Training-free steering at sampling time: noise selection, guidance, scoring, or optimal control.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Inference-time Physics Alignment of Video Generative Models with Latent World Models** [[Paper]](https://arxiv.org/abs/2601.10553)<br>
  *Jianhao Yuan, Xiaofeng Zhang, Felix Friedrich, Nicolas Beltran-Velez, Melissa Hall, Reyhane Askari-Hemmat, Xiaochuang Han, Nicolas Ballas, Michal Drozdzal, Adriana Romero-Soriano*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **LINA: Learning INterventions Adaptively for Physical Alignment and Generalization in Diffusion Models** [[Paper]](https://arxiv.org/abs/2512.13290) [[Code]](https://github.com/opencausalab/lina)<br>
  *Shu Yu, Chaochao Lu*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **OptiWorld: Optimal Control for Video World Generation under Physical Constraints** [[Paper]](https://arxiv.org/abs/2606.00499)<br>
  *Yu Yuan, Jianhao Yuan, Xijun Wang, Daiqing Li, Liu He, Lu Ling, Stanley Chan*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **Proprio: Latent Self-Scoring and Inference-Time Refinement for Physically Plausible Video Generation** [[Paper]](https://neurips.cc/virtual/2026/poster/154132)<br>
  *Mariam Hassan, Kaouther Messaoud, Wuyang Li, Alexandre Alahi*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **Physics in 2-Steps: Locking Motion Priors Before Visual Refinement Erases Them** [[Paper]](https://openreview.net/forum?id=5f2hxtNqpM)<br>
  *Woojung Han, Seil Kang, Youngjun Jun, Min-Hung Chen, Fu-En Yang, Seong Jae Hwang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Seeking Physics in Diffusion Noise** [[Paper]](https://arxiv.org/abs/2603.14294) [[Project]](https://thegreatestcj.github.io/Physics-in-Noise)<br>
  *Chujun Tang, Lei Zhong, Fangqiang Ding*

### Embodied, Driving and Human-Object Interaction World Models

Physics-aware video world models for specific domains.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **GenieDrive: Towards Physics-Aware Driving World Model with 4D Occupancy Guided Video Generation** [[Paper]](https://arxiv.org/abs/2512.12751)<br>
  *Zhenya Yang, Zhe Liu, Yuxiang Lu, Liping Hou, Chenxuan Miao, Siyi Peng, Bailan Feng, Xiang Bai, Hengshuang Zhao*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PAM: A Pose-Appearance-Motion Engine for Sim-to-Real HOI Video Generation** [[Paper]](https://arxiv.org/abs/2603.22193)<br>
  *Mingju Gao, Kaisen Yang, Huan-ang Gao, Bohan Li, Ao Ding, Wenyi Li, Yangcheng Yu, Jinkun Liu, Shaocong Xu, Yike Niu, Haohan Chi, Hao Chen, Hao Tang, Yu Zhang, Li Yi, Hao Zhao*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Physical Object Understanding with a Physically Controllable World Model** [[Paper]](https://arxiv.org/abs/2606.00439)<br>
  *Rahul Venkatesh, Klemen Kotar, Lilian Naing Chen, Wanhee Lee, Gia Ancone, Seungwoo Kim, Luca Thomas Wheeler, Jared Watrous, Honglin Chen, Daniel Bear, Stefan Stojanov, Daniel LK Yamins*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **RoboScape: Physics-informed Embodied World Model** *(Spotlight)* [[Paper]](https://arxiv.org/abs/2506.23135)<br>
  *Yu Shang, Xin Zhang, Yinzhou Tang, Lei Jin, Chen Gao, Wei Wu, Yong Li*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **CoInteract: Physically-Consistent Human-Object Interaction Video Synthesis via Spatially-Structured Co-Generation** [[Paper]](https://arxiv.org/abs/2604.19636)<br>
  *Xiangyang Luo, Xiaozhe Xin, Tao Feng, Xu Guo, Meiguang Jin, Junfeng Ma*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **DreamWorld: Unified World Modeling in Video Generation** [[Paper]](https://arxiv.org/abs/2603.00466)<br>
  *Boming Tan, Xiangdong Zhang, Ning Liao, Jingtao Zhang, Yuqing Zhang, Xiaoqiu Zhong, Xiaosong Jia, Xue Yang, Yanyong Zhang, Shaofeng Zhang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysisForcing: Physics Reinforced World Simulator for Robotic Manipulation** [[Paper]](https://arxiv.org/abs/2606.28128)<br>
  *Peiwen Zhang, Yufan Deng, Shangkun Sun, Juncheng Ma, Duomin Wang, Jonas Du, Zilin Pan, Ye Huang, Hao Liang, Songyan Huang, Ruihua Zhang, Enze Xie, Ming-Yu Liu, Daquan Zhou*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhyWorld: Physics-Faithful World Model for Video Generation** [[Paper]](https://arxiv.org/abs/2605.19242)<br>
  *Pu Zhao, Juyi Lin, Timothy Rupprecht, Arash Akbari, Chence Yang, Rahul Chowdhury, Elaheh Motamedi, Arman Akbari, Yumei He, Chen Wang, Geng Yuan, Weiwei Chen, Yanzhi Wang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **MIND-V: Hierarchical Video Generation for Long-Horizon Robotic Manipulation with RL-based Physical Alignment** [[Paper]](https://arxiv.org/abs/2512.06628)<br>
  *Ruicheng Zhang, Mingyang Zhang, Jun Zhou, Xiaofan Liu, Zunnan Xu, Zhizhou Zhong, Puxin Yan, Haocheng Luo, Xiu Li*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **World Models That Know When They Don't Know: Controllable Video Generation with Calibrated Uncertainty** [[Paper]](https://arxiv.org/abs/2512.05927)<br>
  *Zhiting Mei, Tenny Yin, Micah Baker, Ola Shorinwa, Anirudha Majumdar*

[⬆ Back to top](#contents)

## Physics-Aware Image Generation and Editing

Images, and edits to images or videos, whose content must respect physical relations or the outcome of a physical process.

- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhysEdit: Physically Consistent Image Editing via Causal Enforcement** [[Paper]](https://link.springer.com/chapter/10.1007/978-3-032-37023-5_24) [[Code]](https://github.com/HiDream-ai/PhysEdit)<br>
  *Siqi Wan, Jingwen Chen, Yehao Li, Yingwei Pan, Ting Yao, Tao Mei*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **ChronoEdit: Towards Temporal Reasoning for In-Context Image Editing and World Simulation** [[Paper]](https://openreview.net/forum?id=MbMzoQ91Gk)<br>
  *Jay Zhangjie Wu, Xuanchi Ren, Tianchang Shen, Tianshi Cao, Kai He, Yifan Lu, Ruiyuan Gao, Enze Xie, Shiyi Lan, Jose M. Alvarez, Jun Gao, Sanja Fidler, Zian Wang, Huan Ling*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **Does FLUX Already Know How to Perform Physically Plausible Image Composition?** [[Paper]](https://openreview.net/forum?id=DcVg87ibK9)<br>
  *Shilin Lu, Zhuming Lian, Zihan Zhou, Shaocong Zhang, Chen Zhao, Adams Wai-Kin Kong*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **From Statics to Dynamics: Physics-Aware Image Editing with Latent Transition Priors** [[Paper]](https://openreview.net/forum?id=7YeCG53Bo9)<br>
  *Liangbing Zhao, Le Zhuo, Sayak Paul, Hongsheng Li, Mohamed Elhoseiny*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **PhysicsGen: Can Generative Models Learn from Images to Predict Complex Physical Relations?** [[Paper]](https://arxiv.org/abs/2503.05333)<br>
  *Martin Spitznagel, Jan Vaillant, Janis Keuper*
- ![3DV 2025](https://img.shields.io/badge/3DV%202025-1f6feb?style=flat-square) 🔥 **AutoVFX: Physically Realistic Video Editing from Natural Language Instructions** [[Paper]](https://arxiv.org/abs/2411.02394)<br>
  *Hao-Yu Hsu, Zhi-Hao Lin, Albert J. Zhai, Hongchi Xia, Shenlong Wang*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **Learning Action and Reasoning-Centric Image Editing from Videos and Simulation** *(Spotlight)* [[Paper]](https://neurips.cc/virtual/2024/poster/97473)<br>
  *Benno Krojer, Dheeraj Vattikonda, Luis Lara, Varun Jampani, Eva Portelance, Christopher Pal, Siva Reddy*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **VideoPhysEdit: Physical Counterfactual Video Editing via Rigid-Body Physical Scene Reconstruction** [[Paper]](https://arxiv.org/abs/2609.35134) [[Code]](https://github.com/Hammour-steak/VideoPhysEdit)<br>
  *Conghan Yue, Yuanjie Chen, Yue Han, Ya Gao, Yunyan Xiao, WeiYao Zhang, Zhineng Chen*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Do-Undo: Generating and Reversing Physical Actions in Vision-Language Models** [[Paper]](https://arxiv.org/abs/2512.13609)<br>
  *Shweta Mahajan, Shreya Kadambi, Hoang Le, Rajeev Yasarla, Apratim Bhattacharyya, Munawar Hayat, Fatih Porikli*

[⬆ Back to top](#contents)

## Physics-Aware Audio Generation

Sound synthesized from physical interactions, materials, or motion.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PAVAS: Physics-Aware Video-to-Audio Synthesis** *(Oral)* [[Paper]](https://arxiv.org/abs/2512.08282) [[Code]](https://github.com/SonyResearch/PAVAS)<br>
  *Oh Hyun-Bin, Yuhta Takida, Toshimitsu Uesaka, Tae-Hyun Oh, Yuki Mitsufuji*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **Hearing Hands: Generating Sounds from Physical Interactions in 3D Scenes** [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Dou_Hearing_Hands_Generating_Sounds_from_Physical_Interactions_in_3D_Scenes_CVPR_2025_paper.html)<br>
  *Yiming Dou, Wonseok Oh, Yuqing Luo, Antonio Loquercio, Andrew Owens*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **Differentiable Modal Synthesis for Physical Modeling of Planar String Sound and Motion Simulation** [[Paper]](https://neurips.cc/virtual/2024/poster/94184)<br>
  *Jin Woo Lee, Jaehyun Park, Min Jun Choi, Kyogu Lee*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Tora3: Trajectory-Guided Audio-Video Generation with Physical Coherence** [[Paper]](https://arxiv.org/abs/2604.09057)<br>
  *Junchao Liao, Zhenghao Zhang, Xiangyu Meng, Litao Li, Ziying Zhang, Siyu Zhu, Long Qin, Weizhi Wang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **SonicGauss: Position-Aware Physical Sound Synthesis for 3D Gaussian Representations** [[Paper]](https://arxiv.org/abs/2507.19835)<br>
  *Chunshi Wang, Hongxing Li, Yawei Luo*

[⬆ Back to top](#contents)

## Evaluation

### Benchmarks

Benchmarks that test physical commonsense, laws, or consistency of generated images, videos, 3D/4D content, and edits.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PAI-Bench: A Comprehensive Benchmark For Physical AI** *(Oral)* [[Paper]](https://arxiv.org/abs/2512.01989)<br>
  *Fengzhe Zhou, Jiannan Huang, Jialuo Li, Deva Ramanan, Humphrey Shi*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhysGaia: A Physics-Aware Benchmark with Multi-Body Interactions for Dynamic Novel View Synthesis** [[Paper]](https://arxiv.org/abs/2506.02794) [[Project]](https://cv.snu.ac.kr/research/PhysGaia/)<br>
  *Mijeong Kim, Gunhee Kim, Jungyoon Choi, Wonjae Roh, Bohyung Han*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **A Physics-Grounded Benchmark for Multi-Agent Dynamics in World Models** [[Paper]](https://arxiv.org/abs/2606.28757)<br>
  *Nuo Chen, Lulin Liu, Zihao Li, Ziyao Zeng, Zihao Zhu, Wenyan Cong, Junyuan Hong, Yunhao Yang, Zhengzhong Tu, Yan Wang, Boris Ivanovic, Marco Pavone, Zhangyang Wang, Yang Zhou, Zhiwen Fan*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **Benchmarking Scientific Understanding and Reasoning for Video Generation using VideoScience-Bench** [[Paper]](https://arxiv.org/abs/2512.02942)<br>
  *Lanxiang Hu, Abhilash Shankarampeta, Yixin Huang, Zilin Dai, Haoyang Yu, Yujie Zhao, Haoqiang Kang, Daniel Zhao, Tajana Rosing, Hao Zhang*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **BeyondMasks: Evaluating Causal and Physical Consistency in Video Object Removal** [[Paper]](https://arxiv.org/abs/2608.20107)<br>
  *Yigit Ekin, Enes Sanli, Aykut Erdem, Erkut Erdem, Aysegul Dundar*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **IRIS: A Real-World Benchmark for Inverse Recovery and Identification of Physical Dynamic Systems from Monocular Video** [[Paper]](https://arxiv.org/abs/2603.16432)<br>
  *Rasul Khanbayov, Mohamed Rayan Barhdadi, Erchin Serpedin, Hasan Kurban*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhyEditBench: A Real-World Multi-Stage Benchmark for Physics-Aware Image Editing** [[Paper]](https://arxiv.org/abs/2606.26551)<br>
  *Shengbin Guo, Shaokang He, Chaoyue Meng, Shengpeng Xiao, Xunzhi Xiang, Shaofeng Zhang, Qi Fan*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **Physics Question Scene Graph: Fine-grained Evaluation of Physical Plausibility in Text-to-Video Generation** [[Paper]](https://arxiv.org/abs/2606.25306)<br>
  *Atin Pothiraj, Jaemin Cho, Yue Zhang, Elias Stengel-Eskin, Mohit Bansal*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **Apple-π: Benchmarking Thinking with Video Towards Law-Grounded Physical Intelligence** [[Paper]](https://neurips.cc/virtual/2026/poster/139053)<br>
  *Runmao Yao, Kairui Hu, Yukang Cao, Ruisi Wang, Shulin Tian, Ziang Cao, Weichen Fan, Ziqi Huang, Yuhao Dong, Hao Li, Zhaoxi Chen, Zhongang Cai, Lei Yang, Ziwei Liu*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **Do Joint Audio-Video Generation Models Understand Physics?** [[Paper]](https://neurips.cc/virtual/2026/poster/139141)<br>
  *Zijun Cui, Xiulong Liu, Hao Fang, Mingwei Xu, Jiageng Liu, Zexin Xu, Weiguo Pian, Shijian Deng, Feiyu Du, Chenming Ge, Yapeng Tian*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **PhyMetric: Diagnosing Physical Plausibility in Text-to-Video Generation via Scene-Level QA** ⭐ **Ours** [[Paper]](https://neurips.cc/virtual/2026/poster/139124)<br>
  *Siwei Meng, Xuerou Cai, Rui Hu, Ping Liu*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **Principia: Relational Physics Tests for Video Models** [[Paper]](https://neurips.cc/virtual/2026/poster/139457)<br>
  *Varun V Thozhiyoor, Shivam Tripathi, Venkatesh Babu Radhakrishnan, Anand Bhattad*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **PhyWorldBench: A Comprehensive Evaluation of Physical Realism in Text-to-Video Models** *(Oral)* [[Paper]](https://arxiv.org/abs/2507.13428)<br>
  *Jing Gu, Xian Liu, Yu Zeng, Ashwin Nagarajan, Fangrui Zhu, Daniel Hong, Yue Fan, Qianqi Yan, Kaiwen Zhou, Ming-Yu Liu, Xin Eric Wang*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **VideoPhy-2: A Challenging Action-Centric Physical Commonsense Evaluation in Video Generation** [[Paper]](https://arxiv.org/abs/2503.06800)<br>
  *Hritik Bansal, Clark Peng, Yonatan Bitton, Roman Goldenberg, Aditya Grover, Kai-Wei Chang*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **Evaluating Newtonian Mechanics in Video Generative Models with Real Physical Systems** [[Paper]](https://openreview.net/forum?id=f4xAzcMug6)<br>
  *Antonios Tragoudaras, Chenyu Zhang, Daniil Cherniavskii, Antonios Vozikis, Thijmen Nijdam, Derck W. E. Prinzhorn, Mark Bodracska, Nicu Sebe, Andrii Zadaianchuk, Stratis Gavves*
- ![ICLR 2025](https://img.shields.io/badge/ICLR%202025-1f6feb?style=flat-square) 🔥 **VideoPhy: Evaluating Physical Commonsense for Video Generation** [[Paper]](https://arxiv.org/abs/2406.03520)<br>
  *Hritik Bansal, Zongyu Lin, Tianyi Xie, Zeshun Zong, Michal Yarom, Yonatan Bitton, Chenfanfu Jiang, Yizhou Sun, Kai-Wei Chang, Aditya Grover*
- ![ICML 2025](https://img.shields.io/badge/ICML%202025-1f6feb?style=flat-square) 🔥 **Towards World Simulator: Crafting Physical Commonsense-Based Benchmark for Video Generation** [[Paper]](https://arxiv.org/abs/2410.05363)<br>
  *Fanqing Meng, Jiaqi Liao, Xinyu Tan, Quanfeng Lu, Wenqi Shao, Kaipeng Zhang, Yu Cheng, Dianqi Li, Ping Luo*
- ![ICML 2025](https://img.shields.io/badge/ICML%202025-1f6feb?style=flat-square) 🔥 **WorldSimBench: Towards Video Generation Models as World Simulators** [[Paper]](https://arxiv.org/abs/2410.18072)<br>
  *Yiran Qin, Zhelun Shi, Jiwen Yu, Xijun Wang, Enshen Zhou, Lijun Li, Zhenfei Yin, Xihui Liu, Lu Sheng, Jing Shao, Lei Bai, Ruimao Zhang*
- ![CVPR 2026 Workshop](https://img.shields.io/badge/CVPR%202026%20Workshop-6c757d?style=flat-square) 🔥 **Physics-Aware Video Instance Removal Benchmark** [[Paper]](https://arxiv.org/abs/2604.05898)<br>
  *Zirui Li, Xinghao Chen, Lingyu Jiang, Dengzhe Hou, Fangzhou Lin, Kazunori Yamada, Xiangbo Gao, Zhengzhong Tu*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Beyond Rigid: Benchmarking Non-Rigid Video Editing** [[Paper]](https://arxiv.org/abs/2601.18340)<br>
  *Bingzheng Qu, Xuefeng Bai, Kehai Chen, Min Zhang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Beyond Visual Quality: Evaluating Physical Consistency under Ego-Motion with EgoGenEval** [[Paper]](https://arxiv.org/abs/2609.11172)<br>
  *Yilin Long, Chenming Zhu, Zitang Gou, Jingli Lin, Tai Wang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **CRONOS: Benchmarking Counterfactual Physical Consistency in Video Models** [[Paper]](https://arxiv.org/abs/2605.23699) [[Project]](https://genintel.github.io/CRONOS/)<br>
  *León Begiristain, Olaf Dünkel, Adam Kortylewski*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **MME-CoF-Pro: Evaluating Reasoning Coherence in Video Generative Models with Text and Visual Hints** [[Paper]](https://arxiv.org/abs/2603.20194)<br>
  *Yu Qi, Xinyi Xu, Ziyu Guo, Siyuan Ma, Renrui Zhang, Xinyan Chen, Ruichuan An, Ruofan Xing, Jiayi Zhang, Haojie Huang, Pheng-Ann Heng, Jonathan Tremblay, Lawson L. S. Wong*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhyGround: Benchmarking Physical Reasoning in Generative World Models** [[Paper]](https://arxiv.org/abs/2605.10806)<br>
  *Juyi Lin, Arash Akbari, Yumei He, Lin Zhao, Haichao Zhang, Arman Akbari, Xingchen Xu, Zoe Y. Lu, Enfu Nan, Hokin Deng, Edmund Yeh, Sarah Ostadabbas, Yun Fu, Jennifer Dy, Pu Zhao, Yanzhi Wang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhyRubric: Rubric-Grounded Diagnostic Evaluation of Physical Commonsense in Text-to-Video Generation** [[Paper]](https://arxiv.org/abs/2611.13576) [[Code]](https://github.com/chenyil6/phyRubric)<br>
  *Huiyi Chen, Weitai Kang, Shicheng Fan, Xinshuo Wang, Zhixiang Shen, Yan Yan, Philip S. Yu, Baoxin Li*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Physics-IQ Verified** [[Paper]](https://arxiv.org/abs/2606.18943)<br>
  *Tim Rädsch, Yuki M Asano, Hilde Kuehne, Stefan Bauer, Priyank Jaini, Robert Geirhos, Carsten T. Lüth*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Physion-Eval: Evaluating Physical Realism in Generated Video via Human Reasoning** [[Paper]](https://arxiv.org/abs/2603.19607)<br>
  *Qin Zhang, Peiyu Jing, Hong-Xing Yu, Fangqiang Ding, Fan Nie, Weimin Wang, Yilun Du, James Zou, Jiajun Wu, Bing Shuai*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PVBench: Quantifying Physical Plausibility in Video Generation with Object-Level Physical Measurements** [[Paper]](https://arxiv.org/abs/2610.26711) [[Code]](https://github.com/KSZG-11/PVBench)<br>
  *Kaiwei Chen, Moran Li, Zhenye Gan, Yabiao Wang, Chengjie Wang, Kexin Zhang, Yong Liu, Jiangning Zhang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Physics IQ Benchmark: Do Generative Video Models Understand Physical Principles?** [[Paper]](https://arxiv.org/abs/2501.09038)<br>
  *Saman Motamed, Laura Culp, Kevin Swersky, Priyank Jaini, Robert Geirhos*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **T2VPhysBench: A First-Principles Benchmark for Physical Consistency in Text-to-Video Generation** [[Paper]](https://arxiv.org/abs/2505.00337)<br>
  *Xuyang Guo, Jiayan Huo, Zhenmei Shi, Zhao Song, Jiahao Zhang, Jiale Zhao*
- ![arXiv 2024](https://img.shields.io/badge/arXiv%202024-b31b1b?style=flat-square) 🔥 **PhyBench: A Physical Commonsense Benchmark for Evaluating Text-to-Image Models** [[Paper]](https://arxiv.org/abs/2406.11802)<br>
  *Fanqing Meng, Wenqi Shao, Lixin Luo, Yahong Wang, Yiran Chen, Quanfeng Lu, Yue Yang, Tianshuo Yang, Kaipeng Zhang, Yu Qiao, Ping Luo*

### Automatic Evaluators, Critics and Detectors

Learned or training-free judges of physical plausibility, usable as metrics or rewards.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhyCritic: Multimodal Critic Models for Physical AI** [[Paper]](https://arxiv.org/abs/2602.11124)<br>
  *Tianyi Xiong, Shihao Wang, Guilin Liu, Yi Dong, Ming Li, Heng Huang, Jan Kautz, Zhiding Yu*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **PhyDetEx: Detecting and Explaining the Physical Plausibility of T2V Models** [[Paper]](https://arxiv.org/abs/2512.01843)<br>
  *Zeqing Wang, Keze Wang, Lei Zhang*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **GEOPHYS: The Geometry of Physical Plausibility** [[Paper]](https://neurips.cc/virtual/2026/poster/153630)<br>
  *Christian Internò, Alexander Pondaven, Habon Issa, Fabio Pizzati, Francesco Pinto, Markus Olhofer, Ivan Laptev, Philip Torr, Eero Simoncelli, Barbara Hammer, David Klindt*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **PhyProbe: Rethinking Physical Consistency Evaluation in Generated Videos** [[Paper]](https://neurips.cc/virtual/2026/poster/149508)<br>
  *Max KU, Jiaojiao Fan, Zekun Hao, Francesco Ferroni, Heng Wang, Wenhu Chen, Ming-Yu Liu, Prithvijit Chattopadhyay*
- ![ICLR 2026](https://img.shields.io/badge/ICLR%202026-1f6feb?style=flat-square) 🔥 **Evaluating Intuitive Physics Understanding in Video Diffusion Models via Likelihood Preference** [[Paper]](https://arxiv.org/abs/2510.11512)<br>
  *Jianhao Yuan, Fabio Pizzati, Francesco Pinto, Lars Kunze, Ivan Laptev, Paul Newman, Philip Torr, Daniele De Martini*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **Physics-Driven Spatiotemporal Modeling for AI-Generated Video Detection** *(Spotlight)* [[Paper]](https://openreview.net/forum?id=HiBoJLCyEo)<br>
  *Shuhai Zhang, ZiHao Lian, Jiahao Yang, Daiyuan Li, Guoxuan Pang, Feng Liu, Bo Han, Shutao Li, Mingkui Tan*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Each Judge Its Own Yardstick: Discovering Per-VLM Taxonomies for Physical Video Evaluation** [[Paper]](https://arxiv.org/abs/2606.22918)<br>
  *Yu Cao, Ziquan Liu, Zhensong Zhang, Jiankang Deng, Shaogang Gong, Jifei Song*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **VeriPhy: Agentic Physical Reasoning for World Model Evaluation and Refinement** [[Paper]](https://arxiv.org/abs/2609.03153)<br>
  *Wenzhuo Xu, Yuchen Zhu, Chongjian Ge, Xuan Shen, Jing Shi, Jason Kuen, Yongxin Chen, Molei Tao, Christopher McComb, Noelia Grande Gutiérrez, Jiuxiang Gu*

### Datasets

Training data built for physics-aware generation.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **PhysInOne: Visual Physics Learning and Reasoning in One Suite** [[Paper]](https://arxiv.org/abs/2604.09415) [[Project]](https://vlar-group.github.io/PhysInOne.html)<br>
  *Siyuan Zhou, Hejun Wang, Hu Cheng, Jinxi Li, Dongsheng Wang, Junwei Jiang, Yixiao Jin, Jiayue Huang, Shiwei Mao, Shangjia Liu, Yafei Yang, Hongkang Song, Shenxing Wei, Zihui Zhang, Peng Huang, Shijie Liu, Zhengli Hao, Hao Li, Yitian Li, Wenqi Zhou, Zhihan Zhao, Zongqi He, Hongtao Wen, Shouwang Huang, Peng Yun, Bowen Cheng, Pok Kazaf Fu, Wai Kit Lai, Jiahao Chen, Kaiyuan Wang, Zhixuan Sun, Ziqi Li, Haochen Hu, Di Zhang, Chun Ho Yuen, Bing Wang, Zhihua Wang, Chuhang Zou, Bo Yang*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **VibraVerse: A Large-Scale Geometry-Acoustics Alignment Dataset for Physically-Consistent Multimodal Learning** [[Paper]](https://arxiv.org/abs/2511.20422)<br>
  *Bo Pang, Chenxi Xu, Jierui Ren, Guoping Wang, Sheng Li*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysEditWorld: A Large-Scale Dataset Toward Physics-Editable World Models** [[Paper]](https://arxiv.org/abs/2606.26694)<br>
  *Bin Hu, Yanwen Ma, Jiehui Huang, Ziliang Zhang, Haoning Wu, Ruicheng Zhang, Yaokun Li, Zijun Wang, Yuechen Zhang, Chun-Mei Tseng, Hanhui Li, Shengju Qian, Jun Zhou, Kaipeng Zhang, Xiaodan Liang, Jiaya Jia, Xiu Li*

[⬆ Back to top](#contents)

## Physical Understanding in Video and World Models

Analyses of what video generators, video encoders, and world models know about physics, and methods that recover physical laws from visual dynamics.

- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Pixel2Phys: Distilling Governing Laws from Visual Dynamics** [[Paper]](https://arxiv.org/abs/2602.19516)<br>
  *Ruikun Li, Jun Yao, Yingfan Hua, Shixiang Tang, Biqing Qi, Bin Liu, Wanli Ouyang, Yan Lu*
- ![CVPR 2026](https://img.shields.io/badge/CVPR%202026-1f6feb?style=flat-square) 🔥 **Δynamics: Language-Based Representation for Inferring Rigid-Body Dynamics From Videos** [[Paper]](https://arxiv.org/abs/2605.20576)<br>
  *Chia-Hsiang Kao, Cong Phuoc Huynh, Chien-Yi Wang, Noranart Vesdapunt, Stefan Stojanov, Bharath Hariharan, Oleksandr Obiednikov, Ning Zhou*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **Human-Level Accuracy, Non-Human Strategies: Revealing Model-Human Divergence in Video Physical Reasoning** [[Paper]](https://arxiv.org/abs/2609.22788)<br>
  *Fanhong Li, Shurui Zheng, Zi Yin, Junbo Cui, Lei Ji, Jia Liu*
- ![ECCV 2026](https://img.shields.io/badge/ECCV%202026-1f6feb?style=flat-square) 🔥 **Pretrained Video Models as Differentiable Physics Simulators for Urban Wind Flows** [[Paper]](https://arxiv.org/abs/2603.21210) [[Project]](https://rbischof.github.io/windinet_web)<br>
  *Janne Perini, Rafael Bischof, Moab Arar, Ayça Duran, Michael A. Kraus, Siddhartha Mishra, Bernd Bickel*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **How Do Video Foundation Models Encode Intuitive Physics? Probing Across Pretraining Paradigms** [[Paper]](https://arxiv.org/abs/2606.09646)<br>
  *Samuele Punzo, Niccolò Caselli, Ippokratis Pantelidis, Francesco Massafra, Salvatore Lo Sardo, Mohammadreza Salehi*
- ![NeurIPS 2026](https://img.shields.io/badge/NeurIPS%202026-1f6feb?style=flat-square) 🔥 **The Invisible Hand of Physics: When Video Diffusion Models Know More Than They Show** *(Spotlight)* [[Paper]](https://neurips.cc/virtual/2026/poster/149891)<br>
  *Parsa Esmati, Somjit Nath, Katja Hofmann, Derek Nowrouzezahrai, Samira Ebrahimi Kahou, Majid Mirmehdi*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **From Kepler to Newton: Inductive Biases Guide Learned World Models in Transformers** [[Paper]](https://openreview.net/forum?id=ij3UfXzgYp)<br>
  *Ziming Liu, Surya Ganguli, Andreas S. Tolias*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **Interpreting Physics in Video World Models** [[Paper]](https://openreview.net/forum?id=aijGVmEG9Y)<br>
  *Sonia Joseph, Quentin Garrido, Randall Balestriero, Matthew Kowal, Thomas Fel, Shahab Bakhtiari, Blake Aaron Richards, Michael Rabbat*
- ![ICML 2026](https://img.shields.io/badge/ICML%202026-1f6feb?style=flat-square) 🔥 **Physics from Video: Identifiability of Time-Invariant Second-Order ODEs under Minimal Trajectory Conditions** [[Paper]](https://openreview.net/forum?id=xrXxqLadvS)<br>
  *Yuanyuan Wang, Wenjie Wang, Kun Zhang, Mingming Gong*
- ![CVPR 2025](https://img.shields.io/badge/CVPR%202025-1f6feb?style=flat-square) 🔥 **Learning Physics From Video: Unsupervised Physical Parameter Estimation for Continuous Dynamical Systems** [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Garcia_Learning_Physics_From_Video_Unsupervised_Physical_Parameter_Estimation_for_Continuous_CVPR_2025_paper.html)<br>
  *Alejandro Castañeda Garcia, Jan Warchocki, Jan van Gemert, Daan Brinks, Nergis Tomen*
- ![NeurIPS 2025](https://img.shields.io/badge/NeurIPS%202025-1f6feb?style=flat-square) 🔥 **Seeing the Wind from a Falling Leaf** [[Paper]](https://openreview.net/forum?id=4NaW9mbTqq)<br>
  *Zhiyuan Gao, Jiageng Mao, Hong-Xing Yu, Haozhe Lou, Emily Yue-ting Jia, Jernej Barbic, Jiajun Wu, Yue Wang*
- ![ICML 2025](https://img.shields.io/badge/ICML%202025-1f6feb?style=flat-square) 🔥 **How Far Is Video Generation from World Model: A Physical Law Perspective** [[Paper]](https://arxiv.org/abs/2411.02385)<br>
  *Bingyi Kang, Yang Yue, Rui Lu, Zhijie Lin, Yang Zhao, Kaixin Wang, Gao Huang, Jiashi Feng*
- ![ECCV 2024](https://img.shields.io/badge/ECCV%202024-1f6feb?style=flat-square) 🔥 **Understanding Physical Dynamics with Counterfactual World Modeling** [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/3523_ECCV_2024_paper.php)<br>
  *Rahul Venkatesh, Honglin Chen, Kevin Feigelis, Daniel M Bear, Khaled Jedoui, Klemen Kotar, Felix J Binder, Wanhee Lee, Sherry Liu, Kevin Smith, Judith E. Fan, Daniel Yamins*
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS%202024-1f6feb?style=flat-square) 🔥 **A General Protocol to Probe Large Vision Models for 3D Physical Understanding** [[Paper]](https://neurips.cc/virtual/2024/poster/96940)<br>
  *Guanqi Zhan, Chuanxia Zheng, Weidi Xie, Andrew Zisserman*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Do Vision Models Learn Physical Constraints or Rendering Shortcuts? A Counterfactual Benchmark for Grounded Physical Consistency** [[Paper]](https://arxiv.org/abs/2610.09205)<br>
  *M. Moein Esfahani, Sepehr Salem, Mohammed Alser, Vince Calhoun*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **PhysMind: From Video to Executable Worlds for Training-Free Physical Reasoning** [[Paper]](https://arxiv.org/abs/2608.04575)<br>
  *Chen Yang, Shenxiang Zeng, Haoyang Zhao, Zhouyuan Xu, Youquan He, Haoyu Li, Mingyi Deng, Jiansheng Fan, Chen Wang*
- ![arXiv 2026](https://img.shields.io/badge/arXiv%202026-b31b1b?style=flat-square) 🔥 **Why Do Video Diffusion Models Violate Physics? Unveiling the Flaws in Attention Mechanisms** [[Paper]](https://arxiv.org/abs/2609.23658)<br>
  *Yueyan Li, Haibo Wang, Caixia Yuan, Xiaojie Wang*
- ![arXiv 2025](https://img.shields.io/badge/arXiv%202025-b31b1b?style=flat-square) 🔥 **Intuitive physics understanding emerges from self-supervised pretraining on natural videos** [[Paper]](https://arxiv.org/abs/2502.11831)<br>
  *Quentin Garrido, Nicolas Ballas, Mahmoud Assran, Adrien Bardes, Laurent Najman, Michael Rabbat, Emmanuel Dupoux, Yann LeCun*

[⬆ Back to top](#contents)

## Related Awesome Lists

- [Awesome-Code-World-Models](https://github.com/pinglmlcv/Awesome-Code-World-Models): code as the representation of world dynamics, including code-based physical simulation for video generation.
- [Awesome-Concept-Erasure](https://github.com/pinglmlcv/Awesome-Concept-Erasure): concept erasure and unlearning in generative models.
- [Awesome-Physics-Cognition-based-Video-Generation](https://github.com/minnie-lin/Awesome-Physics-Cognition-based-Video-Generation): companion list of the physics cognition survey for video generation.
- [Awesome-Physics-aware-Generation](https://github.com/BestJunYu/Awesome-Physics-aware-Generation): companion list of the Generative Physical AI in Vision survey.
- [Awesome-From-Video-Generation-to-World-Model](https://github.com/ziqihuangg/Awesome-From-Video-Generation-to-World-Model): video generation models as world simulators.

[⬆ Back to top](#contents)

## Citation

If you find this list useful, please consider citing our survey:

```bibtex
@inproceedings{meng2025grounding,
  title     = {Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC},
  author    = {Meng, Siwei and Luo, Yawei and Liu, Ping},
  booktitle = {Proceedings of the Thirty-Fourth International Joint Conference on Artificial Intelligence (IJCAI)},
  year      = {2025}
}
```
