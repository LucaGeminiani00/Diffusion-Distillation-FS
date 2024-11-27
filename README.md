
<div align="center">
  <img src="Assets/tsne.png" alt="Project Logo" width="200">
</div>

---

### Current Release

[![Release](https://img.shields.io/github/v/release/your-username/your-repo)](https://github.com/your-username/your-repo/releases)
[![Build Status](https://img.shields.io/github/actions/workflow/status/your-username/your-repo/build.yml)](https://github.com/your-username/your-repo/actions)
[![License](https://img.shields.io/github/license/your-username/your-repo)](LICENSE)




# Progressive Distillation of Diffusion models for Time Series synthesis 

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
