MNIST Digit Classifier using Convolutional Neural Networks (CNNs)

Objective:
To build a CNN model to classify handwritten digits from the MNIST dataset.

Implementation:

Libraries Used:

tensorflow: For building and training the CNN model.
matplotlib: For visualizing the test images and predictions.
Steps:

Load and Preprocess Data:
The MNIST dataset is loaded, normalized, and reshaped to fit the input format required by the CNN.

CNN Model Design:
A CNN model is constructed with two convolutional layers, followed by max pooling, flattening, and dense layers. The final layer uses softmax for classification.

Model Training and Evaluation:
The model is trained using categorical cross-entropy loss and the Adam optimizer. It’s evaluated on a test set for accuracy.

Single Image Prediction:
The model is used to predict the digit in a single test image.

Design Choices:

Using a small CNN architecture allows for quick training while still achieving good accuracy.
Softmax activation in the final layer ensures probabilistic outputs for classification.
Challenges Faced:

Balancing the number of layers and model complexity was important to ensure good performance without overfitting.
