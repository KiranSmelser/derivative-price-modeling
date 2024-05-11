# derivative-price-modeling
> Utilizing a linear regression model in conjunction with LASSO regression to predict the price of an option.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Files](#files)
* [Usage](#usage)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
Uses SPY Options Chain data from 2020 to 2022, curated by Kyle Graupe and presented on Kaggle, to predict the price of an SPY option based on time in days until the option expires, providing a timeframe for the option's validity; the Option's implied volatility, indicating the market's forecast of the underlying stock's volatility; the number of contracts traded, reflecting the option's market activity; the highest price offered to buy and lowest price asked to sell, showing the buying and selling prices for the options; and the price at which the option can be exercised, known as the Strike Price.


## Technologies Used
- Jupyter Notebook


## Files & Folders
- main.ipynb contains exploratory data analysis and modeling.
- Results/ contains a correlation plot and scatter plots of the predictors.
- Linear Model/ contains model diagnostics and hypothesis testing.   


## Usage
Run main.ipynb and download SPY dataset. 


## Project Status
Project is: _complete_


## Acknowledgements
- This project was completed as part of coursework for DATA 467 - Intro to Applied Linear Models at the University of Arizona.


## Contact
Created by [@KiranSmelser](https://github.com/KiranSmelser).
