# DynamicSeg
DynamicSeg: Unsupervised image segmentation with dynamic weighted loss functions for accurate and scalable results.

# DynamicSeg: Unsupervised Image Segmentation with Dynamic Weighted Loss Function

## Overview
Image segmentation serves as the cornerstone for numerous computer vision tasks, necessitating pixel-wise understanding for accurate target achievement. While supervised deep learning models show promising performance, their reliance on extensive pixel-level annotations limits scalability and applicability. This project introduces an improved version of an unsupervised Convolutional Neural Network (CNN)-based algorithm for image segmentation. Unlike conventional approaches employing constant weight factors, our method employs a novel dynamic weighting scheme, facilitating automatic parameter adjustment for enhanced segmentation without manual intervention.

## Key Features
- **Dynamic Weighted Loss Function:** Automatically adjusts the balance between feature similarity and spatial continuity, ensuring flexible parameter updates.
- **Unsupervised Learning:** Segmentation without the need for extensive manual annotations.
- **Flexible and Scalable:** Adaptable to various datasets and image complexities.

## Methodology
The proposed dynamic weighting scheme prioritizes either feature similarity or spatial continuity criteria dynamically during training iterations, leading to a balanced segmentation. This dynamic approach eliminates the need for manual parameter tuning, enhancing segmentation accuracy across different datasets.

## Experimental Results
- **Quantitative Evaluation:** Outperforms existing unsupervised segmentation approaches on benchmark datasets.
- **Qualitative Assessment:** Produces semantically meaningful segmentation results, highlighting its efficacy in various application contexts.

## Installation
```bash
git clone https://github.com/bijou-bijou/DynamicSeg.git
cd DynamicSeg
# Set up your environment and dependencies
