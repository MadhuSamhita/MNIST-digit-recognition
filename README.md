# Handwritten Digit Recognition using MNIST dataset

Data Loading: Loaded the MNIST dataset containing 60,000 training images and 10,000 test images of handwritten digits.

Data Preprocessing:
Reshaped the images to match the model's input requirements.
Converted pixel values to a scale between 0 and 1 by dividing by 255.

Model Architecture:
Constructed a Convolutional Neural Network (CNN) using TensorFlow and Keras.
Designed the network with layers for digit recognition, including a Flatten layer for data preparation, Dense layers for pattern recognition, and a Softmax layer for probability-based classification.

Model Compilation:
Compiled the model with the Adam optimizer and categorical cross-entropy loss.
Set accuracy as the evaluation metric.

Model Training:
Trained the model using the training images and labels.
Conducted training over 5 epochs with a batch size of 64.

Model Evaluation:
Evaluated the trained model's performance using the test images and labels.
Calculated and displayed the test accuracy.

Predictions and Visualization:
Made predictions on the test images using the trained model.
Derived predicted classes from prediction probabilities.
Created a classification report to showcase precision, recall, and F1-score.
Generated a confusion matrix to visualize the model's performance on each class.

Individual Prediction Visualization:
Chose a sample test image and its true label.
Made predictions on the selected image.
Displayed the image, true label, and predicted label using matplotlib.

Project Summary:
Developed a deep learning model that achieved remarkable accuracy in recognizing handwritten digits.
Explored and visualized model performance through classification reports, confusion matrices, and individual predictions.
Keywords: Data Loading, Data Preprocessing, CNN, Model Compilation, Model Training, Model Evaluation, Predictions, Visualization, Deep Learning, Handwritten Digit Recognition, MNIST Dataset.





Regenerate
