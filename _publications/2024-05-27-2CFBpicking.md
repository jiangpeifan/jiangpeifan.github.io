---
title: "<*first author*> 3-D Seismic First Break Picking Based on Two-channel Mask Strategy"
collection: publications
permalink: /publication/2024-05-27-2CFBpicking
excerpt: 'Propose a two-channel mask strategy to improve the accuracy and generalization of first break picking'
date: 2024-05-27
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
# paperurl: ''
---

## Abstract

In recent years, much attention has been paid to using deep learning techniques for land seismic first break (FB) picking. Among these, the deep learning-based 3-D FB picking method has shown stronger noise resistance than the 2-D method, as it simultaneously considers the correlation of FBs in both crossline and inline directions. In existing studies, whether using 2-D or 3-D methods, they are often regarded as a binary semantic segmentation problem of pre- and post-first break (PPFB). The FB time is determined by dividing the image with a binary classification mask. However, due to the instability of the threshold setting for the PPFB mask strategy, different threshold values can yield distinct segmentation results. Improper threshold setting can result in continuous erroneous picking in localized traces. Considering this, we propose a two-channel (2C) mask strategy that utilizes the feature interaction between a strip-like FB range mask and a line-like FB preference mask to predict the confidence of FBs in seismic traces, thereby achieving high-precision FB picking. Additionally, to address the problem of insufficient network receptive field in the FB picking method via 3-D U-Net, we construct a 3-D FB picking network USwinNet based on Swin Transformer, which establishes a global receptive field through a multi-stage self-attention mechanism. Experimental results demonstrate that our method significantly improves the picking accuracy compared to existing methods. It also exhibits strong generalization capabilities, making it more suitable for practical engineering under complex geological conditions.

## Paper

[3-D Seismic First Break Picking Based on Two-channel Mask Strategy]( )

## Mask Strategy
![Mask Strategy](../images/FB/2CFB.png)


## Dataset

### The dataset implementation is [here.](https://github.com/jiangpeifan/2C-SeismicFBpicking)

## Cite


### if this work is helpful for you, please cite

```
Undergoing Review (Minor Revision)

````

