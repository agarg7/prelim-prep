We know $Y$ is a guassian:

$$
Y \sim N (X \beta, \Sigma)
$$

We can compute the mean and variance of the residual:

$$
E = (I - X(X'WX)^{-1}X'W)XB = XB -XB  =0 \\
V = Q\Sigma Q^T\\
R \sim M(0, Q\Sigma Q^T)
$$

We can simplify $Q\Sigma Q = Q\Sigma$ (what i was missing in my explanation live) using the the fact $\Sigma = W^{-1}$:

$$
Q\Sigma Q^T = (I - X(X'WX)^{-1}X'W) \Sigma Q^T\\
= (\Sigma - X(X'WX)^{-1}X') Q^T\\
= (\Sigma - X(X'WX)^{-1}X') (I - X(X'WX)^{-1}X'W)^T\\
= \Sigma 
- \Sigma (X(X'WX)^{-1}X'W)^T
  - X(X'WX)^{-1}X' 
   + X(X'WX)^{-1}X') (X(X'WX)^{-1}X'W)^T\\
= \Sigma - X(X'WX)^{-1}X'\\
= Q\Sigma\\
$$

This is moslty just expanding and canceling the linear algebra. There is probably a simpler proof of this possible, and the unsimplified form is a valid solution

$$
E[R'\Delta R] = tr(\Delta Q\Sigma Q^T ) = tr(\Delta Q\Sigma )\\
Var[R'\Delta R] = 2tr((\Delta Q\Sigma Q^T)^2 ) =2tr((\Delta Q\Sigma )^2 ) \\
$$

This last step follows from simply plugging into the trace properties in the hint(see solution)
