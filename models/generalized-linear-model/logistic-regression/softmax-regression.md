# Multinomial Logistic Regression

## Model

Consider the problem of classifying a feature vector x $\in \mathbb{R}^m$ to one of k classes.

The output of the model is a vector containing the estimated probabilities of x being classified as each class.

$$
h(\mathbf{x}) = \sigma(f(\mathbf{x}))
$$

Softmax function **σ**: $\mathbb{R}^k \rightarrow \mathbb{R}^k$ is defined as

$$
\theta(\mathbf{x})_i =\frac{\exp(x_i)}{\sum_j \exp(x_j)}
$$

Linear transform f: $\mathbb{R}^m \rightarrow \mathbb{R}^k$ is defined as

$$
f(\mathbf{x})=\mathbf{W}\mathbf{x} + \mathbf{b}
$$

## Training Objective

Loss function: cross-entropy loss.

