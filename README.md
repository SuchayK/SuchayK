<h1 align="center">Suchay Kommisetty</h1>

<p align="center">
  CS @ UT Austin — Turing Scholars '30
</p>

<p align="center">
  <a href="mailto:suchay.kommisetty@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-suchay.kommisetty%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/suchay-kommisetty-474125285"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>

---

### About

CS student in the **Turing Scholars** honors program at **UT Austin**. Currently **SWE/AI Intern**
at **Sony × University at Buffalo Visual Computing Lab**, working on real-time basketball action
recognition for camera autofocus.

I work on applied computer vision and machine learning — medical image segmentation,
uncertainty-aware models, and time-series anomaly detection — with a background in competitive
programming and four years of competition robotics. Most of what I build now is in private repos;
the public ones here are my research and robotics work.

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
</p>

---

### Research

| Lab | Work | Result |
|---|---|---|
| **Sony × UB Visual Computing Lab** | Real-time basketball action recognition for camera autofocus — YOLOv8 + transformers, multi-player spatiotemporal modeling | 94% accuracy; firmware-ready proof of concept tested at a WNBA game |
| **UH Mohan Lab** | [Segmentation of renal tubules and immune cells](https://github.com/SuchayK/TRIMS-results) in lupus nephritis biopsies — Detectron2 Mask R-CNN | ~90% accuracy on 3,000+ labeled images |
| **UH Real-Time Systems Lab** | [Uncertainty-aware classifiers](https://github.com/SuchayK/IDK-classifiers-results) that abstain rather than answer wrong — Waymo/nuScenes, DuckieTown + SUMO | 37% fewer false positives |
| **Stanford S3L / LIMESS** | [Anomaly detection in EPA air-quality series](https://github.com/SuchayK/air-quality-anomaly-detection) — LSTM vs. CNN on PM2.5 and ozone | AUC 1.0, up to 99.87% accuracy |
| **Ohio State IVCL × Nike** | Predicting image memorability — CNN feature extraction over visual and linguistic features | 20,000+ labeled images + human recall studies |
| **UH Ergodic Theory & Dynamical Systems** | [Conjugate Gradient methods for sparse systems](https://github.com/SuchayK/conjugate-gradient-sparse) — convergence, stability, preconditioning | Published on TechRxiv |

<sub>Where a repo is linked, it holds the method write-up or the implementation. Lab datasets and
proprietary code aren't mine to publish — happy to walk through the details directly.</sub>

---

### Publications

- **Exploring the Numerical Stability and Efficiency of Conjugate Gradient Methods for Sparse Systems** — *TechRxiv*
- **TRIMS: A Novel Deep Learning Model for Segmentation of Renal Tubules and Immune Cells in Immunostained Biopsies** — *Journal of Imaging* (in progress) · presented at **ASN Kidney Week 2025**
- **Implementing Dynamic User Equilibrium Through "I Don't Know" Classifiers for Autonomous Driving Using DuckieTown and SUMO** — *IEEE RTSS 2025* (in progress) · preliminary at **IEEE IEMDC 2025**
- **Deep Learning-Based Anomaly Detection in Air Quality Monitoring: LSTM and CNN Models for PM2.5 and Ozone** — in progress

---

### Projects

**[SceneSponsor](https://github.com/SuchayK/ScreenSponsor)** — An agent that places branded
products inside creator videos that already exist, rather than interrupting them with an ad. A
vision model plans placement geometry per keyframe; the clip is composited with FFmpeg in an
isolated worker; nothing exports without creator approval. Built with a team at Daytona
HackSprint #5 — I worked across the scene-understanding pipeline, rendering, creator studio,
and job API, and produced the sponsor asset library the compositor draws from.
*(Team repo, hosted on a teammate's account.)*

**[greenAcres](https://github.com/SuchayK/greenAcres)** — Pick a point on a map and get the crops
that will actually grow there. Live climate data into a Keras classifier over 22 crops, served
from Flask behind a Leaflet frontend. **1st place, Software Development, Texas TSA State 2025.**

**[Pololu---Robot-Tour](https://github.com/SuchayK/Pololu---Robot-Tour)** — Autonomous 4×4 maze
navigation on a Pololu 3pi+ 32U4: A\* planning, gyro-corrected odometry, dual PID.
**2nd place, MIT Science Olympiad National Invitational 2025.**

**[VEXRobot1](https://github.com/SuchayK/VEXRobot1)** — VEX V5 competition robot (Team 19697Z):
6-motor drive, three-encoder odometry, inertial-corrected PID, pneumatics.
**Excellence Award and UIL Texas State 6A Champions, 2025.**

---

### Competitions

**USACO Platinum** · **2× AIME qualifier** · **National Merit Semifinalist** · **4× VEX Robotics
Worlds qualifier** · **3× FIRST Robotics Worlds qualifier**

---

<!--
  ### Stats

  GitHub stats card is staged below but DISABLED. As of Aug 3, 2026 the shared
  github-readme-stats instance (github-readme-stats.vercel.app) returns
  503 DEPLOYMENT_PAUSED for every user, so embedding it would render a broken
  image on the profile. To enable: confirm the URL below returns an SVG, then
  uncomment this block. If it's still down, deploy your own instance — the
  project's README covers the one-click Vercel fork, which is also the fix for
  the rate limits the shared instance is prone to.

  <p align="center">
    <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=SuchayK&show_icons=true&hide_border=true&include_all_commits=true&hide_title=true&theme=graywhite">
  </p>

  ---
-->

<p align="center">
  <sub>Some of my work is proprietary and lives in private repos. Happy to talk about it —
  reach out by email.</sub>
</p>
