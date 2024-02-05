# Cats-vs.-Dogs-Image-Classification-with-Convolutional-Neural-Network
This repository contains a Python script for building a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images of cats and dogs. The model is trained on the Dogs vs. Cats dataset and can predict whether an input image is a cat or a dog.
**Key Features:**
**Data Preparation:** The script includes code for downloading the Dogs vs. Cats dataset from Kaggle, extracting the zip file, and setting up training and validation datasets using TensorFlow's image_dataset_from_directory.

**Model Architecture:** The CNN model is designed using Keras, comprising convolutional layers, batch normalization, max-pooling, and fully connected layers for effective feature extraction and classification.

**Training:** The model is trained on the training dataset for a specified number of epochs, and the training progress is visualized using matplotlib.

**Prediction:** An example code snippet demonstrates how to preprocess and predict the class (cat or dog) of a new image using the trained model.

Link to the datset used : **https://www.kaggle.com/datasets/salader/dogs-vs-cats**

**Usage:**
Clone the repository to your local machine.

Install the required dependencies. Ensure you have TensorFlow, Keras, NumPy, OpenCV, Pillow, and Matplotlib installed.
pip install tensorflow opencv-python pillow matplotlib

Run the main script (cats_vs_dogs_classification.py) to train the model and see the training progress.

Use the provided code snippet in the README to predict the class of a new image using the trained model.

Feel free to customize the script, explore different model architectures, or adapt it for other image classification tasks. Contributions and feedback are welcome!
