# README

## Deep Learning Project 3 - Adversarial Attacks on ResNet-34

### Project Overview
This project implements various adversarial attacks on a pre-trained ResNet-34 model using the ImageNet dataset. The goal is to evaluate the robustness of the model against different perturbation strategies, including FGSM, PGD, Auto-PGD, Patch-PGD, Gaussian Noise, and Jitter attacks.

### Requirements
- Python 3.10+
- PyTorch
- torchvision
- numpy
- matplotlib
- scikit-learn

### Installation
```bash
pip install torch torchvision numpy matplotlib scikit-learn
```

### Project Structure
```
.
├── codezero_dl_project3.py    # Main implementation script
├── TestDataSet/               # Test dataset directory
├── AdversarialTestSet_*/      # Generated adversarial examples
├── images/                    # Visualization and results images
├── pred.csv                   # Prediction results
└── CodeZero_Project3_Report.pdf # Project report
```

### Implementation Details
- **Base Model**: ResNet-34
- **Dataset**: ImageNet
- **Attack Methods**:
  - FGSM (Fast Gradient Sign Method)
  - PGD (Projected Gradient Descent)
  - Auto-PGD
  - Patch-PGD
  - Gaussian Noise
  - Jitter Attack

### Key Features
- Comprehensive evaluation of adversarial attacks
- Visualization of original and adversarial images
- Performance metrics (Top-1 and Top-5 accuracy)
- Transferability analysis on EfficientNet-V2-S

### Results
- **Clean Data Performance**: Top-1: 76.0%, Top-5: 94.2%
- **Adversarial Performance**: Varies by attack method (see results section)
- **Transferability**: Evaluated on EfficientNet-V2-S

### Report Contents
- Project overview and findings summary
- Methodology section
- Model design process
- Training approach
- Hyperparameter choices and rationale
- Lessons learned
- Results section
- Citations

### Repository Guidelines
- Code is well-documented
- Results are reproducible
- Visualizations are included
- Performance metrics are clearly printed 