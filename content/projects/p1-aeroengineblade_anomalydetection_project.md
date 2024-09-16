---
title: 'Aero Engine Blade Anomaly Detection Project'
date: '2024-08-29T08:16:41+04:00'
draft: false
cover:
  image:
  alt:
  caption:
  relative: true
showtoc: true
---
In this project, we've applied the Masked Multi-scale Reconstruction (MMR) method which can be found [here](https://arxiv.org/pdf/2304.02216v2) on the Aero-engine Blade Anomaly Detection (AeBAD) dataset.  This model utilizes a Vision Transformer (ViT) based encoder-decoder architecture and Feature Pyramid Network to enhance the model’s ability to perform multi-scale reconstruction of image patches. The architecture looks as follows:

{{< figure src="/assets/aeroengine-blade-project-assets/MMR-Architecture.png">}}


The code can be found [here](https://github.com/ParteekSJ/Masked-Multiscale-Reconstruction). Below are the outputs of the trained model on the AeBAD dataset.

{{< figure src="/assets/aeroengine-blade-project-assets/output_video.gif">}}
{{< figure src="/assets/aeroengine-blade-project-assets/output_video_V2.gif">}}

