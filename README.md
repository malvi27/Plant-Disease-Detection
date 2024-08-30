# Plant-Disease-Prediction
Deep Learning Model

This project aims to detect plant diseases from images using a Convolutional Neural Network (CNN). It utilizes the TensorFlow and Keras libraries for building and training the deep learning model. The dataset used contains images of potato plants categorized into different classes representing various diseases.

The dataset used in this project is the "Potato Disease" dataset, which can be downloaded from Kaggle. It contains images of potato plants affected by different diseases as well as healthy plants.

To download the dataset, you need to set up the Kaggle API.
STEPS:

mkdir ~/.kaggle
pip install kaggle
cp kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json
! kaggle datasets download sumanrathaur/potato-disease
! unzip potato-disease.zip
