# Hi there 👋, I'm Yang Li

- 🎓 **Master Student in Software Engineering @ Hainan University**
- 🔬 **Research Interest:** Computational Pathology | Deep Learning | Computer Vision
- 💻 **Tech Stack:** Python | PyTorch | C | OpenCV | Linux
- ⚙️ **Hardware Enthusiast:** Master of System Optimization & Overclocking

### 🚀 Current Focus
- Building **BioGraP** — a Biology-Anchored Graph Progression Network for cancer survival prediction on Whole Slide Images.
- Leveraging pathology foundation models (**CONCH ViT-B/16**) and graph neural networks (**GraphSAGE**) for multimodal WSI analysis.
- Evaluating across **4 TCGA cohorts** (BLCA, LUAD, LUSC, LIHC) covering ~1,700+ patients with nested cross-validation.

### 🔬 Featured Project: BioGraP

**BioGraP** (Biology-Anchored Graph Progression Learning) models tumor progression as a directed graph process for survival prediction from histopathology WSIs.

- **Architecture:** Prototype-based graph coarsening (256 prototypes → 64 supernodes) with directed GraphSAGE message passing
- **Features:** Dual-stream — CONCH ViT-B/16 context features (512-dim) + HoverFast morphological features (256-dim)
- **Evaluation:** 4 TCGA cancer cohorts, 8 baselines (Static MIL / Spatial Graph / Dynamic Trajectory)
- **Infrastructure:** Dockerized pipeline with Jupyter integration, deployed on GPU servers

### 📊 GitHub Stats

