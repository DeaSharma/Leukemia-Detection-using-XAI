# Leukemia-Detection-using-XAI
# CNN-based Leukemia Detection with GradCAM Visualization

This project focuses on developing a Convolutional Neural Network (CNN) model for the classification of leukemia images into two classes: "all" (referring to all cells) and "hem" (referring to immature white blood cells or hematopoietic cells). Additionally, the project includes the implementation of GradCAM (Gradient-weighted Class Activation Mapping) for visualizing the regions of the input images that the trained CNN model considers important for its predictions.

## Project Overview

The project consists of the following main steps:

1. **Data Preparation**: The dataset is loaded and split into training, validation, and test sets using scikit-learn's `train_test_split` function.

2. **CNN Model Creation**: A CNN model is defined using TensorFlow's Keras API. The model consists of convolutional layers, max-pooling layers, a flatten layer, and dense layers with a softmax output layer for binary classification.

3. **Model Training**: The CNN model is trained on the training data using the `fit` method. The training progress is visualized using accuracy and loss plots.

4. **Model Evaluation**: The trained model is evaluated on the test data, and performance metrics such as accuracy, precision, recall, and F1-score are calculated.

5. **GradCAM Visualization**: The GradCAM technique is implemented to visualize the regions of the input images that the CNN model focuses on for making its predictions.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/DeaSharma/Leukemia-Detection-using-XAI.git
 
   
