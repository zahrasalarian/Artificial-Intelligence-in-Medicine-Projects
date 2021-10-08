# AI-Mini-Projects
## First project
The purpose of this project was to identify breast cancer in patients by using various machine learning algorithms, including Logistic Regression, SVM with linear kernel, SVM with RBF kernel, Decision Tree, and KNN.  
For the implementation of these algorithms, I used the scikit-learn library, followed by the k-fold cross validation method to assess their accuracy.  
First, to gain a better understanding of the data, I plotted single-feature diagrams and their feature pairs, and then I fitted the models to the data.  
You can access the dataset [here](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Coimbra#).

## Second project
The aim of this project is to implement a multilayer perceptron neural network to classify the cifar10 dataset.  
This model was implemented using the Keras and Tensorflow libraries.  
To pre-process the images, I first converted the pixel values from integers to decimals so that they were decimals when performing the operation and could be more accurate. Then divide them by 255.0 so that all the pixels are in the range of 0 to 1.  
The next step is to design a multilayer perceptron neural network for which the best combination of hyperparameters must be achieved. First, for a one-unit model, the number of different nodes was tested and the best one was selected. Then, different activation functions were tested and their speed and accuracy were compared, the learning rate was evaluated using different optimizers and the best one was selected. Finally, the best number of epochs and batch size were selected. In the next step, Drop out method was used to prevent over-fitting and under-fitting. Finally, after training and testing the designed model, the results were reported in the notebook.
