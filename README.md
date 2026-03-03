CNN Cat vs Dog Classifier

Project Overview:

In this project, I built a Convolutional Neural Network (CNN) model to classify images of cats and dogs. The main goal was to understand how CNNs work in real image classification problems and to implement the complete pipeline using TensorFlow/Keras in Google Colab.

This project helped me practically explore concepts like convolution, pooling, overfitting control, and model evaluation.

Objective:

* To build a binary image classifier using CNN
* To distinguish between cat and dog images
* To gain hands-on experience with deep learning for computer vision
* To evaluate model performance on unseen data

Model Architecture:

The model is a simple yet effective CNN that includes:

* Convolutional layers for feature extraction
* MaxPooling layers to reduce spatial dimensions
* Dropout layer to reduce overfitting
* Fully connected (Dense) layers for final prediction
* Sigmoid activation function for binary classification

Dataset:

The dataset consists of images of cats and dogs arranged in train and test folders.
I used Keras `image_dataset_from_directory` to load and preprocess the images.

Note: The dataset is not uploaded to GitHub due to size limitations.

Technologies Used:

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Google Colab

How to Run the Project

Step 1: Clone the repository
git clone https://github.com/annieannie12345/cnn-cat-dog-classifier.git

Step 2: Install dependencies
pip install -r requirements.txt

Step 3: Open and run the notebook
Run all cells in Google Colab or Jupyter Notebook.

Results:
The trained CNN model is able to classify whether an input image is a cat or a dog with good accuracy on the validation set.

Future Improvements

In future, I plan to:

* Apply data augmentation
* Experiment with transfer learning (VGG16, ResNet)
* Perform hyperparameter tuning
* Deploy the model using Streamlit

Author:
Anisha Gupta
M.Tech (Artificial Intelligence)
