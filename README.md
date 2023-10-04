# Rishabh Simple Digit Recognizer

This project is a simple digit recognition neural network using Python and the MNIST dataset. It demonstrates how to train a neural network to recognize handwritten digits.

## Getting Started

### Prerequisites

Before running the notebook, make sure you have the following dependencies installed:

- Google Colab (for running the notebook)
- Python 3
- NumPy
- Matplotlib

### Dataset

You'll need to download the MNIST dataset and upload it to your Google Drive. You can download the dataset from [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/) and place it in the `mnist` directory in your Google Drive.

### Running the Notebook

1. Open the provided Colab notebook in your Google Colab environment.
2. Follow the notebook's instructions to mount your Google Drive and preprocess the dataset.
3. Execute the code cells in the notebook to train and test the neural network.

## Neural Network Architecture

The neural network architecture used in this project consists of the following layers:

- Input Layer: 784 neurons (corresponding to the 28x28 pixel input images)
- Hidden Layer 1: 128 neurons
- Hidden Layer 2: 64 neurons
- Output Layer: 10 neurons (for digit classification)

## Training

The neural network is trained using stochastic gradient descent (SGD) with the specified number of epochs and learning rate.

## Results

The notebook will display the training progress, including the accuracy of the model on the test data after each epoch.

## Author

- Rishabh Ranjan

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- The MNIST dataset is provided by Yann LeCun and can be found at [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/).


