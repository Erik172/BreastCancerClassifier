# Breast Cancer Classifier using K-Nearest Neighbors

This is a breast cancer classification project using the K-Nearest Neighbors algorithm in Python. The goal of the project is to build a model that can classify tumors as either benign or malignant using a breast cancer dataset.

## Data

The data used in this project is obtained from the Wisconsin Breast Cancer dataset, available in Scikit-Learn. The dataset contains 569 samples of breast tumors with 30 features each. The features include physical measurements of the cell nuclei, such as size, shape, and texture. The target variable is a binary label indicating whether the tumor is benign or malignant.

## Requirements

- Python 3
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Implementation

The breast cancer classifier is implemented using the K-Nearest Neighbors algorithm. In summary, the algorithm works as follows: when a new sample is presented, the algorithm finds the "k" nearest data points in the training set and makes a decision based on the majority of the labels of the nearby samples.

The project is divided into several sections. First, the breast cancer data is loaded and split into a training set and a validation set. Next, the model is trained using the training set, and the performance of the model on the validation set is evaluated. Then, a sensitivity analysis of the hyperparameter "k" is performed to find the best value of "k". Finally, the model is trained with the best value of "k", and a prediction is made on the validation set.

## Results

The breast cancer classification model achieves an accuracy of 93.85% on the validation set using the best value of "k" found. It is observed that the accuracy of the model varies depending on the value of "k". For example, for k = 1, the model achieves an accuracy of 92.11%, while for k = 23, the model achieves an accuracy of 93.85%.

## Conclusions

In this project, a breast cancer classifier was implemented using the K-Nearest Neighbors algorithm in Python. A model was obtained that can classify breast tumors as benign or malignant with an accuracy of 93.85% on the validation set. The sensitivity of the model to values of "k" was also investigated, and it was found that the best value of "k" for this dataset is 23. This project may be useful for those who want to implement a breast cancer classification model using K-NN or for those interested in learning more about the K-NN algorithm in Python.