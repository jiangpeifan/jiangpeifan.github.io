---
title: "<font color='000000'>third author |</font> SeisFusion: Constrained Diffusion Model With Input Guidance for 3-D Seismic Data Interpolation and Reconstruction"
collection: publications
permalink: /publication/2024-09-17-SeisFusion
excerpt: '3-D Seismic Data Interpolation and Reconstruction Using Diffusion Model.'
date: 2024-09-17
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
# paperurl: ''
---

## Abstract

Seismic data often suffer from missing traces, and traditional reconstruction methods are cumbersome in parameterization and struggle to handle large-scale missing data. While deep learning has shown powerful reconstruction capabilities, convolutional neural networks’ (CNNs) point-to-point reconstruction may not fully cover the distribution of the entire dataset and may suffer performance degradation under complex missing patterns. In response to this challenge, we propose a novel diffusion model reconstruction framework tailored for 3-D seismic data. To facilitate 3-D seismic data reconstruction using diffusion models, we introduce conditional constraints into the diffusion model, constraining the generated data of the diffusion model based on the input data to be reconstructed. We introduce a 3-D neural network architecture into the diffusion model and refine the diffusion model’s generation process by incorporating existing parts of the data into the generation process, resulting in reconstructions with higher consistency. Through ablation studies determining optimal parameter values, although the sampling time is longer, our method exhibits superior reconstruction accuracy when applied to both field datasets and synthetic datasets, effectively addressing a wide range of complex missing patterns.
## Paper

[SeisFusion: Constrained Diffusion Model With Input Guidance for 3-D Seismic Data Interpolation and Reconstruction](https://ieeexplore.ieee.org/abstract/document/10681481)


## Code

### The code is available at [here.](https://github.com/WAL-l/SeisFusion)

## Cite


### if this work is helpful for you, please cite

```
@article{wang2024seisfusion,
  title={SeisFusion: Constrained Diffusion Model with Input Guidance for 3D Seismic Data Interpolation and Reconstruction},
  author={Wang, Shuang and Deng, Fei and Jiang, Peifan and Gong, Zishan and Wei, Xiaolin and Wang, Yuqing},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2024},
  publisher={IEEE}
}
````

