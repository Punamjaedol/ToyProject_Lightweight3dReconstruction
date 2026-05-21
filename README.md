# ToyProject_Lightweight3dReconstruction

Lightweight multi-view 3D reconstruction practice project using three input images. The repository includes data preprocessing scripts, custom encoder-decoder model implementations, point cloud reconstruction pipelines, Chamfer Distance-based training, and saved checkpoints/outputs.

## Overview
- **Models:** Custom Lightweight Encoder-Decoder Network
- **Input:** 3 multi-view images
- **Output:** Point cloud-based 3D reconstruction
- **Core Features:** lightweight architecture, iterative point refinement, Chamfer Distance loss, point density regularization
- **Included assets:** dataset preprocessing scripts, training/inference notebooks, saved checkpoints, and reconstruction outputs.

## Project Structure
- `custom3dreconstruction.ipynb`: main notebook containing model architecture, training pipeline, reconstruction experiments, and evaluation.


## Dataset
- **Format:** Multi-view image dataset
- **Contents:** Three-view image sets paired with ground truth point cloud data for supervised 3D reconstruction training.

## Requirements
Main packages used in this project:
- `torch`
- `torchvision`
- `numpy`
- `opencv-python`
- `matplotlib`
- `open3d`
- `pandas`
