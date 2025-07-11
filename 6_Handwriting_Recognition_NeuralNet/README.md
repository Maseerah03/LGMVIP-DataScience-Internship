# Neural Network That Can Read Handwriting

This project was completed as part of my Data Science Internship at LetsGrowMore (October 2023 batch). The objective was to build a basic feedforward neural network that can recognize handwritten digits using the MNIST dataset. The project involves image preprocessing, model building, training, evaluation, and error analysis.

## Objective

To develop a multi-layer neural network that can classify handwritten digits (0–9) from grayscale images using the MNIST dataset. The network is trained on thousands of labeled digit images and evaluated for classification accuracy.

## Tools and Libraries Used

- Python  
- TensorFlow / Keras  
- matplotlib

## Summary of Work

- Loaded the MNIST dataset using Keras and reshaped the image data into a flat vector format (784 pixels per image).
- Normalized pixel values to fall within the range [0, 1] for faster convergence.
- Converted the digit labels into one-hot encoded vectors suitable for categorical classification.
- Visualized sample digits and their labels using matplotlib.
- Built a feedforward neural network with two hidden layers (512 neurons each) and dropout regularization to prevent overfitting.
- Compiled the model using categorical crossentropy loss and RMSprop optimizer.
- Trained the model for 10 epochs using a batch size of 100 and validated performance on test data.
- Evaluated the model’s accuracy and identified examples where predictions were incorrect.

## Key Outcomes

- Achieved high classification accuracy on unseen test data.
- Built a deep learning model from scratch using Keras Sequential API.
- Gained experience in image preprocessing, one-hot encoding, and dropout regularization.
- Conducted manual inspection of misclassified digits to better understand model performance.

## Files Included

- `Neural_Network_That_Can_Read_Handwriting.ipynb` – Google Colab notebook with full implementation and results.
- `README.md` – Project summary and documentation.

## Dataset

The dataset used is the publicly available **MNIST Handwritten Digit Dataset**, which contains 60,000 training and 10,000 test grayscale images of handwritten digits (28x28 pixels).  
Source: [MNIST Database](http://yann.lecun.com/exdb/mnist/)  
(Note: Dataset is accessed directly via Keras and not included in this repository.)

## Acknowledgement

This project was developed during my internship at LetsGrowMore under the guidance of Mr. Aman Kesarwani.
