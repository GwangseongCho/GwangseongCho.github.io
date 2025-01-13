---
layout: post
title: Statistics Chapter 7
category: Mathematics
---

# Chapter 7: Sampling Distributions

## Purpose of this Chapter
This chapter explores the concept of **sampling distributions**, which describe the behavior of sample statistics (e.g., sample mean, variance) across repeated sampling. Topics include the central limit theorem, the sampling distribution of the mean and variance, and chi-square, t, and F distributions.

---

## 7.1 Introduction

### Key Definitions:
- **Population**: The entire set of observations.
- **Sample**: A subset of the population.
- **Statistic**: A numerical measure computed from the sample (e.g., sample mean $\bar{X}$).
- **Sampling Distribution**: The probability distribution of a statistic.

---

## 7.2 The Sampling Distribution of the Mean

If $X_1, X_2, \ldots, X_n$ are independent and identically distributed (i.i.d.) random variables with mean $\mu$ and variance $\sigma^2$, then the **sample mean** is:
$$
\bar{X} = \frac{1}{n} \sum_{i=1}^n X_i.
$$

### Properties of $\bar{X}$:
1. Mean:
   $$
   E(\bar{X}) = \mu.
   $$
2. Variance:
   $$
   \text{Var}(\bar{X}) = \frac{\sigma^2}{n}.
   $$
3. Standard Error:
   $$
   \text{SE}(\bar{X}) = \frac{\sigma}{\sqrt{n}}.
   $$

---

## 7.3 The Central Limit Theorem (CLT)

The **central limit theorem** states that for a sufficiently large sample size $n$, the sampling distribution of $\bar{X}$ approaches a normal distribution, regardless of the population's original distribution:
$$
\bar{X} \sim N\left(\mu, \frac{\sigma^2}{n}\right), \quad \text{as } n \to \infty.
$$

### Practical Rule:
- The CLT is generally valid for $n \geq 30$.

---

## 7.4 The Sampling Distribution of the Variance

For a normal population with variance $\sigma^2$, the sample variance $S^2$ is:
$$
S^2 = \frac{1}{n-1} \sum_{i=1}^n (X_i - \bar{X})^2.
$$

### Chi-Square Distribution:
The sampling distribution of $(n-1)S^2/\sigma^2$ follows a chi-square distribution with $n-1$ degrees of freedom:
$$
\frac{(n-1)S^2}{\sigma^2} \sim \chi^2_{n-1}.
$$

---

## 7.5 The t Distribution

When sampling from a normal population, the **t distribution** arises when the population variance is unknown. The t-statistic is defined as:
$$
t = \frac{\bar{X} - \mu}{S / \sqrt{n}},
$$
where $S$ is the sample standard deviation.

### Properties of the t Distribution:
1. Symmetric and bell-shaped.
2. Depends on degrees of freedom ($\nu = n-1$).
3. Approaches the standard normal distribution as $n \to \infty$.

---

## 7.6 The F Distribution

The **F distribution** arises as the ratio of two independent chi-square variables divided by their degrees of freedom. If $\( X_1 \sim \chi^2_{\nu_1} \)$ and $\( X_2 \sim \chi^2_{\nu_2} \)$, then:
$$
F = \frac{\frac{X_1}{\nu_1}}{\frac{X_2}{\nu_2}} \sim F_{\nu_1, \nu_2}.
$$

### Applications:
1. Comparing variances.
2. Analysis of variance (ANOVA).

---

## 7.7 The Relationship Between the t, F, and Chi-Square Distributions

1. If $\( Z \sim N(0, 1) \)$ and $\( X \sim \chi^2_\nu \)$, then:
   $$
   t = \frac{Z}{\sqrt{X / \nu}} \sim t_\nu.
   $$
2. If $\( X_1 \sim \chi^2_{\nu_1} \)$ and $\( X_2 \sim \chi^2_{\nu_2} \)$, then:
   $$
   F = \frac{\frac{X_1}{\nu_1}}{\frac{X_2}{\nu_2}} \sim F_{\nu_1, \nu_2}.
   $$

---

## 7.8 Sampling Distributions in Practice

### Practical Considerations:
1. For small sample sizes, use the \( t \) distribution when the population variance is unknown.
2. For comparing variances, use the \( F \) distribution.

### Example:
If \( X_1, X_2, \ldots, X_5 \) are sampled from a normal population with \( \mu = 10 \) and \( \sigma^2 = 4 \), the sampling distribution of \( \bar{X} \) is:
$$
\bar{X} \sim N\left(10, \frac{4}{5}\right).
$$

---

## 7.9 Summary

This chapter introduced key concepts of sampling distributions, including:
1. The sampling distribution of the sample mean and variance.
2. The central limit theorem.
3. Special distributions such as t, chi-square, and F.
4. Applications of these distributions in hypothesis testing and estimation.

---

## Exercises

1. If $X \sim N(100, 16)$ and $n = 25$, find the probability that $\bar{X}$ lies between 98 and 102.
2. A sample of size $n = 10$ is drawn from a normal population. Compute the 95% confidence interval for the mean if $\bar{X} = 50$ and $S = 5$.
3. For two independent samples with variances $S_1^2 = 10$ and $S_2^2 = 15$, test if the variances are equal using the F distribution with $n_1 = 8$ and $n_2 = 10$.
4. Verify the relationship between the t and chi-square distributions for $t = Z / \sqrt{X / \nu}$.
5. Simulate the sampling distribution of the mean for $n = 50$ and compare it with the normal distribution.

---