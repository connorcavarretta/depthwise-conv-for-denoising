# depthwise-conv-for-denoising
Code for our paper: "Depth-wise Convolution is All We Need for a Lightweight Deep Learning Model for Image Denoising"

---

##  Overview

Image denoising aims to remove additive Gaussian noise from images and has been studied extensively over the last five decades. While recent deep learning approaches have achieved state-of-the-art results, their large model sizes often limit their deployment on resource-constrained platforms such as spaceborne computers or IoT devices.

This repository provides the implementation of a lightweight CNN for image denoising based on depth-wise separable convolutions. Despite having only **~1.2M parameters**, our model achieves performance comparable to state-of-the-art methods.

---

##  Key Features

- ✅ Lightweight architecture with only ~1.2M parameters
- ✅ Depth-wise and dilated depth-wise convolutions in a modified ResNet-style backbone
- ✅ Designed for efficient denoising in low-resource environments
- ✅ Competitive performance on standard benchmarks

---
