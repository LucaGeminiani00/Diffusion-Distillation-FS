# Progressive Distillation of Diffusion models for Time Series synthesis 

<div align="center">
  <img src="Assets/tsne.png" alt="Image 1" width="200">
  <img src="Assets/pca.png" alt="Image 2" width="200">
  <img src="Assets/kernel.png" alt="Image 3" width="200">
</div>

<div align="center">
  <a href="https://github.com/LucaGeminiani00/Diffusion-Distillation-WL/releases">
    <img src="https://img.shields.io/github/v/release/LucaGeminiani00/Diffusion-Distillation-WL" alt="Release">
  </a>
  <a href="https://github.com/LucaGeminiani00/Diffusion-Distillation-WL/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/LucaGeminiani00/Diffusion-Distillation-WL/build.yml" alt="Build Status">
  </a>
  <a href="https://github.com/LucaGeminiani00/Diffusion-Distillation-WL/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/LucaGeminiani00/Diffusion-Distillation-WL" alt="License">
  </a>
</div>


## Project Description 

This repository provides an extension of the Diffusion TS model, proposed in https://github.com/Y-debug-sys/Diffusion-TS, which changes the underlying logic for learning the Seasonal and Trend components of the model; it also provides an implementation of Progressive Distillation, extending the methodology to the Time Series domain. 

Distillation of the originally trained model reduces by half the Diffusion step of the teacher, rendering the original network into a narrower, faster one. The training procedure follows from what is originally proposed in "Progressive Distillation for Fast Sampling of Diffusion Models", by Tim Salimans and Jonathan Ho https://openreview.net/forum?id=TIdIXIpzhoI . 

This is work for my Master's Thesis, which is still in progress, thus the code will still be most likely subject to changes / additions. The attached Jupyter Notebook can be run in Google Colab, obtaining reasonable computational times even with the weakest GPUs available. 
## Acknowledgements

I made use of the following github repos for their valuable code base:

https://github.com/lucidrains/denoising-diffusion-pytorch

https://github.com/cientgu/VQ-Diffusion

https://github.com/XiangLi1999/Diffusion-LM

https://github.com/philipperemy/n-beats

https://github.com/salesforce/ETSformer

https://github.com/ermongroup/CSDI

https://github.com/jsyoon0823/TimeGAN
