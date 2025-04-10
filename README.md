# Titanic Survival Prediction

This project uses a neural network implemented in PyTorch to predict passenger survival on the Titanic, based on the famous Kaggle competition dataset.

## Overview

This notebook (`Titanic_model01 (1).ipynb`) details the process of building and training a neural network to predict passenger survival on the Titanic. It includes data loading, preprocessing, model definition, training, evaluation, and submission file generation.

## Project Structure

*   `Titanic_model01 (1).ipynb`: Jupyter Notebook containing the entire project code, from data preprocessing to model training and evaluation.
*   `train.csv`: The training dataset from the Kaggle competition.
*   `test.csv`: The test dataset from the Kaggle competition.
*   `submission.csv`: The generated submission file in the format required by Kaggle. (This is created when the notebook is run)
*   `README.md`: This file, providing an overview of the project and instructions for running the code.

## Dependencies

*   Python 3
*   PyTorch (>=1.10.0)
*   NumPy (>=1.21.0)
*   Pandas (>=1.3.0)
*   Scikit-learn (>=0.24.0)
*   Matplotlib (>=3.4.0)

You can install these dependencies using `pip`:

```bash
pip install torch numpy pandas scikit-learn matplotlib
