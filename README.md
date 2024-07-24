# microalgae-image

This repository contains the code and image material described in: Stegemüller et al. (2024) -  Online monitoring of Haematococcus lacustris cell cycle using machine and deep learning techniques

The files are organized as follows: 

'Build CNN.ipynb' contains the construction, optimization, training, validation and evaluation (SHAP) of the Convolutional Neural Network 

'Use CNN.ipynb' can be used to clasiify images using a trained Convolutional Neural Network

'Build XGBoost.ipynb' contains the construction, optimization, training, validation and evaluation (SHAP) of the Gradient Boosting Decision tree model (XGBoost)

'Use XGBoost.ipynb' can be used to clasiify images using a trained XGBoost model

'Sorted Dataset Haematococcus cell cycle' contains the dataset used for model training and validation 
  The file contains one subfolder for each class ('Greenflag', 'Greenround', 'Others', 'Redflag' and 'Redround')
[test](https://github.com/stegemlar/microalgae-image/blob/main/Sorted%20Dataset%20Haematococcus%20cell%20cycle.zip)
