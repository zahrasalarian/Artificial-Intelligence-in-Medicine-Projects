# AI-Mini-Projects
## First project
The purpose of this project was to identify breast cancer in patients by using various machine learning algorithms, including Logistic Regression, SVM with linear kernel, SVM with RBF kernel, Decision Tree, and KNN.  
For the implementation of these algorithms, I used the scikit-learn library, followed by the k-fold cross validation method to assess their accuracy.  
First, to gain a better understanding of the data, I plotted single-feature diagrams and their feature pairs, and then I fitted the models to the data.  
You can access the dataset [here](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Coimbra#).

## Second project
This project aims to implement a multilayer perceptron neural network to classify the cifar10 dataset.  
The model was implemented using the Keras and Tensorflow libraries.
To pre-process the images, I first converted the pixel values from integers to decimals when operating and could be more accurate. Then divide them by 255.0 so that all the pixels are in the range of 0 to 1.
The next step is to design a multilayer perceptron neural network for which the model must achieve the best combination of hyperparameters. To do this, I selected the following hyperparameters, respectively:  
  1. Tested the number of nodes for a one-unit model, and selected the best one.  
  2. Tested different activation functions, compared their speed and accuracy, and selected the best one.    
  3. Evaluated the learning rate using various optimizers, and selected the best one.  
  4. Determined the best number of epochs and batch size.
In the end, I used the Drop Out method to prevent over-fitting and under-fitting. Finally, after training and testing the designed model, the results were reported in the notebook.
