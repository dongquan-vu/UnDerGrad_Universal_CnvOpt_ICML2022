<center> <h1> UNDERGRAD: A Universal Black-Box Optimization Method with Almost Dimension-Free Convergence Rate Guarantees</h1> </center>


## How to cite:

K. Antonakopoulos, D. Q. Vu, V. Cevher, K. Y. Levy, and P. Mertikopoulos. UnderGrad: A universal black-box optimization method with almost dimension-free convergence rate guarantees. In ICML '22: Proceedings of the 39th International Conference on Machine Learning, 2022.


## Abstract:
Universal methods for optimization are designed to achieve theoretically optimal convergence rates without any prior knowledge of the problem's regularity parameters or the accurarcy of the gradient oracle employed by the optimizer. In this regard, existing state-of-the-art algorithms achieve an $\mathcal{O}(1/T^{2})$ value convergence rate in Lipschitz smooth problems with a perfect gradient oracle, and an $\mathcal{O}(1/\sqrt{T})$ convergence rate when the underlying problem is non-smooth and/or the gradient oracle is stochastic. On the downside, these methods do not take into account the problem's dimensionality, and this can have a catastrophic impact on the achieved convergence rate, in both theory and practice. Our paper aims to bridge this gap by providing a scalable universal gradient method---dubbed UNDERGRAD---whose oracle complexity is almost dimension-free in problems with a favorable geometry (like the simplex, linearly constrained semidefinite programs and combinatorial bandits), while retaining the order-optimal dependence on $T$ described above. These ''best-of-both-worlds'' results are achieved via a primal-dual update scheme inspired by the dual exploration method for variational inequalities.
