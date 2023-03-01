# Predicting the Highest Performing Currency Carry Trade Pairs

This repository contains code and data for predicting the highest performing currency carry trade pairs. 

## Overview

The code in this repository is based on a gradient boosted decision trees model that uses historical data to predict which currency pairs are likely to generate the highest returns when used in a carry trade strategy. The model takes into account various factors such as interest rates, exchange rates, and market volatility to make its predictions. 

The data used to train and test the model is included in the repository in the `data/` folder. The `src/` folder contains the Python scripts used to preprocess the data, train the model, and generate predictions. 

## Requirements

To run the code in this repository, you will need the following:

- Python 3.x
- NumPy
- pandas
- Scikit-learn
- Jupyter Notebook (optional, for running the example notebook)
- XGBoost

## Usage

To use the code in this repository, you can follow these steps:

1. Clone the repository to your local machine
2. Install the required dependencies
3. Open Jupyter Notebook (optional)
4. Navigate to the `src/` folder and run the `main.py` script to generate predictions
5. View the results in the `output/` folder

Alternatively, you can run the example notebook provided in the `notebooks/` folder to see a step-by-step demonstration of how to use the code.

## License

This repository is licensed under the MIT License. Please see the `LICENSE` file for more details.

## Acknowledgments

This project is an extension of my thesis, and uses data from Yahoo, Fed of St. Luis and OECD. I would like to thank the contributors of scikit-learn and pandas for their excellent libraries, as well as the Jupyter community for creating a powerful tool for data analysis and visualization and the Imperial Big Data faculty for their guidance. 

## Contact

If you have any questions or comments about this repository, please feel free to contact me at pk122@ic.ac.uk. We welcome contributions and feedback from the community.
