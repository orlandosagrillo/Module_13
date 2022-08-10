# Module_13

## What is Created

Predict whether Alphabet Soup funding applicants will be successful, creating a binary classification model using a deep neural network. 

## Instructions

- Preprocess data for a neural network model.
- Use the model-fit-predict pattern to compile and evaluate a binary classification model.
- Optimise the model.

## Imports Used

- import pandas as pd
- from pathlib import Path
- import tensorflow as tf
- from tensorflow.keras.layers import Dense
- from tensorflow.keras.models import Sequential
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import StandardScaler,OneHotEncoder

## Findings

#### Original Model Results

- The original model provided Loss of 0.2495381385087967, and Accuracy of 0.5343440175056458, thus indicating that the model is neither ideal or realisitic, as it does not achieve a great enough accuracy in order to be determined as a great model performance. However, it is notable that the model calculated a good loss. Loss is calculated on training and validation and its interperation is how well the model is doing for these two sets. Unlike accuracy, loss is not a percentage. 'It is a summation of the errors made for each example in training or validation sets.' Therefore the lower the loss, the better and more precise the model.

### Alternative Model 1 Results

- The 1st alternate model provided Loss of 0.690929651260376, and Accuracy of 0.5337609052658081. Much like the original model in accuracy, providing little evidence to assume that it is a great model performance. However, with such a high loss score, it is determined that the 1st alternate model will not perform as good as the original model.

Alternative Model 2 Results

- The 2nd alternate model provided Loss of 0.6908577680587769 and Accuracy: 0.5343440175056458. With almost identical values for both variables, it is safe to assume that both the 1st and 2nd model do not possess the accuracy or performance, than that of the original model, which provided a lower loss value.

