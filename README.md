# Regression Models for Outlier Handling

## RANSAC Regression
The `RANSACReg` class implements the Random Sample Consensus (RANSAC) algorithm for robust linear regression. RANSAC is particularly useful for models like linear regression when there are outliers in the dataset. This class fits a line to a set of data points, robustly handling outliers and providing a reliable estimate of the underlying linear relationship.


## Linear Regression
The `LinearReg` class provides a simple linear regression model using the closed-loop form. It fits a line to a set of data points using the pseudo-inverse method.


# Dependencies

The provided code relies on the following Python libraries:

- [NumPy](https://numpy.org/): For numerical operations and array manipulation.
- [Matplotlib](https://matplotlib.org/): For creating visualizations, such as plots.
- [scikit-learn](https://scikit-learn.org/): A machine learning library providing various tools for regression and classification tasks.
- [SciPy](https://www.scipy.org/): Used here for statistical functions.
