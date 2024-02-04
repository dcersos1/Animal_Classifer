# Animal_Classifer

Dan Cersosimo | Data Scientist | k-NN Modeling

**Overview**:

This project employs a dataset from Kaggle that has a variety of animals, features, and their class (Mammals, Reptiles, Birds, etc.). The features depict traits such as fins or feathers alongside the presence or lack thereof for certain animals. I clean, prepare, and explore the data then subsequently utilize k-NN to train a model on the features with the class as the target variable. I conduct k value hyperparameter tuning via n--fold cross-validation while ensuring the stratified state of the folds. This provides the optimal k value which is then used to train the model on the stratified training set. This is tested against the test data with 100% accuracy. This trained model is then harnessed to build a tool to take in user input for an animal and its features which promptly returns the predicted class. 

**How to Run**:

The entire project is within the .ipynb file in this repository. As a result, you must be able to run Jupyter Notebooks as well as install and import the necessary libraries/functions as detailed in the file.

**Breakdown**

Contextualization 

Data Acquisition and Loading

Data Preprocessing and EDA

k-NN Modeling

Confusion Matrix Visualization 

Animal Classifier Tool

Reflection and Real-World Relevance
