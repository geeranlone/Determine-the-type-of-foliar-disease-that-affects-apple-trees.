# Plant Pathology Image Classification

This project involves building a Convolutional Neural Network (CNN) model to classify images of plant diseases using TensorFlow and Keras. The model is trained on a dataset of images labeled as healthy or affected by various diseases (multiple diseases, rust, and scab).


## Installation

To run this project, you need to install the following dependencies. You can do this by running:

```
pip install -r requirements.txt
```

## Usage
## Data Preparation

Place your dataset in the specified directory structure.
Use the provided code to preprocess and organize your images into training and testing directories.
Training the Model

Execute the training code to fit the model on your dataset. The model will automatically save the best weights.
Testing the Model

After training, you can test the model with new images to predict their categories.
Data Preparation
Ensure your data is structured as follows:

```
Plant pathology/
    └── train/
        ├── healthy/
        ├── multiple_diseases/
        ├── rust/
        └── scab/
    └── test/

```
The script will preprocess the images, generate labels, and save them into corresponding folders.
## Model Architecture
The CNN model architecture is as follows:

Convolutional Layers: 4 layers with ReLU activation
Max Pooling: 2 layers
## Flatten Layer
Dense Layer: 4 output neurons with softmax activation
The model is compiled with Adam optimizer and categorical cross-entropy loss function.

## Results
After training, the model accuracy on the validation set was approximately 93.27%. Training and validation accuracy and loss plots can be visualized using Matplotlib.



## DATASET DOWNLOADED FROM: 
```
"https://www.kaggle.com/datasets/piantic/plantpathology-apple-dataset/download?datasetVersionNumber=1"
