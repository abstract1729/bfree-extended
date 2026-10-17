# B-Free Extended

This repository aims to **re-create the B-Free training pipeline** for generalizable AI-generated image detection and investigate potential improvements to its data-generation and training methodology. The project will begin by reconstructing the original approach described in the B-Free paper, including the preparation of pristine images, generation of manipulated images, and the application of training-time augmentations. Building on this baseline, we will explore three directions for expanding the training data: 

**(1) pristine image diversity**, by incorporating additional datasets, object categories, and scene types beyond the original data sources; 

**(2) editing diversity**, by investigating a broader range of manipulations, including localized and partial-object edits, appearance modifications, and background or scene changes; 

**(3) generative-model diversity**, by incorporating outputs from additional image-generation and editing models, including suitable diffusion-based and GAN-based approaches. 

These extensions will help us investigate how the diversity of training images and manipulation strategies affects detector generalization.

Beyond data generation, the repository will expand the **detector training pipeline** to support systematic experimentation with training configurations, data mixtures, augmentation strategies, and model generalization. This will include implementing the training workflow, validation and checkpointing, and evaluation procedures for assessing detection performance across diverse datasets and generative models. We will use controlled experiments and ablation studies to examine the contribution of individual data and training components, alongside robustness evaluations under common image transformations such as JPEG compression, resizing, and blurring. The original B-Free methodology will serve as the reference baseline, while proposed extensions will be developed and evaluated separately. **Re-creating the complete B-Free training pipeline is a key future-work objective**; the implementation will be refined as the original methodology is reconstructed and the results are validated against the paper.

## Reference

- **Official B-Free repository:** [https://github.com/grip-unina/B-Free](https://github.com/grip-unina/B-Free)
- **Research paper:** *A Bias-Free Training Paradigm for More General AI-generated Image Detection*[Link](https://arxiv.org/abs/2412.17671)
