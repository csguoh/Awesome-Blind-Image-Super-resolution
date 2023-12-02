# Awesome-Blind-Image-Super-resolution

This repository collects recent work on blind image super-resolution, including zero-shot SR, classic blind image SR and real-SR. 

Feel free to pose issues if there is any missing work ;)

## Classic blind image SR

[TPAMI]Blind Image Super-Resolution: A Survey and Beyond

[NeurIPS2019]Blind Super-Resolution Kernel Estimation using an Internal-GAN

[ICCV2023]Learning Correction Filter via Degradation-Adaptive Regression for Blind Single Image Super-Resolution

## Zero-shot/Few-shot SR

> Zero-shot SR tasks train a specific SR model for each LR input, which is degraded by unknow corruption. 
Therefore, these methods perform train and test with every single image,i.e., batchsize is always 1.
There are not training-tesing splits as classic ML setting, but only one type datasets which is used for both trainnig and testing.
Some commonly used datasets including DIV2KRK, NTIRE2017, NTIRE2018. And the RealSR dataset is usually adopted for visually comparison.
Some representatives includs ZSSR and KernerGAN. Following are some related works in recent years.


[CVPR2018]Zero-Shot Super-Resolution Using Deep Internal Learning

[ICCV2019]Blind Super-Resolution With Iterative Kernel Correction

[CVPS2021]Zero-Shot Dual-Lens Super-Resolution

[CVPR2022]Meta-Transfer Learning for Zero-Shot Super-Resolution

[ICLR2023]Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model

[TIP2023]Meta-Learning based Degradation Representation for Blind Super-Resolution

[ICCV2023]MetaF2N: Blind Image Super-Resolution by Learning Efficient Model Adaptation from Faces

[NeurIPS2023]Efficient Test-Time Adaptation for Super-Resolution with Second-Order Degradation and Reconstruction

## Real-SR

> Real-SR, as a incresingly popular research topic in recent years, aiming to deal with LR image which is corrupted by real-world degradations.
There are explicit train-test spilt in the Real-SR task. Some recent works usually use DIV2K, Flickr2K and OST datasets for training. The testing datasets 
usually uses the validation set from DIV2K (100 images), and use three different levels of degradation to genrerate differnet real-world LR images. 
Following are some recent works.  


[ICCV2019]Toward Real-World Single Image Super-Resolution: A New Benchmark and a New Model

[CVPR2021]Real-ESRGAN: Training Real-World Blind Super-Resolution with Pure Synthetic Data

[CVPR2022]A Closer Look at Blind Super-Resolution: Degradation Models, Baselines, and Performance Upper Bounds

[ECCV2022]Efficient and Degradation-Adaptive Network for Real-World Image Super-Resolution

[Arixv]Evaluating the Generalization Ability of Super-Resolution Networks

[NeruIPS2023]Real-World Image Super-Resolution as Multi-Task Learning

[ICLR2024,under-review]SEAL: A Framework for Systematic Evaluation of Real-World Super-Resolution




# Others

[NeurIPS2023]PromptRestorer: A Prompting Image Restoration Method with Degradation Perception

