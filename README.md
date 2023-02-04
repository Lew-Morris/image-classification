[![MIT/Apache 2.0](https://img.shields.io/badge/license-MIT%2FApache-blue.svg)](https://github.com/lew-morris/image-classification#license)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/lew-morris/image-classification/master)

# Classifying images in the Fashion-MNIST dataset

This was for an assignment as part of my computer vision module at university.

A convolutional neural network to classify images from the Fashion-MNIST dataset. On average, the network is able to 
achieve an accuracy of ~92, up from ~89% on the original. 

# Installation and Usage
This project is best viewed on 
[Google Colab](https://colab.research.google.com/drive/1AdxRQO7QljulNxcaOnlj53EARPiUFZ8u?usp=sharing). 
If this is being run on Colab, you will likely need to 
change the runtime type. This can be done by going to `Runtime` > `Change runtime type` > `GPU`. Otherwise, the 
training will take hours!

1. [Clone the repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
2. Install required libraries (if not using Colab) - [requirements](#requirements)
3. Train the network
4. Look at the results!

# Requirements
- tensorflow
- numpy
- matplotlib
- scikitlearn
- jupyter

To install these locally, run the command
`pip install tensorflow numpy matplotlib scikitlearn jupyter` in terminal. This can also be done using conda.

# License
This is dual-licensed under [MIT](LICENSE-MIT) and [APACHE](LICENSE-%20APACHE) licenses.

# Credit
Credits to [@radenjezic153](https://github.com/radenjezic153/Stat_ML/blob/master/project.ipynb) for building the basic framework which I was able to improve upon.
