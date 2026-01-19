# End-to-End PET Image Reconstruction via a Posterior-Mean Diffusion Model

[Project Website](https://yransun.github.io/PMDM/)

This is the official pytorch implementation of the deep leraning model PMDM for PET image reconstruction from sinograms. The paper has been accepted to ISBI 2026. The arxiv version of the paper is available [here](https://arxiv.org/abs/2503.08546).


## Code release
The code will be released soon. In the meantime, if you have any questions regarding our paper, please feel free to open a new issue here or send me an email! Thanks for your patience :).


## Abstract
Positron Emission Tomography (PET) is a functional imaging modality that enables the visualization of biochemical and physiological processes across various tissues. Recently, deep learning (DL)-based methods have demonstrated significant progress in directly mapping sinograms to PET images. However, regression-based DL models often yield overly smoothed reconstructions lacking of details (i.e., low distortion, low perceptual quality), whereas GAN-based and likelihood-based posterior sampling models tend to introduce undesirable artifacts in predictions (i.e., high distortion, high perceptual quality), limiting their clinical applicability. To achieve a robust perception–distortion tradeoff, we propose the Posterior-Mean Denoising Diffusion Model (PMDM-PET), a novel approach that builds upon a recently established mathematical theory to explore the closed-form expression of the perception–distortion function in diffusion model space for PET image reconstruction from sinograms. Specifically, PMDM-PET first obtained posterior-mean PET predictions under minimum mean square error (MSE), then optimally transports the distribution of them to the ground-truth PET images distribution. Experimental results demonstrate that PMDM-PET not only generates realistic PET images with possible minimum distortion and optimal perceptual quality but also outperforms five recent state-of-the-art (SOTA) DL baselines in both qualitative visual inspection and quantitative pixel-wise metrics PSNR (dB), SSIM, and NRMSE.


## Citing our work
If you find the paper useful in your research, please cite these:

                @article{sun2025posterior,
                  title={End-to-End PET Image Reconstruction via a Posterior-Mean Diffusion Model},
                  author={Sun, Yiran and Mawlawi, Osama},
                  journal={arXiv preprint arXiv:2503.08546},
                  year={2025}
                }
