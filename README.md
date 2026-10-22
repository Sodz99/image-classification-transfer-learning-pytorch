# Image Classification Model using Transfer Learning in PyTorch

- To understand the transfer learning and ResNet model.

## Overview
Transfer Learning is a machine learning algorithm where we reuse a pre-trained model as the starting point for a model on a new task. The intuition behind transfer learning for image classification is that if a model is trained on a large and general enough dataset, this model will effectively serve as a generic model of the visual world. In this project, the ResNet model has been used as a pre-trained model for image classification in PyTorch. The images have been classified into classes of social security cards, driving licenses, and others. If you haven't visited already, here is the previous project of the series PyTorch Project to Build a LSTM Text Classification Model

## Data
Dataset used in this project are images of driving licenses, social security, and others categorized into respective categories. The images are of different shapes and sizes which are preprocessed before modeling.

_Data is not included in this repository._

## Approach
- Data Loading
- Data Preprocessing ○ Resizing and scaling the images ○ Encoding the class labels
- Model Building and Training ○ ResNet model building in PyTorch

Modular Code Overview

Once you unzip the pytorch_resnet.zip file, you can find the following folders within it.
1. Input
2. ML_Pipeline
3. Notebook
4. Output
5. Engine.py
6. Readme.md
7. requirements.txt
1. The Input folder contains the data that we have for analysis. In our case, it contains training data and testing of images to be classified
2. The Notebook folder contains the jupyter notebook file of the project
3. The ML_pipeline is a folder that contains all the functions put into different python files, which are appropriately named. These python functions are then called inside the Engine.py file
4. The Output folder contains the saved model
5. The requirements.txt file has all the required libraries with respective versions. Kindly install the file by using the command pip install -r requirements.txt
6. All the instructions for running the code are present in Readme.md file

## Tech stack
➔ Language: Python ➔ Libraries: pytorch,     pandas,    matplotlib,   numpy,   opnecv_python_headless, torchvision

## How to run
```bash
pip install -r pytorch_resnet/requirements.txt
```
Notebooks: [`TransferLearning_CNN.ipynb`](Notebook/TransferLearning_CNN.ipynb), [`TransferLearning_CNN.ipynb`](pytorch_resnet/Notebook/TransferLearning_CNN.ipynb)

## Project structure
```
.gitignore
Notebook/
  TransferLearning_CNN.ipynb
README.md
pytorch_resnet/
  Engine.py
  MLPipeline/
    CreateDataset.py
    ResNet_Model.py
    Train.py
  Notebook/
    TransferLearning_CNN.ipynb
  Readme.md
  requirements.txt
```

## Credits
Based on a ProjectPro guided project.
