# Dog Breed Classification

This project aims to classify dog breeds using deep learning techniques. It utilizes the Stanford Dogs Dataset, which contains images of 120 different dog breeds. The goal is to train models that can accurately predict the breed of a dog given an input image.

## Dataset

The Stanford Dogs Dataset is used for this project. It consists of 20,580 images belonging to 120 different dog breeds. The dataset is split into training (60%), validation (20%), and test (20%) sets.

## Models

Two pre-trained models are employed for this project:

1. ResNet50: A deep residual network with 50 layers, pre-trained on the ImageNet dataset.
2. VGG19: A deep convolutional neural network with 19 layers, pre-trained on the ImageNet dataset.

Transfer learning is utilized by initializing the models with pre-trained weights and fine-tuning them on the dog breed classification task.

## Requirements

To run this project, you need the following dependencies:

- Python 3.x
- PyTorch
- Torchvision
- Gradio (for the user interface)
