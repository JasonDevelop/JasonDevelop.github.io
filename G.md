
# Gradient decent
---
##linear regression


**hypothesis**
$$h_{\theta}(x) = \sum_{i=1}^n\theta_ix_i$$

*vectorize*    $$X*\theta$$
**cost function**
$$J(\theta) = \frac{1}{2m}\sum_{i=1}^n(h_\theta(x^i)-y^i)^2$$
**Gradient Descent**
$$\theta_j := \theta_j - \alpha\frac{\partial}{\partial \theta_j}J_\theta$$
$$gradient = \frac{\partial}{\partial \theta_j}J_\theta
=\frac{1}{m}\sum_{i=1}^n(h_\theta(x^i)-y^i)x^i_j$$

##Logistic Regression
**hypothesis**
$$h_\theta(x) = sigmoid(\theta*x) = \frac{1}{1+e^(x\theta)}=P{(y|x,\theta)}$$
**cost function**
$$J(\theta) = -\frac{1}{m}\sum_{i=1}^n[y^ilog(h_\theta(x^i))+(1-y^i)log(1-h_\theta(x^i))]$$
**Gradient Descent**

##Regularization

*optima*
*Formal Equation*









> Written with [StackEdit](https://stackedit.io/).