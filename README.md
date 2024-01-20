# Movie Recommender System using SVD

This repository implements a movie recommendation system using Singular Value Decomposition (SVD). The system decomposes a user-item matrix derived from movie ratings into three matrices: U, Σ, and V^T. These matrices are then utilized for recommending movies to users based on their preferences and similarity to others.


## Singular Value Decomposition (SVD)

SVD is a mathematical technique used in linear algebra and numerical analysis. It decomposes a matrix A into three matrices: U, Σ, and V^T. In the context of collaborative filtering for recommendation systems, the user-item interaction matrix is decomposed using SVD. The resulting matrices U, Σ, and V^T are employed to make recommendations for missing values in the original matrix.

## Power Iteration

Power iteration is an iterative method to find the dominant eigenvalue and corresponding eigenvector of a matrix. In the context of SVD, power iteration is used to find singular vectors and values. The algorithm converges to the dominant singular vector and value by updating vectors at each iteration.

## Deflation

Deflation is a technique used in SVD to iteratively find subsequent singular vectors and values. It involves subtracting the contributions of already computed singular vectors and values from the original matrix. This process helps in finding a series of singular vectors and values that approximate the original matrix.

## Truncation Parameter (k)

The parameter k in SVD represents the number of singular values and their corresponding vectors to retain during truncation. It determines the dimensionality of the approximation to the original matrix. The choice of k is a trade-off between dimensionality reduction and preserving information.

## Lecture

- **University:** Isfahan University - Faculty of Computer Engineering
- **Course:** Linear Algebra
- **Student Name:** Sheida Abedpour
- **Date:** January 2023

## References

- [Towards Data Science](https://towardsdatascience.com/simple-svd-algorithms)
- [SJTU Linear Algebra Course](http://ins.sjtu.edu.cn/people/leili/teaching/sjtu)
- [YouTube Tutorials](www.youtube.com)
- [GitHub Resources](https://github.com/RRisto/learning/blob/master/linear_algebra_learn/PCA_SVD/power_method.ipynb)

