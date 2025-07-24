# Fetal Bladder Segmentation

This repository contains code and resources for segmenting the fetal bladder from medical images using **nnU-Net V2**, a state-of-the-art deep learning framework for medical image segmentation.

## About nnU-Net V2

- **nnU-Net V2** is an automated, self-configuring segmentation framework that adapts its architecture and training pipeline to the given dataset.
- It supports 2D, 3D full-resolution, and 3D low-resolution U-Net architectures.
- nnU-Net V2 requires minimal manual tuning and achieves top results across many medical segmentation tasks.
- This project uses the 3D full-resolution model configuration for fetal bladder segmentation.

## Dataset and Images

- The dataset consists of fetal MRI images with corresponding bladder segmentation masks.
- Images are in NIfTI (`.nii`) format, widely used for 3D medical imaging.
- This repo includes the `first_dataset.ipynb` notebook showcasing preprocessing, training, and evaluation on the initial dataset.
- Larger datasets and label folders are not included here but can be linked or added separately.

## Usage

1. Clone the repo:

   ```bash
   git clone https://github.com/rutvik-dudhat/fetal-bladder-segmentation.git
   cd fetal-bladder-segmentation
