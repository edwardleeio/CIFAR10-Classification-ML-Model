# CIFAR10-Classification-ML-Model

Lab 8 Documentation (Neural Networks)

Description
The program involves the creation of a neural network, a structure composed of many neurons that are organized specifically into layers as designed by the program. 
This neural network can be trained and optimized by calculating the loss with a loss function, and backpropagation to adjust the weights of the neural network based on 
the loss. These steps can be summarized into iterations called epochs. After a certain number of epochs, the neural network will ideally continue to improve until it 
performs well. The function of our neural network will be classification, in which input images will be able to be accurately classified as a type of image, which ranges
from an airplane, automobile, to flowers. 

Environment
The environment used to run these neural networks involved Google Colab instead of Anaconda. Google Colab is a free resource provided by Google through the link colab.research.google.com, the only requirement is a Gmail account. After signing up for a gmail account if you do not have one, going to that link allows the creation of python notebooks that are fully integrated into the website. The rest of the code can be run simply by dragging the .pynb (python notebook) file into the Google colab website, and it will upload it and allow immediate use of the notebook, much like Google Drive.
Below is a screenshots showing the available notebooks that you have worked on. To create a new notebook, simply click on the new notebook on the bottom right.
 
The packages involved installing primarily Tensorflow and Keras, which are two important Python libraries used in machine learning for professional machine learning applications. To install these, use !pip install, as shown in the code snippet below:
!pip install tensorflow keras h5py matplotlib numpy

Afterwards, the remaining packages should be imported:
import tensorflow as tf
import numpy as np
import os
import PIL

from tensorflow import keras
from tensorflow.keras import datasets, layers, models
from tensorflow.keras.models import Sequential
import matplotlib.pyplot as plt

Noted is that these can be inputted in the coding blocks that you can create through the + Code option amongst the Jupyter Notebook menu options. 
