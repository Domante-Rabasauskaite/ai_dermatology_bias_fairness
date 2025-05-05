# Fairness-Aware Deep Learning for Eczema Diagnosis in Dermatology

This repository contains the code and evaluation tools developed for the MSc Artificial Intelligence thesis titled:

**"Advancing AI in Dermatology: Bias Mitigation and Computational Optimization for Skin Condition Diagnostics"**

by Domante Rabasauskaite, Munster Technological University, 2025.


## Project Overview

Despite significant progress in AI for medical imaging, dermatological diagnostic systems often exhibit poor generalization across diverse skin tones, particularly Fitzpatrick types IV–VI. This research project addresses these concerns by developing fairness-aware deep learning models to diagnose **eczema** from dermatoscopic images, with a specific focus on:

- **Bias mitigation** across skin types
- **Fairness-aware architectural design**
- **Post-hoc calibration and optimization**
- **Cross-domain generalization**



## Core Contributions

- Developed a **Vision Transformer (ViT)** model with **Fitzpatrick skin type embeddings** for fairness-aware diagnosis.
- Implemented and evaluated a **ResNet-50 baseline** with parallel fairness integration.
- Integrated **Optuna** for automated hyperparameter tuning.
- Applied **temperature scaling** for post-hoc calibration.
- Measured **demographic parity** and **equalized odds** across skin tone subgroups.
- Conducted extensive benchmarking across the **PASSION** and **DermNet** datasets.



## Repository Structure


├── evaluate_models.ipynb               # Final evaluation notebook with fairness and calibration analysis

├── ai_dermatology_bias_fairness.ipynb # Model training and tuning notebook (ViT and ResNet architectures)
