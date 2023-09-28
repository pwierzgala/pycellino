#########
Changelog
#########

*****
0.2.1
*****

Changed:

-   Data type of predicted values in regression methods is now set to the data type of column for
    which values were predicted. This change was introduced because of the warning raised by
    pandas 2.1.0: "FutureWarning: Setting an item of incompatible dtype is deprecated and will
    raise in a future error of pandas."

*****
0.2.0
*****

Added:

-   Classes `RegressionBase`, 'LinearRegression`, `PolynomialRegression`, `PowerRegression`,
    `ExponentialRegression`.


*****
0.1.0
*****

Added:

- Function `group_feature_values`.
