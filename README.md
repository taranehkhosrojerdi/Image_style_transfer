This repository contains my codes for the final project of the Machine Learning course lectured by Dr. Fatemeh Seyedsalehi on Spring 2024 semester.

The project contains the below sections:

1. Implementation of a CNN from scratch:
   1.1. Convolutional layer implementation using PyTorch's Conv2D with forward and backward pass.
   1.2. Using Edge detection kernel, Grayscale kernel, Blurring kernel, and Sobels kernel with the implemented convolutional layer.
2. Neural style transfer with VGG19:
  2.1. Preprocessing with torchvision.transforms.
  2.2. Using torchvision for image classification.
  2.3. Visualizing feature-maps of each layer of VGG19.
  2.4. Defining Content and Style loss.
  2.5. Style transfer using the defined losses and optim.LBFGS optimizer.
