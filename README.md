# Linear-Regression-Implimentation-from-scratch
Linear Regression implemented from scratch using Python and NumPy to understand the mathematics and optimization behind the model.

## What I Implemented

* Linear regression model
* Mean Squared Error (MSE) loss function
* Partial derivatives
* Gradient descent
* Vectorized gradient calculations
* Model training
* Prediction

## Mathematics

The model is based on:

**Prediction:**

```math
\hat{y} = wx + b
```

**Loss function:**

```math
L(w,b) = \frac{1}{m}\sum_{i=1}^{m}(\hat{y}^{(i)}-y^{(i)})^2
```

The parameters are updated using gradient descent:

```math
w := w - \alpha \frac{\partial L}{\partial w}
```

```math
b := b - \alpha \frac{\partial L}{\partial b}
```

The implementation also uses vectorized operations with NumPy to perform the calculations efficiently.

## Purpose

The main goal of this project was not simply to use a pre-built machine learning library, but to understand what happens mathematically during the training of a linear regression model.

This project helped connect concepts from **Calculus and Linear Algebra** with a practical machine learning algorithm.

## Technologies

* Python
* NumPy
* Matplotlib

## Next Steps

* Multivariable Linear Regression
* Regularization
* More machine learning algorithms

## Author

**Sithum Amayuru**
