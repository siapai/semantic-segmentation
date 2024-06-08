# CityScapes Semantic Segmentation Project
Welcome to our Semantic Segmentation project! This repository contains our implementation of various neural network architectures for multiclass semantic segmentation using the Cityscapes dataset.

## Key Points
- Dataset: Cityscapes
- Task: Multiclass segmentation
- Architectures: FCN, U-Net, DeepLabV3, LR-ASPP
- Loss Function: DiceLoss
- Framework: PyTorch with custom modules
  
## Architectures
- FCN: Replaces fully connected layers with convolutional layers for dense predictions.
- U-Net: Combines a contracting path for context and an expanding path for precise localization.
- DeepLabV3: Uses atrous convolutions and ASPP for multi-scale context.
- LR-ASPP: A lightweight version of RefineNet combined with ASPP for efficiency.

## Loss Function
- DiceLoss: Effective for handling class imbalance by focusing on the overlap between predicted and ground truth masks.

## Custom PyTorch Modules
- Dataset and DataLoader: Custom classes for loading and preprocessing Cityscapes.
- Model Architectures: Implementations of FCN, U-Net, DeepLabV3, and LR-ASPP.
- Training and Evaluation: Scripts for training, validation, testing, logging, and checkpointing.
