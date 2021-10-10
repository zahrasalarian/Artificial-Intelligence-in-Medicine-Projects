# AI-Mini-Projects
## First project: Basic Machine Learning algorithms
This project aims to identify breast cancer in patients using various machine learning algorithms, including Logistic Regression, SVM with linear kernel, SVM with RBF kernel, Decision Tree, and KNN.  
I used the scikit-learn library to implement these algorithms, followed by the k-fold cross-validation method to assess their accuracy.  
First, to better understand the data, I plotted single-feature diagrams and their feature pairs, and then I fitted the models to the data.  
You can access the dataset [here](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Coimbra#).

## Second project: Perceptron Neural Network
This project aims to implement a multilayer perceptron neural network to classify the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset.  
The model was implemented using the Keras and Tensorflow libraries.  
To pre-process the images, I first converted the pixel values from integers to decimals so that the operation results could be more accurate. Then divide them by 255.0 so that all the pixels are in the range of 0 to 1.  
The next step is to design a multilayer perceptron neural network for which the model must achieve the best combination of hyperparameters. To do this, I selected the following hyperparameters:  
  1. Tested the number of nodes for a one-unit model, and selected the best one.  
  2. Tested different activation functions, compared their speed and accuracy, and selected the best one.    
  3. Evaluated the learning rate using various optimizers, and selected the best one.  
  4. Determined the best number of epochs and batch size.  
                                  
In the end, I used the Dropout method to prevent over-fitting. Finally, after training and testing the designed model, the results were reported in the notebook.

## Third project: Convolutional Neural Network
This project aims to implement the Convolutional Neural Network on the Derma MNIST dataset.  
In the preprocessing phase, I used the over-sampling solution to deal with the imbalance of the database. In this way, with the help of an Image Data Generator, I created new photos for the class that had fewer photos, and in this way, balanced the data set. Then, with the help of Keras and TensorFlow libraries, I implemented and fitted the CNN model and chose the best hyperparameters for it.

## Forth project: Semantic Segmentation
The purpose of this project is to train a network to perform the semantic segmentation task.  
In this project, the images of [this dataset](https://warwick.ac.uk/fac/cross_fac/tia/data/hovernet/) enter the neural network, and we will have one label for each output pixel.  In the preprocessing stage, Data Augmentation must be done, and in this case, all the changes that have been made to the original image must also be done on its mask.  
I used the [Segmentation Models](https://github.com/qubvel/segmentation_models) library to access the pre-trained U-Net network. After that, with the help of fine-tuning, I first fitted only the last layer and then the whole network.
