# Training-Neural-networks-with-Keras


**Part 1: Data Augmentation and Generalization Techniques**
- **1-a:** [L1 and L2 Regularization](https://colab.research.google.com/drive/1tcw4xU71uj2PNTIGbfuA6XtolX4jlwek?usp=sharing)
- **1-b:** [Dropout](https://colab.research.google.com/drive/1joJtMqnvgE4KtOhDms7LFfmDbH7P21IJ?usp=sharing)
- **1-c:** [Early Stopping](https://colab.research.google.com/drive/1sHBe0KdDujwoguFSPxN67OVw_mbTU2JO?usp=sharing)
- **1-d:** [Monte Carlo Dropout](https://colab.research.google.com/drive/1AzC6QDCBGxMyl5Z-ErLqxLX0sQnT_pqX?usp=sharing)
- **1-e:** [Various Initializations](https://colab.research.google.com/drive/1uR8JpdrrdB9xBWG6NuVm6DOttYMMUy8w?usp=sharing)
- **1-f:** [Batch Normalization](https://colab.research.google.com/drive/1vzjtckhqW8H4xjVAcB71LdkEYpoumZ3R?usp=sharing)
- **1-g:** [Custom Dropout, Custom Regularization](https://colab.research.google.com/drive/17_hMCg-8_Jv-IyNYAXK8PWPNKErAW7cX?usp=sharing)
- **1-h:** [Using Callbacks and TensorBoard](https://colab.research.google.com/drive/1zhvEmPYij4TcwSBWI248f62eV9osX-jI?usp=sharing)
- **1-i:** [Using Keras Tuner](https://colab.research.google.com/drive/1nTC2sa40ne1KtKcmNP2BCCHWWYdBt-q4?usp=sharing)
- **1-j:** [Using KerasCV Data Augmentation](https://colab.research.google.com/drive/1bf40AN0xx6LmVNsMd3LFa9gXq6H_doFZ?usp=sharing)
- **1-k:** [Data Augmentation for Multiple Data Types](https://colab.research.google.com/drive/1_lNnpo0xpgoWvtPSZ_08yfkgXrtIikXV?usp=sharing)
- **1-l:** [Demonstrating Fastai Data Augmentation](https://colab.research.google.com/drive/1wuN_TDfVufL33aqST4vQp2HzdxgfSYmn?usp=sharing)

[**Part 2: Advanced Keras Deep Learning Constructs**](https://colab.research.google.com/drive/16XL_GCMcE_vQTHkk6VihZ00L6HmRyvyl?usp=sharing)


# Data Augmentation, Regularization, and Advanced Keras Constructs Assignment

> 📅 Submission Locked: **April 13, 11:59 PM**  
> 🎥 Video Walkthrough: A detailed explanation for each Colab notebook is provided along with code execution.

---

## 📚 Assignment Structure

This repository contains multiple organized Google Colab notebooks divided into **two main parts**:

---

## 🧩 Part 1: Data Augmentation and Generalization Techniques

In this part, we explore various **regularization**, **initialization**, and **data augmentation** strategies using TensorFlow and Keras.

Each technique is demonstrated through separate or logically grouped Colab notebooks.

### Covered Topics:

- **Regularization Techniques**
  - L1 Regularization
  - L2 Regularization
  - Dropout
  - EarlyStopping
  - Monte Carlo Dropout
  - Batch Normalization
  - Custom Dropout Layers
  - Custom Regularization Functions
- **Weight Initialization Techniques**
  - Various initialization strategies (Glorot, He initialization, etc.)
  - When and why to use specific initializers
- **Callbacks and Monitoring**
  - TensorBoard Integration
  - Keras Tuner for Hyperparameter Optimization
- **Data Augmentation**
  - KerasCV Data Augmentation Pipelines
  - Image Augmentation (rotation, flipping, brightness adjustments, etc.)
  - Video Augmentation
  - Text Augmentation using NLPaug
  - Time-Series Augmentation
  - Tabular Data Augmentation
  - Speech Data Augmentation
  - Document Image Augmentation
- **Augmentation Libraries Used**
  - [AugLy by Facebook Research](https://github.com/facebookresearch/AugLy)
  - [fastai Data Augmentation](https://github.com/fastai/fastbook/blob/master/07_sizing_and_tta.ipynb)
  - [Awesome Data Augmentation Techniques](https://brunokrinski.github.io/awesome-data-augmentation/)

---

## 🧠 Part 2: Advanced Keras Deep Learning Constructs

This part demonstrates the power of custom deep learning components using Keras' low-level APIs.

Each concept is clearly explained and annotated inside Colab notebooks.

### Covered Concepts:

- **Custom Learning Rate Schedulers**
  - OneCycleScheduler and custom schedulers
- **Custom Dropout Layers**
  - Implementation of MCAlphaDropout
- **Custom Normalization Layers**
  - Example: MaxNormDense Layer
- **TensorBoard Monitoring**
  - Integrating custom scalars, graphs, and training metrics
- **Custom Loss Functions**
  - Example: Huber Loss
- **Custom Activation Functions**
  - Example: Leaky ReLU
- **Custom Initializers**
  - Example: MyGlorotInitializer
- **Custom Regularizers**
  - Example: MyL1Regularizer
- **Custom Weight Constraints**
  - Example: MyPositiveWeights
- **Custom Metrics**
  - Example: Huber Metric
- **Custom Layers**
  - Examples: ExponentialLayer, MyDense, AddGaussianNoise, Custom Layer Normalization
- **Custom Models**
  - Example: Residual Regressor with Residual Blocks
- **Custom Optimizers**
  - Example: MyMomentumOptimizer
- **Custom Training Loops**
  - Full implementation from scratch for Fashion MNIST dataset


