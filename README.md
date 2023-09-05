# SAM4UDASS: When SAM meets unsupervised domain adaptive segmantic segmentation

This is the official implementation of our paper "SAM4UDASS: When SAM meets unsupervised domain adaptive segmantic segmentation".

## Abstract

Semantic segmentation plays a critical role in
enabling intelligent vehicles to comprehend their surrounding environments.
However, deep learning-based methods usually perform poorly in domain shift
scenarios due to the lack of labeled data for training. Unsupervised domain
adaptation (UDA) techniques have emerged to bridge the gap across different
driving scenes and enhance model performance on unlabeled target environments.
Although self-training UDA methods have achieved state-of-the-art results, the
challenge of generating precise pseudo-labels persists. These pseudo-labels
tend to favor majority classes, consequently sacrificing the performance of
rare classes or small objects like traffic lights and signs. To address this
challenge, we introduce SAM4UDASS, a novel approach that incorporates the
Segment Anything Model (SAM) into self-training UDA methods for refining
pseudo-labels. It involves Semantic-Guided Mask Labeling, which assigns
semantic labels to unlabeled SAM masks using UDA pseudo-labels. Furthermore, we
devise fusion strategies aimed at mitigating semantic granularity inconsistency
between SAM masks and the target domain. SAM4UDASS innovatively integrate SAM
with UDA for semantic segmentation in driving scenes and seamlessly complements
existing self-training UDA methodologies. Extensive experiments on
synthetic-to-real and normal-to-adverse driving datasets demonstrate its
effectiveness. It brings more than 3% mIoU gains on GTA5-to-Cityscapes,
SYNTHIA-to-Cityscapes, and Cityscapes-to-ACDC when using DAFormer and achieves
SOTA when using MIC. The code will be available at
https://github.com/ywher/SAM4UDASS.

## Method Overview

## Environment Setup

## Dataset Preparation

## Usage Example

## Acknowledgement

## Citation

> TBD

## Concate

Weihao Yan: weihao_yan@outlook.com
