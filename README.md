# Neural-networks
This project focuses on the design and implementation of deep neural networks for classification problems, with the goal of understanding how different architectures, optimization strategies, and regularization techniques affect model performance. It represents my first attempt at using neural networks to solve simple Sudoku puzzles.

In this implementation, each Sudoku grid is flattened into 81 input features. For every puzzle, one value is randomly removed and set as the target variable y. The objective is to train the model to accurately predict the missing value.

A key concept in this model is the use of a masking technique, which helps the network identify which values are missing and should be ignored during training. This is crucial because the missing values are scattered randomly across the dataset.

In the next phase of this project, I plan to modify the underlying data to observe how changes in data characteristics affect preprocessing steps and require adjustments to the model architecture to maintain performance.
