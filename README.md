
### Prerequisites
Ensure you have the following Python packages installed:
numpy
pandas
tensorflow (includes Keras)
matplotlib
You can install these packages using pip

### Explanation of the Code
## Data Loading and Preprocessing:

Load the Fashion MNIST dataset using fashion_mnist.load_data().
Reshape the data to include the channel dimension and normalize pixel values to be between 0 and 1.
One-hot encode the target labels.

## Model Architecture:

Define a CNN model with three convolutional layers and two max-pooling layers.
Flatten the output and use two dense layers, with the final dense layer having 10 units (for 10 classes) and a softmax activation function.

## Model Compilation:

Compile the model with the Adam optimizer and categorical crossentropy loss function.
Train the model using model.fit() with a validation split.


##Model Evaluation:

Evaluate the model on the test set to check accuracy.


##Prediction and Visualization:

Make predictions on randomly selected images from the test set.
Display the images along with their true and predicted labels.