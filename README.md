## Welcome to my portfolio.
Below you can find a number of my personal projects that I've worked on recently. They tackle data science and analysis issues with machine learning, plotting, and/or data exploration techniques.

**Note**: These projects are in chronological order, so the higher a project is, the newer it is.

## Projects

### Energy Dashboard

This is a base analysis of energy consumption in buildings of various sizes.  

This is our scenario: Imagine a property owner wants to estimate which of their buildings are most likely to consume the most amount of energy. They would need to know what aspects of the building influence the energy cost the most in order to better understand their energy consumption. To do this they want to keep track of two important trends:

1. A buildings cooling load
2. A buildings heating load

Using data that contains the energy and size metrics of various buildings, I answer this question using a linear and ridge regression models. The end result being models that can predict a buildings energy consumption based on its compactness, total wall and glazing area, and overall height.  

View the notebook [here](https://github.com/zarekivey/ds-portfolio/blob/main/Energy_Dashboard/energy_dashboard.ipynb).

_Technology Used: Python, Pandas, Sklearn, Matplot, Numpy_

---

### Book Reviews

TODO

_Technology Used: Python, Numpy, Pandas_

---

### AirBnB Price Checker

This project consist of a dash app that utilizes a keras model to predict the price of an airbnb listing based on key paramaters. The data was first explored, cleaned, and visualized with the goal in mind. After determining that the data was fit for analysis, a keras model was built and then implimented into the dash app. The projects code can be found [here](https://github.com/tt-dsft-45-AirBnb).

_Technology Used: Python, Pandas, Keras, Matplot, Numpy, Dash, Heroku_

---

### Chess Analyzed

The goal of this analysis is to pinpoint optimal, and popoular sets of moves in the game of chess. This is achieved via feature extraction and visualization. After the initial anlysis, a random forest classifier model is instantiated to predict the probability of a player winning based on their elo, piece color, and initial moves. 

_Technology Used: Python, Pandas, Sklearn, Matplot, Numpy_

---

### Rent Regression

Rent Regression establishes a prediction of apartments in nyc listed on renthop.com. To achieve this I performed data analysis to determine an ideal way to structure the data for use in a regression model. After the model creation, I validated my findings through the use of regression metrics.

_Technology Used: Python, Sklearn, Numpy_
