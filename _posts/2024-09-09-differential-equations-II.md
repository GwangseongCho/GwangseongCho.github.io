---
layout: post
title: Differential Equations II
category: Mathematics
---

# Pre-chapter: Linear Algebra Review

### System of Linear Algebraic Eqautions

A set of n simultaneous linear algebraic eqautions in n variables

$$ a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n = b_1,\\
\vdots\\
a_{n1}x_1 + a_{n2}x_2 + \cdots + a_{nn}x_n = b_n$$

can be written as 
$$\mathbf{Ax = b}$$

### Homogenenous Equation

If **b** = 0, the system is said be to **homogeneous**; otherwise, it is **nonhomogeneous**

### Singularity

If the coefficient matrix A is **nonsingular**$-$that is, if det $\mathbf{A}$ is not zero$-$then there is a unique solution of the system. Since $\mathbf{A}$ is nonsingular, $\mathbf{A^{-1}}$ exists, and the solution can be found by multiplying each side of $\mathbf{Ax = b} $ on the left by $\mathbf{A^{-1}}$; thus 
$$\mathbf{x = A^{-1}b}$$
In particular, the homogeneous problem $\mathbf{Ax = 0}$, has only the trivial solution.
- A trivial solution is when $\mathbf{x = 0}$

On the other hand, if A is singular$-$that is, if det $\mathbf{A}$ is zero$-$then solution do not exist, or do exist but are not unique. Since $\mathbf{A}$ is singular,  $\mathbf{A^{-1}}$ does not exist, $\mathbf{x = A^{-1}b}$ is no longer valid.
Also, the homogenouse system $\mathbf{Ax = 0}$ has infinitely many solutions in addition to the trivial solution.

### Linear Independence
A collection of $k$ vectors **$\mathbf{x}^{(1)} ,  \cdots , \mathbf{x}^{(n)}$** is said to be linearly dependent if there exists a set of real or complex numbers $c_1, \cdots , c_n$ at least one of whice is nonzero, such that 
$$ c_1 $$


### Linear Transformation

### Matrix Inverse & Transpose

### Null Space

### Column Space

### Bases

### Spanning Set Theorem

### Rank & Dimension

### Eigenvalues & Eigenvector & Eigenspace