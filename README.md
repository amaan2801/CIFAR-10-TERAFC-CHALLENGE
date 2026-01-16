# CIFAR-10 Image Classification using Transfer Learning (PyTorch)

## Project Overview
# CIFAR-10 Image Classification using Transfer Learning (PyTorch)

## Project Overview
This project implements a level-wise image classification pipeline on the CIFAR-10 dataset using PyTorch and ResNet-18 transfer learning. The work is structured into four progressive levels, demonstrating improvements through fine-tuning, data augmentation, architectural customization, interpretability, and ensemble learning.

## Dataset
- Dataset: CIFAR-10
- Total Images: 60,000 (50,000 train + 10,000 test)
- Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

## Levels Implemented
### Level 1: Baseline Transfer Learning
- Pretrained ResNet-18
- Fine-tuned final layer and last ResNet block
- Saved model: models/level1.pth

### Level 2: Data Augmentation & Ablation Study
- Random crop, flip, normalization
- Comparison with/without augmentation
- Saved model: models/level2.pth

### Level 3: Custom Classifier + Grad-CAM
- Custom classification head
- Per-class accuracy
- Grad-CAM visualization
- Saved model: models/level3.pth

### Level 4: Ensemble Learning
- Ensemble of Level 2 and Level 3 models
- Improved accuracy
- Saved model: models/level4_ensemble.pth

## Requirements
- Python 3.8+
- PyTorch
- Torchvision
- Matplotlib

## How to Run
1. Open the notebook in Google Colab
2. Enable GPU
3. Run all cells sequentially

## Project Structure
├── data/
├── models/
├── CIFAR-10.ipynb
└── README.md


## Dataset
- Dataset: CIFAR-10
- Total Images: 60,000 (50,000 train + 10,000 test)
- Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

## Levels Implemented
### Level 1: Baseline Transfer Learning
- Pretrained ResNet-18
- Fine-tuned final layer and last ResNet block
- Saved model: models/level1.pth

### Level 2: Data Augmentation & Ablation Study
- Random crop, flip, normalization
- Comparison with/without augmentation
- Saved model: models/level2.pth

### Level 3: Custom Classifier + Grad-CAM
- Custom classification head
- Per-class accuracy
- Grad-CAM visualization
- Saved model: models/level3.pth

### Level 4: Ensemble Learning
- Ensemble of Level 2 and Level 3 models
- Improved accuracy
- Saved model: models/level4_ensemble.pth

## Requirements
- Python 3.8+
- PyTorch
- Torchvision
- Matplotlib

## How to Run
1. Open the notebook in Google Colab
2. Enable GPU
3. Run all cells sequentially

## Project Structure
├── data/
├── models/
├── CIFAR-10.ipynb
└── README.md
# CIFAR-10-TERAFC-CHALLENGE
This project implements a level-wise image classification pipeline on the CIFAR-10 dataset using PyTorch and ResNet-18 transfer learning. The work is structured into four progressive levels, demonstrating improvements through fine-tuning, data augmentation, architectural customization, interpretability, and ensemble learning.
