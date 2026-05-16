# Assignment-Module-5_Part-2_Parul-Mital

# Part 2: Computer Vision Problem Formulation and CNN Prototype

 

## Problem Statement

The goal of this project is to build a CNN model to classify images into different surface conditions such as normal, dent, scratch, and stain.

 

## Problem Identification

This is an image classification problem since each image belongs to one class. There are no bounding boxes or pixel-level labels, so classification is the appropriate approach.

 

## Dataset Exploration

The dataset contains four categories: normal, dent, scratch, and stain. Each class has a similar number of images, making the dataset balanced. Sample images were reviewed to understand visual differences between these categories.

 

## Image Preprocessing

Images were resized to a fixed size of 128x128. Pixel values were normalized between 0 and 1. The labels were converted into numerical form. The dataset was split into training and testing sets.

 

## CNN Model Creation

A convolutional neural network was used to process the images. Convolution layers help detect patterns, pooling layers reduce size, and dense layers perform classification. The final layer uses softmax activation to predict the class.

 

## Model Training and Evaluation

The model was trained using the training dataset and evaluated on test data. Accuracy improved during training, and the model was able to classify most images correctly. A confusion matrix was used to analyze prediction performance.

 

## Hyperparameter Experimentation

The model was trained for 10 epochs initially. Later, the number of epochs was increased to 15. This improved learning but also showed signs of overfitting.

 

## CNN Concept Explanation

Convolution extracts important features from images such as edges and textures. Pooling reduces image size while keeping key information. ReLU helps the model learn complex patterns. CNNs perform better than regular neural networks because they understand spatial relationships in images.

 

## Business Use Case Mapping

This model can be used in manufacturing to detect defects during quality inspection. It helps identify scratches, dents, or stains automatically, reducing manual work.

 

## Conclusion

The CNN model successfully learned visual patterns and classified images into different categories. This shows how CNNs can be used effectively in image-based applications.

 

## Repository Structure
part-2-cnn-computer-vision/ │ ├── README.md ├── notebook.ipynb ├── requirements.txt ├── sample_predictions/ │   └── prediction_outputs.png └── results/ ├── accuracy_loss_curves.png └── confusion_matrix.png
