# Predicting the Highest Performing Currency Carry Trade Pairs

This repository contains code and data for predicting the highest performing currency carry trade pairs. 

## Overview

The code in this repository is based on a gradient boosted decision trees model that uses historical data to predict which currency pairs are likely to generate the highest returns when used in a carry trade strategy. The model takes into account various factors such as interest rates, exchange rates, and market volatility to make its predictions. 

The data used to train and test the model is included in the repository in the `data/` folder. The `src/` folder contains the Python scripts used to preprocess the data, train the model, and generate predictions. 

##Theory 

###Currency Carry Trade

A currency carry trade is an investment strategy in which an investor takes advantage of the interest rate spread of two countries to generate excess profit (Eun & Resnick, 2011). The underlying concept of the carry trade involves buying the high interest-bearing asset and selling the low interest-bearing one, profiting on the difference. Nonetheless, under the assumptions of perfect capital mobility and substitutable riskiness and liquidity (Madura, 2007), such investment opportunities should follow a no-arbitrage condition and therefore, investors should be indifferent between which interest-bearing instrument they purchase. This no–arbitrage condition is also known as Interest rate parity.


###Forward Premium Puzzle

Hansen and Hodrick (1980) were among the first researchers who investigated the relationship between exchange rates and interest rate specifically using a large data sample. Their findings show a systematic violation of the uncovered interest rate parity. This relates directly to the previous paragraph as it suggests that excess profits on currency trades can be made. In 1984, Fama investigated the relationship between exchange rates and interest rates further. Fama not only found a violation of the no-arbitrage clause, but he also found that countries that have higher interest rates tend to have their currency appreciate instead of depreciate against the lower interest rate currencies. Fama coined the term Forward Premium puzzle for this phenomenon. The violations of uncovered Interest rate parity have only become more egregious since the 2008 financial crisis (Du et al., 2018), potentially creating more profitable trading opportunities.

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
