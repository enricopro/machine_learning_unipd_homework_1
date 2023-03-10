# Linear Regression on a Combined Cycle Power Plant (CCPP) Data
This project is part of the homework assignment for the University of Padua's Computer Engineering MSc course. It is an implementation of linear regression on a Combined Cycle Power Plant (CCPP) dataset. The dataset contains hourly average ambient variables Temperature (AT), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V) to predict the net hourly electrical energy output (PE) of the plant. The data was collected over 6 years (2006-2011) from a CCPP when the plant was set to work with full load.

# Dataset Description
The dataset contains 5281 data points. In a CCPP, the electricity is generated by gas and steam turbines, which are combined in one cycle, and is transferred from one turbine to another. The Vacuum has an effect on the Steam Turbine, while the other three ambient variables affect the GT performance.

# Implementation
The implementation uses linear regression to predict the net hourly electrical energy output of the plant based on the given input features. Linear regression is a linear approach to modeling the relationship between a dependent variable and one or more independent variables.

The implementation is done in Python, using the following libraries:

- numpy
- pandas
- sklearn