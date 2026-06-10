<div align="center">
  <h1>Hi 👋, I'm Md Suzauddola</h1>
  
  <p><strong>Researcher | Deep Learning Engineer | Computer Vision for Agriculture</strong></p>
  
  <img src="https://img.shields.io/badge/Research-AI%20for%20Sustainable%20Agriculture-green" alt="Research Focus" />
  <img src="https://img.shields.io/badge/PyTorch-Expert-red" alt="PyTorch" />
  <img src="https://img.shields.io/badge/YOLO-Advanced-blue" alt="YOLO" />
  
  <h3>🌟 Featured Work</h3>
  
  <h2><a href="https://github.com/yourusername/CMPestNet">CMPestNet</a></h2>
  <p><strong>Advanced Channel-Enhanced Multi-Scale Pest Detection Network</strong></p>
  
  <p>Published in <strong>Expert Systems with Applications (2025)</strong></p>
  
  <img src="https://github.com/yourusername/CMPestNet/raw/main/assets/teaser.jpg" width="780" alt="CMPestNet Overview" />
  
  <h4>Key Achievements</h4>
  
  | Dataset   | mAP / Acc | Improvement | FPS     |
  |-----------|-----------|-------------|---------|
  | **Jute17**    | **85.6% mAP** | **+9.2%**   | **350+** |
  | **Pest24**    | **78.22% mAP** | **+8.02%** | **370+** |
  | **IP102**     | **78.15% Acc** | SOTA        | -       |

  <p>
    <a href="https://github.com/yourusername/CMPestNet"><strong>⭐ Star CMPestNet</strong></a> • 
    <a href="https://doi.org/10.1016/j.eswa.2025.126896">📄 Read the Paper</a> • 
    <a href="https://github.com/yourusername/CMPestNet/releases">⬇️ Download Models</a>
  </p>
</div>

---

## 🚀 About Me

I am a researcher focused on developing efficient deep learning solutions for **real-world agricultural challenges**. My work emphasizes **crop pest detection** in complex field environments, addressing small objects, camouflage, and multi-scale variability.

**Research Interests:**
- Object Detection & Computer Vision
- Efficient Neural Architectures (YOLO-based)
- Agricultural AI & Precision Farming
- Multi-scale Feature Extraction & Channel Attention

---

## 📌 Featured Project: **CMPestNet**

**"Advanced deep learning model for crop-specific and cross-crop pest identification"**

### ✨ Core Innovations
- **CE-GELAN** (Channel-Enhanced Generalized Efficient Layer Aggregation Network)
- **GMSFE-ELAN** (Generalized Multi-Scale Feature Extraction with 1×1, 3×3, 5×5, 7×7 kernels)
- **Custom Re-parameterization** for real-time inference (350+ FPS)
- New **Jute17 Dataset** (12,916 images, 17 pest classes)

### 📊 Performance Highlights
- **Jute17**: 85.6% mAP (9.2% better than baseline)
- **Pest24**: 78.22% mAP (excellent on tiny pests)
- **IP102**: 78.15% Accuracy (outperforms multiple SOTA models)
- Strong generalization across crop-specific and cross-crop scenarios

### 🛠️ Tech Stack
- **Framework**: PyTorch 2.1+
- **Architecture**: Enhanced YOLO-style with custom modules
- **Tools**: OpenCV, Albumentations, Grad-CAM, etc.

---

## 📁 Repository Structure (CMPestNet)

```bash
CMPestNet/
├── README.md                  # ← You are here
├── LICENSE
├── requirements.txt
├── setup.py
├── assets/                    # Visuals & Results
│   ├── teaser.jpg
│   ├── architecture.png
│   ├── gradcam_comparison.png
│   └── performance_charts/
├── models/
│   ├── cmpestnet.py
│   ├── ce_gelan.py
│   ├── gmsfe_elan.py
│   └── reparam.py
├── utils/
│   ├── augmentations.py
│   ├── loss.py
│   └── metrics.py
├── scripts/
│   ├── train.py
│   ├── infer.py
│   └── export.py
├── notebooks/
│   ├── training_demo.ipynb
│   └── inference_demo.ipynb
├── config/
│   └── hyperparameters.yaml
├── data/                      # Download scripts
└── weights/                   # Pre-trained models (Git LFS)


🚀 Quick Start

# Clone the repo
git clone https://github.com/yourusername/CMPestNet.git
cd CMPestNet

# Install dependencies
pip install -r requirements.txt

# Inference example
python scripts/infer.py --weights weights/cmpestnet_jute17.pt --source test_images/ --save-txt



📄 Citation

@article{suzauddola2025cmpestnet,
  title   = {Advanced deep learning model for crop-specific and cross-crop pest identification},
  author  = {Md Suzauddola and Defu Zhang and Adnan Zeb and Junde Chen and others},
  journal = {Expert Systems with Applications},
  year    = {2025},
  doi     = {10.1016/j.eswa.2025.126896}
}

🌐 Connect With Me

GitHub: @suzauddola
Google Scholar / ResearchGate / LinkedIn: https://sites.google.com/view/mdsuzauddola/home
