## Matrix Algebra
---
If $\bf{A}$ is a matrix:
- $A^T$ is the Transpose of $A$ gotten by switching the rows and the columns of $A$

Example:
If 
$$
A = \begin{bmatrix}
    3 & 4 & 5 \\
    6 & 7 & 8
    \end{bmatrix}
$$
then:
$$
A^T = \begin{bmatrix}
      3 & 6 \\
      4 & 7 \\
      5 & 8
      \end{bmatrix}
$$
- $A^{-1}$ is the inverse of $A$
It is important to note that for any matrix, to arrive at its inverse, the matrix must bare the following characteristics:
- (1) Is a square matrix
- (2) Is full Rank
- Rank of a matrx refers to the number of linearly independent rows or columns in the matrix.
- Trace of a matrix is sum of leading terms in the main diagonal.

## Side Note
---
Assume that the below data are observations made by a researcher for a study

|      | var1 | var2 | ...| varp|
|------|------|-----------|-----|
|Item 1|  x1  | x2   | ...| xp  |
|Item 2|  x2  | x2   | ...| ... |
|.     |   .  | .    | ...| ... |
|.     |   .  | .    | ...| ... |
|.     |   .  | .    | ...| ... |
|item n| xn   | xn   | ...| xpn |
|-------------------------------|


## Propeties of Expected Value

---
- Expected value of a constant is a constant 
$E(c) = c$
- The expected value of a constant multiplied by a random variable: 
$E(c x) = cE(x)$
- Expected value of two random variables:
$E(x_1x_2) = E(x_1)E(x_2)$


## Propeties of Variance

---
- The variance of a random variable $var(x) = E[x-E(x)]^2$
- For two randoms variables $Var(x_1 + x_2) = var(x_1)+ var(x_2)$ 
# Variance 
This measures of how far a set of variables are from the mean. 
$$
\bf{var(x)} = \frac{\sum_{i=1}^n(x_i - \bar{x})^2} {N}
$$
In the case whereby the variance of a sample is to be computed, the formula changes to:
$$
S^2 = \frac{\sum_{i = 1}^n(x_i - \bar{x})^2}{n-1}
$$
or a simple method:
$$
S^2 = \frac{\sum x_i^2 - \frac{(\sum x_i)^2}{N}} {n-1}
$$

---
### Application of Variance in Finance
In finance, variance plays a critical role in determining the volatility of an investment. The higher the variance of a given portfolio, the greater the risk.

---
# Covariance
This is the measure of how two similar variables vary together. It is similar to variance the only difference being unlike variance that looks at one variable, covariance looks at two variables.
$$
cov(x,y) = \frac{\sum_{i=1}^n(x_i -\bar{x})(y_i -\bar{y})}{N}
$$
In case of a sample:
$$
S_{xy} = \frac{\sum_{i=1}^n(x_i-\bar{x})(y_i - \bar{y})}{n-1}
$$


# Variance-Covariance Matrix
The variance-covariance matrix is atimes refeered to as the Correlation matrix. This is a type of matrix where the variances are displayed in the main diagonal while the covariance in the minor diagonal.


$$
M=
  \begin{bmatrix}
    \color{blue}{var_{1}} & \color{red}{cov_{1,2}} & \color{yellow}{cov_{1,3}} & .. & \color{maroon}{cov_{1,n}} \\
    \color{red}{cov_{2,1}} & \color{blue}{var_{2}} & cov_{2,3} & .. & cov_{2,n} \\
    \color{yellow}{cov_{3,1}} & cov_{3,2} & \color{blue}{var_{3}} & .. & cov_{3,n} \\
    ... &....&...&...&... \\
    \color{maroon}{cov_{n,1}} & cov_{n,n-1} & cov_{n,n-2} & .. & \color{blue}{var_{n}}
  \end{bmatrix}
$$
As shown in $\bf{M}$ above, each value of the matrix represents the covariance between two dimensions of the data. 

$$
cov_{i,j} = \frac{1}{n-1}\sum_{i = 1}^n(x_{ij}- \bar{x}_j)
$$
### Finding a Var - Covar Matrix

---
l


# PRINCIPAL COMPONENT ANALYSIS
---
Eigenvector as the term vector suggests is important as it shows the direction while the magnitude is determined by the eigenvalues.




$$
x_i - \sum_{i = 1}^n
$$
$$
x=\frac{1+y}{1+2z^2}
$$

$$
\int_0^\infty e^{-x^2} dx=\frac{\sqrt{\pi}}{2}
$$




