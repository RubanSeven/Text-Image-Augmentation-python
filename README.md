# Text Image Augmentation

[![Build Status](https://travis-ci.org/Canjie-Luo/Text-Image-Augmentation.svg?branch=master)](https://travis-ci.org/Canjie-Luo/Text-Image-Augmentation)

A tool for scene text data augmentation. We provide the tool to avoid overfitting and gain robustness of models.

We are now focusing on the shape of the cropped scene text image. 

## Requirements

- [Python](https://www.python.org/) 3.6.4
- [Numpy](https://numpy.org/) 1.14.0

## Demo

- Distortion

![](imgs/distort.gif) 

- Stretch

![](imgs/stretch.gif)

- Perspective

![](imgs/perspective.gif)

## Speed

To transform an image with size (H:64, W:200), it takes less than 14ms using a 2.5GHz CPU. It is possible to accelerate the process by calling multi-process batch samplers in an on-the-fly manner, such as setting [**\"num_workers\"**](https://pytorch.org/docs/0.3.1/data.html?highlight=dataset#torch.utils.data.DataLoader) in [PyTorch](https://pytorch.org/docs/0.3.1/data.html?highlight=dataset#torch.utils.data.DataLoader).

## Attention
Modify from https://github.com/Canjie-Luo/Text-Image-Augmentation.git.
