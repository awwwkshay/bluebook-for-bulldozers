
# Bluebook for Bulldozers

## Project Description

This project aims to predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers. The project is based on the [Kaggle Bluebook for Bulldozers competition](https://www.kaggle.com/competitions/bluebook-for-bulldozers/). 

## Data

The data for this project is split into three parts:

- Train.csv is the training set, which contains data through the end of 2011.
- Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012.
- Test.csv is the test set, which contains data from May 1, 2012 - November 2012.

The key fields in the train.csv file are:

- SalesID: the unique identifier of the sale
- MachineID: the unique identifier of a machine. A machine can be sold multiple times
- saleprice: what the machine sold for at auction (only provided in train.csv)
- saledate: the date of the sale

The data can be downloaded from the [Kaggle competition page](https://www.kaggle.com/c/bluebook-for-bulldozers/data).

## Installation

This project requires Python and the following Python libraries installed:

- NumPy
- Pandas
- Matplotlib
- Scikit-learn

You will also need to have software installed to run and execute a Jupyter Notebook.

## Usage

To run the notebook, you'll need to install Jupyter. If you have Python installed, you can do this by running `pip install jupyter` in your terminal. Once installed, you can start the notebook by running `jupyter notebook` in your terminal, and using the Jupyter interface in your browser to open the `.ipynb` notebook file.

## Results

The model achieved a Root Mean Squared Log Error (RMSLE) of 0.245 on the validation set. The feature importance analysis also showed what the most important features were and are visualized at the end of the jupyter notebook.
