# Vision-Transformer

This repository is improved for a classification problem of the MNIST dataset using [Vision Transformer](https://arxiv.org/abs/2010.11929v2). There are a total of 10 classes in this dataset including handwritten digits, and all images' sizes are 28x28.

During this study, a transformer architecture has been utilized. A simple way of creating the model can be seen here:

<a href="url">
  <img src="https://github.com/ekaraali/Vision-Transformer/blob/main/images/ViT.png?raw=true" height="320" width="470">
</a>

According to this architecture, input images are divided into 7x7 pieces so that positional encoding could be applied. At the end of the pachifying step, 4 patches are expected to have for each image.

# Introduction

This repo has a from-scratch Transformer that includes a self-attention mechanism, linear layers, and layer normalizations. A total of **10000** images are utilized to train the Vision Transformer.
  - The model is trained with the following parameters:
    - Loss function -> CrossEntropy Loss
    - Optimizer -> Adam
    - Learning rate -> 0.005
    - Batch size -> 256
    - Epoch number -> 5

All necessary functions and codes can be found in [google colab](https://github.com/ekaraali/Vision-Transformer/blob/main/Vision_Transformer.ipynb) folder, and the parameters can be updated by editing the related lines.

# Results

In this study, a decreasing loss curve is aimed to be achieved, and the following training loss curve is obtained for the provided parameters:

<a href="url">
  <img src="https://github.com/ekaraali/Vision-Transformer/blob/main/images/loss_curve.png?raw=true" height="350" width="470">
</a>


