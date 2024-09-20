---
layout: post
title: Differential Equations II
category: Mathematics
---

# Pre-chapter: Linear Algebra Review

### System of Linear Algebraic Eqautions

A set of n simultaneous linear algebraic eqautions in n variables

$$
a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n = b_1,\\
\vdots\\
a_{n1}x_1 + a_{n2}x_2 + \cdots + a_{nn}x_n = b_n
$$

can be written as

$$
\mathbf{Ax = b}
$$

### Homogenenous Equation

If **b** = 0, the system is said be to **homogeneous**; otherwise, it is **nonhomogeneous**

### Singularity

If the coefficient matrix A is **nonsingular**$-$that is, if **det $\mathbf{A}$ is not 0** $-$ then there is a unique solution of the system. Since $\mathbf{A}$ is nonsingular, $\mathbf{A^{-1}}$ exists, and the solution can be found by multiplying each side of $\mathbf{Ax = b} $ on the left by $\mathbf{A^{-1}}$; thus

$$
\mathbf{x = A^{-1}b}
$$

In particular, the homogeneous problem $\mathbf{Ax = 0}$, has only the trivial solution.
- A trivial solution is when $\mathbf{x = 0}$

On the other hand, if A is **singular** $-$ that is, if **det $\mathbf{A}$ is 0** $-$then solution do not exist, or do exist but are not unique. Since $\mathbf{A}$ is singular,  $\mathbf{A^{-1}}$ does not exist, $\mathbf{x = A^{-1}b}$ is no longer valid. <br>
Also, the homogenouse system $\mathbf{Ax = 0}$ has infinitely many solutions in addition to the trivial solution.

> **Example 1**
> 
> <p>$A = \begin{bmatrix} 3 & 6 \\ 2 & 4 \end{bmatrix}$  is a singular matrix because</p>
> $\det(A) = 3 \times 4 - 6 \times 2 = 12 - 12 = 0$

### Linear Independence

A set of vectors ${v_1, v_2,\cdots, v_k}$ is **linearly independent** if the vector equation 

$$
x_1v_1 + x_2v_2 + \cdots + x_kv_k = 0
$$

has only the trivial solution $x_1 = x_2 = \cdots = x_k = 0$.<br>
A set of vectors ${v_1, v_2,\cdots, v_k}$ is **linearly dependent** if the vector equation 

$$
x_1v_1 + x_2v_2 + \cdots + x_kv_k = 0
$$

has non-trivial solution.

> **Example 1**
> 
> <p>Are the vectors  $v_1 = \begin{bmatrix} 1 \\ 4 \\ 5 \end{bmatrix}, v_2 = \begin{bmatrix} 10 \\ 2 \\ 1 \end{bmatrix}, v_3 = \begin{bmatrix} -5 \\ 0 \\ 6 \end{bmatrix}$  linearly independent?<p>
> then,
> $c_1 \begin{bmatrix} 1 \\ 4 \\ 5 \end{bmatrix} + c_2 \begin{bmatrix} 10 \\ 2 \\ 1 \end{bmatrix} + c_3 \begin{bmatrix} -5 \\ 0 \\ 6 \end{bmatrix} = \begin{bmatrix} 0 \\ 0 \\ 0 \end{bmatrix} $
> 
> <p>$\begin{bmatrix} 1 & 10 & -5 \\ 4 & 2 & 0 \\ 0 & 1 & 6 \\ 0 & 0 & 0 \end{bmatrix} $<p>

### Linear Transformation

A **linear transformation** is a transformation $T : R^{n} \rightarrow R^n$ satisfying 

$$
T(u+v) = T(u) + T(v)\\
T(cu) = cT(u)
$$


### Matrix Inverse & Transpose

### Null Space

### Column Space

### Bases

### Spanning Set Theorem

### Rank & Dimension

### Eigenvalues & Eigenvector & Eigenspace