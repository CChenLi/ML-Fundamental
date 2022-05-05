# ML-Fundamental
Machine learning algorithm fundamental knowledge, Including code implementation notes and experiments. Most of the works are based on the assignment in Columbia University, See **Acknowledgement** of each notebook

## [Impement Trainable MLP with numpy](https://github.com/CChenLi/ML-Fundamental/blob/main/ML/MLP_implementation.ipynb)
- Implementing feedforward neural network with numpy
- Implementing **Backpropogation** to train the model
- Hand-write gradient calculation for backpropogation

## [Optimizer Implementation and Understand Their Features](https://github.com/CChenLi/ML-Fundamental/blob/main/ML/optimizer.ipynb)
- Implementation of common optimizers:
  - **Gradient Descent**, **SGD**, **SGD + Momentum**, **AdaGrad**, **ADAM**
  - Intuition behind each optimizer
- Test the performance of each optimizers on test functions:
  - **bowl**, **mult**, **monkey**, **matyas**, **Easom**
- To test and compare each optimizer when 
  - Contains **Local mins**
  - Contains **Saddle**
  - Hyperparameter is wrong

## [Convolution and Fourier Transform](https://github.com/CChenLi/ML-Fundamental/blob/main/ML/Conv_Fourier.ipynb)
- Fundamental knowledge of convolution
- Implement Conv2D with Numpy
- Applications and classic filters including
  - Image Denoising
  - Edge Detection
- Application of Fourier transform on image
  - Convolution in time space is multiplication in frequency space
  - Convolution in frequency space is multiplication in time space
  - When Kernel is large, multiplication in Fourier space can enhance efficiency

## [GAN](https://github.com/CChenLi/ML-Fundamental/blob/main/ML/GAN.ipynb)
- Common Generative adversarial network on Minist dataset, nothing special

## [VAE](https://github.com/CChenLi/ML-Fundamental/blob/main/ML/VAE.ipynb)
- Common Variational auto encoder on Minist dataset, nothing special

