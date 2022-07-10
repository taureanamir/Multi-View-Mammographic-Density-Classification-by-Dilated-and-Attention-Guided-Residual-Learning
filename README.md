# Multi-View-Mammographic-Density-Classification-by-Dilated-and-Attention-Guided-Residual-Learning

## Overview
This repo consists the keras implementation of the model presented in paper
**Multi-View Mammographic Density Classification by Dilated and Attention-Guided Residual Learning**. Here's the [link](https://ieeexplore.ieee.org/document/8978513) to the full paper.

In this implementation, I've created a two-branch model with the ResNet50 as the base model. Each branch is initialized with pretrained ImageNet weights.

## Artifacts
1. Script to create the multi branch model.
    ```
    01-build-model.ipynb
    ```

2. Keras weights file of the model initialized with ImageNet weights.
    ```
    Multi-View-MMG-Density-DC-CA-v0.1.h5
    ```

3. Model architecture file in JSON format which can be loaded using keras. This file can be loaded using the weights in #2.
    ```
    Multi-View-MMG-Density-DC-CA-v0.1.json
    ```

The model architecture can be visualized in ```Multi-View-MMG-Density-DC-CA-v0.1.png```.
## References
1. The ResNet50 model implementation is adapted from [FChollet](https://github.com/fchollet/deep-learning-models/blob/master/resnet50.py)

