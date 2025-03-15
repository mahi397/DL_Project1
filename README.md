# Employing ResNet Architecture for CIFAR-10 Classification

This repository houses the codebase for Deep Learning Project #1.

The final model is in this notebook: [Modified Resnet-34](https://github.com/mahi397/Employing-ResNet-Architecture-for-CIFAR-10-Classification/blob/main/notebooks/rn_34_mod.ipynb)

The model has been trained on the CIFAR-10 dataset and tested on the same dataset.
Further, its predictions have been generated for the unlabeled dataset provided for this project, which are located here: [Output CSV file](https://github.com/mahi397/Employing-ResNet-Architecture-for-CIFAR-10-Classification/blob/main/results/rn_34_output.csv)

The final model checkpoints have been saved here: [Final checkpoint](https://github.com/mahi397/Employing-ResNet-Architecture-for-CIFAR-10-Classification/blob/main/models/resnet_34_best.pth)

Here is our model at a glance:

* Number of trainable parameters: 4,525,066
* Number of epochs trained for: 100
* Loss: CrossEntropyLoss
* Optimizer: Stochastic Gradient Descent
* Learning Rate: 0.1
* Momentum: 0.9
* Weight Decay: 5e-4
* Learning Rate Schedule: Cosine Annealing
* Dropout Probability: 0.2

==> Performance:
* Training Accuracy: 99.845%
* Validation Accuracy: 94.13%

The Jupyter Notebooks for our models can be found inside `models/`.

