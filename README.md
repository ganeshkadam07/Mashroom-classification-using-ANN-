# Mashroom-classification-using-ANN-

Mushroom Classification using Artificial Neural Networks (ANN)
This project is an implementation of a mushroom classification system using Artificial Neural Networks (ANN). The goal of this project is to train a model that can accurately classify mushrooms as edible or poisonous based on their features.

Dataset
The dataset used for this project is the Mushroom Classification Dataset, which can be obtained from the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Mushroom). The dataset contains a collection of samples of different species of mushrooms, each described by various attributes such as cap shape, cap color, odor, etc. The target variable indicates whether the mushroom is edible or poisonous.

Prerequisites
Before running the code, make sure you have the following dependencies installed:

Python 3.x
numpy
pandas
scikit-learn
Keras
matplotlib
You can install the dependencies using pip:

bash
Copy code
pip install numpy pandas scikit-learn keras matplotlib
Usage
Clone this repository to your local machine or download the source code as a ZIP file.
bash
Copy code
git clone https://github.com/ganeshkadam07/Mashroom-classification-using-ANN.git
Navigate to the project directory.
bash
Copy code
cd mushroom-classification-ann
Run the mushroom_classification_ann.py script to train and evaluate the ANN model.
bash
Copy code
python mushroom_classification_ann.py
The script will preprocess the dataset, split it into training and testing sets, train the ANN model, and evaluate its performance. The accuracy of the model on the test set will be displayed in the console.

Additionally, the script will generate a file named mushroom_ann_model.h5 that contains the trained ANN model.

File Description
mushroom_classification_ann.py: The main script file that implements the mushroom classification using ANN.
mushroom_ann_model.h5: The trained ANN model saved in HDF5 format.
README.md: The README file providing information about the project.
Results
The ANN model achieves an accuracy of approximately 98% on the test set, indicating its ability to classify mushrooms as edible or poisonous based on their features.
