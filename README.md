# fpl-moneyball
A machine learning-powered Fantasy Premier League optimisation tool built in Python.

## Features

- Initial Transfer recommendations
- Most optimal long term players
- Triple Captain optimisation - uses machine learning to predict optimal week for triple captain alongside predicted returns
- Free Hit optimisation - uses machine learning to predict optimal week for free hit alongside predicted returns
- Wildcard planning - Gives optimal wildcard squad, giving all the players in your current squad that need to be sold, and those that aren't already in your squad that need to be bought
- Fixture difficulty analysis - uses FPL API's fixture difficulty tiers
- Random Forest player point prediction
- Multivariate Gaussian confidence checking

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Requests
- Jupyter Notebook

## Note

The project relies on live data from the official Fantasy Premier League API. Some functionality cannot be demonstrated until the FPL season begins because public squad and fixture endpoints are not fully populated before Gameweek 1.
