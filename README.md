# SAM4UDASS: When SAM meets unsupervised domain adaptive segmantic segmentation

This is the official implementation of our paper "SAM4UDASS: When SAM meets unsupervised domain adaptive segmantic segmentation".

## Abstract

Semantic segmentation plays a critical role in enabling intelligent vehicles to comprehend their surrounding environments. However, deep learning-based methods usually perform poorly in domain shift scenarios due to the lack of labeled data for training. Unsupervised domain adaptation (UDA) techniques have emerged to bridge the gap across different driving scenes and enhance model performance on unlabeled target environments. Although self-training UDA methods have achieved state-of-the-art (SOTA) results, the challenge of generating precise pseudo-labels persists. These pseudo-labels tend to favor majority classes, consequently sacrificing the performance of rare classes or small objects like traffic lights and signs. To address this challenge, we introduce SAM4UDASS, a novel approach that incorporates the Segment Anything Model (SAM) into self-training UDA methods for refining pseudo-labels. It involves Semantic-Guided Mask Labeling, which assigns semantic labels to unlabeled SAM masks using UDA pseudo-labels. Furthermore, we devise fusion strategy aimed at mitigating semantic granularity inconsistency between SAM masks and the target domain. SAM4UDASS innovatively integrate segmentation foundation model SAM with UDA for semantic segmentation in driving scenes and seamlessly complements self-training UDA methods. Extensive experiments on synthetic-to-real, normal-to-adverse, and pinhole-to-panoramic driving datasets demonstrate its effectiveness. It brings
more than 3% mIoU gains on GTA5-to-Cityscapes, SYNTHIA-to-Cityscapes, and Cityscapes-to-ACDC when using DAFormer and achieves SOTA when using MIC. The code is available at https://github.com/ywher/SAM4UDASS.

## Method Overview


## Environment Setup

## Dataset Preparation

## Usage Example

## Acknowledgement

## Citation

> TBD

## Concate

Weihao Yan: weihao_yan@outlook.com
