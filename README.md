# me592-robotics-project

Three ipynb files can be used to load data, perform various types of training, and evaluate results.

1. IntraRow_Navigation_CNN: this file will train the basic CNN models set up, and has largely been used to examine the results of different image transforms and optimization settings. It also contains several Autoencoder architectures and the ability to select pretrained Autoencoder models for preprocessing images before inputting them into a CNN.
2. IntraRow_Navigation_Autoencoder: this file was used to train the Autoencoder models
3. IntraRow_Navigation_AECNN: this file contains CNNs designed to recieve inputs in the form of latent layers from corresponding Autoencoders. It provides means to analyze and observe the results.

The data folder contains all images and .csv files used for generating training and testing sets.

The trained_models folder contains several trained models (all small enough to upload), including trained autoencoder models used for varying CNN applications.
