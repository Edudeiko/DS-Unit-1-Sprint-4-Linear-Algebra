# DS-Unit-1-Sprint-4-Linear-Algebra

# Linear Algebra

Linear Algebra is the foundation of nearly all the numerical routines used for practical statistics and machine learning. It’s a deep topic, but this week we’ll learn enough to appreciate how it is used and applied to the many models we’ll learn.

## Vectors and Matrices

Learning the fundamentals of linear algebra is critical in order to be a well-rounded data scientist. Many algorithm implementations are involve large amounts of Linear Algebra, so a familiarity with these topics is necessary in order to comprehend those approaches.

In this lesson we will be covering some of the most basic (yet the most important) topics in linear algebra including:

- Scalars
- Vectors
- Norm
- Dot Product
- Matrices
- Matrix Equality
- Matrix Multiplication
- Transpose
- Square Matrix
- Special kinds of Square Matrices
- Determinant
- Inverse
- Intro to NumPy for Linear Algebra

### Objectives:

- Explain why we care about linear algebra in the scope of data science
- Graph vectors, identify their dimensionality, calculate their length (norm), and take the dot product of two vectors.
- Identify the dimensionality of matrices, multiply them, identify when matrix multiplication is a legal operation, and transpose a matrix.
- Identify special types of square matrices including the identity matrix, as well as find the determinant and inverse of a matrix.
- Use NumPy to perform basic Linear Algebra operations with Python.

## Intermediate Linear Algebra

In this module we’ll do a review of some basic statistics concepts:

- Variance
- Standard Deviation
- Covariance
- Correlation

These topics will build up to a discussion about variance-covariance matrices, why they’re important and what some of their main uses are in data science. We’ll also explore some intermediate Linear Algebra topics focused on building a strong intuition in regards to working with high dimensional data. We’ll establish the concepts of:

- Orthogonality
- Unit Vectors
- Linear Independence and Span
- Basis Vectors & Orthogonal Basis
- Rank and Nullity
- Linear Projections in R^2

### Objectives:

- Visualize orthogonal projections in R^2 as being the "shadow" of a vector onto a subspace at a right angle
- Understand the differences in standardization between variance and standard deviation as well as covariance and correlation in preparation for learning about variance-covariance matrices
- Show when two vectors/matrices are orthogonal and explain the intuitive implications of orthogonality
- Rewrite any vector as a linear combination of scalars and unit vectors, give the definition for what makes a vector a "unit" vector and learn how to turn any vector into a unit vector.
- Identify the space spanned by multiple vectors by learning to identify linearly dependent vectors in both their graphical and numeric representations
- Calculate the rank of a matrix and use it to determine the span and basis for the vectors that the matrix is composed of 

## Dimensionality Reduction Techniques

One of Linear Algebra’s great strengths is its ability to represent and perform efficient computations on high dimensional data. In this module we will give a short introduction to:

- Vector transformations
- Eigenvectors and Eigenvalues
- The “Curse of Dimensionality”
If we can establish these topics sufficiently then we will have a great foundation for understanding Principal Component Analysis (PCA). PCA is a dimensionality reduction technique (feature extraction) that seeks to reduce the dimensions (columns) of a dataset while preserving the maximum amount of information (variance) possible. PCA is not an easy topic to wrap your head around, but we will demonstrate the steps for performing this technique using both numpy and sklearn and hopefully get you well on your way to “grok-ing” this popular and powerful dimensionality reduction technique.

### Objectives:

- Recognize when p > n, and why this leads to failure of certain ML models
- Recognize high dimensionality data, and can employ PCA to improve model performance
- Understand the limitations that come with projecting data onto an eigenvector subspace

## Clustering

In this module we will:

1) Get a general overview for the different categories of Machine Learning Algorithms. (Supervised vs Unsupervised, Regression vs Classification)

2) Look at our first Machine Learning algorithm which happens to be an unsupervised learning algorithm - K-Means Clustering! Why are we starting with this algorithm? Because it involves high dimensional data, typically works well when combined with PCA, and will help tie together some of the intuition that we have been working towards building over the course of the week.

3) Briefly discuss the No Free Lunch Principle (NFL) Which basically states that the more we optimize an algorithm for solving one specific kind of problem, the worse it gets at solving all other kinds of problems. This is highly pertinent to clustering algorithms, but the biggest takeaway from the NFL principle is that there is no single approach that is going to be the best for every circumstance. The tools you use have to be informed by the data that you’re working with and the context of the problem that you’re trying to solve.

### Objectives:

- Recognize when unsupervised learning is necessary, and select and apply appropriate clustering techniques
- Use K-Means clustering and other centroid-based clustering algorithms
- Articulate the "No Free Lunch Principle" and use it to guide them when searching for the appropriate ML algorithm to apply to a particular situation
