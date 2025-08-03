#  Explainable AI for Automatic Target Recognition (ATR)

##  Overview
This project implements a deep learning-based **Automatic Target Recognition (ATR)** system enhanced with **Explainable AI (XAI)** techniques to ensure both high accuracy and transparent decision-making. The system classifies visual inputs (e.g., military vehicles, aircraft, or enemy/friendly tanks) and uses post-hoc interpretability methods to justify predictions — a critical requirement in high-stakes defense applications.

---

##  Objectives
- Classify battlefield targets from aerial or satellite imagery using CNNs.
- Provide **visual and quantitative explanations** for predictions to ensure **trust**, **accountability**, and **human-in-the-loop** verification.
- Improve transparency in target recognition pipelines for military intelligence systems.

---

##  Methodology
-  **Model**: Fine-tuned **ResNet-50** CNN trained on annotated target imagery.
-  **XAI Techniques Used**:
  - **Grad-CAM**: Heatmaps to show spatial attention of the CNN.
  - **LIME & SHAP**: Feature-level impact analysis.
  - **Integrated Gradients**: Gradient-based attribution for pixel contributions.
  - **Occlusion Sensitivity**: Perturbation-based explanation for robustness testing.

---

##  Technologies Used
- **Python**, **PyTorch**, **TensorFlow**
- **OpenCV** – Image preprocessing
- **captum**, **lime**, **shap** – XAI libraries
- **Matplotlib, Seaborn** – Visualization

---

