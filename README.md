# Trust-Aware Multi-View Learning for Hand Pose Estimation with Uncertainty  

## 📌 Overview  
This repository contains the code, datasets, and research materials related to the **Trust-Aware Multi-View Learning for Hand Pose Estimation with Uncertainty** project. The study integrates **multi-view learning** with **Bayesian Neural Networks (BNNs)** to enhance **hand pose estimation accuracy**, while incorporating **trust-awareness and uncertainty quantification**.  

By leveraging a **probabilistic neural network architecture**, we propose a **Trust-Aware Bayesian MobileNet (TABM)** model, which dynamically adjusts predictions based on image quality, noise levels, and occlusions. This approach enhances model **robustness, accuracy, and reliability** in real-world applications.  

---

Features  
✔ **Multi-view learning integration** for hand pose estimation  
✔ **Trust-aware mechanism** that assesses image clarity, noise, and occlusions  
✔ **Uncertainty quantification** via Bayesian Neural Networks  
✔ **Lightweight architecture (MobileNetV2 backbone)** for real-time applications  
✔ **Comprehensive evaluation** on the Large-scale Multiview 3D Hand Pose (MHP) dataset  

---

## 📂 Repository Structure  

```bash
📁 Thesis_Repo/
│── 📄 README.md                  # This file
│── 📁 dataset/                    # MHP dataset (not included; download separately)
│── 📁 models/                     # Pre-trained and trained model checkpoints
│── 📁 src/                        # Source code for training and evaluation
│    ├── train.py                 # Model training script
│    ├── evaluate.py              # Model evaluation script
│    ├── dataloader.py            # Data preprocessing and augmentation
│    ├── architecture.py          # Bayesian MobileNet implementation
│    ├── utils.py                 # Utility functions
│── 📁 notebooks/                  # Jupyter notebooks for exploratory analysis
│── 📁 results/                    # Experiment results, logs, and visualizations
│── 📁 docs/                       # Research paper, methodology, and references
│── 📄 requirements.txt            # Python dependencies  
