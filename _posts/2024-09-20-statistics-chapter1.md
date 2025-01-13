---
layout: post
title: Statistics Chapter 2
category: Mathematics
---

# Chapter 2: Probability

## Purpose of this Chapter
This chapter introduces the foundational concepts of probability, which form the basis for statistical inference. Understanding probability allows us to quantify uncertainty and make predictions about random phenomena.

---

## 2.1 Introduction

### What Is Probability?
Probability measures the likelihood of an event occurring, expressed as a number between 0 and 1:
- \( P(A) = 0 \): Event \( A \) will not occur.
- \( P(A) = 1 \): Event \( A \) will certainly occur.
- \( 0 < P(A) < 1 \): Event \( A \) may occur with some likelihood.

---

## 2.2 Probability and Inference
Statistical inference relies on probability to:
1. Predict population characteristics based on a sample.
2. Quantify the uncertainty of conclusions.

---

## 2.3 A Review of Set Notation

### Definitions
1. **Sample Space (\( S \)):** The set of all possible outcomes.
   - Example: Rolling a die: \( S = \{1, 2, 3, 4, 5, 6\} \).

2. **Event:** A subset of the sample space.
   - Example: \( A = \{\text{rolling an even number}\} = \{2, 4, 6\} \).

3. **Union (\( A \cup B \)):** Events in \( A \), \( B \), or both.
4. **Intersection (\( A \cap B \)):** Events in both \( A \) and \( B \).
5. **Complement (\( A^c \)):** Events not in \( A \).

---

## 2.4 A Probabilistic Model for an Experiment: The Discrete Case

### Key Components
1. **Sample Space (\( S \))**
2. **Events:** Subsets of \( S \).
3. **Probability Function (\( P \)):** Assigns probabilities to events.

#### Example: Rolling a Die
- \( S = \{1, 2, 3, 4, 5, 6\} \).
- Probability of rolling an even number:
  \[
  P(\text{even}) = P(\{2, 4, 6\}) = \frac{1}{6} + \frac{1}{6} + \frac{1}{6} = \frac{1}{2}.
  \]

---

## 2.5 Calculating the Probability of an Event: The Sample-Point Method

### Formula
For a finite sample space:
\[
P(A) = \sum_{x \in A} P(x)
\]

#### Example
For a loaded die:
- \( P(1) = 0.1 \), \( P(2) = 0.2 \), \( P(3) = 0.2 \), \( P(4) = 0.1 \), \( P(5) = 0.2 \), \( P(6) = 0.2 \).
- Probability of rolling \( \{2, 4, 6\} \):
  \[
  P(\{2, 4, 6\}) = P(2) + P(4) + P(6) = 0.2 + 0.1 + 0.2 = 0.5.
  \]

---

## 2.6 Tools for Counting Sample Points

### 1. **Multiplication Rule**
If an experiment has \( k \) stages, with \( n_1, n_2, \ldots, n_k \) outcomes:
\[
\text{Total outcomes} = n_1 \cdot n_2 \cdot \ldots \cdot n_k
\]
- Example: Tossing a coin and rolling a die:
  - Coin: \( 2 \) outcomes (\( H, T \)).
  - Die: \( 6 \) outcomes.
  - Total outcomes: \( 2 \cdot 6 = 12 \).

### 2. **Permutations**
Number of ways to arrange \( n \) distinct objects:
\[
P(n, r) = \frac{n!}{(n-r)!}
\]

### 3. **Combinations**
Number of ways to choose \( r \) objects from \( n \) without regard to order:
\[
C(n, r) = \binom{n}{r} = \frac{n!}{r!(n-r)!}
\]
- Example: Choosing 2 fruits from 3 (\( A, B, C \)):
  \[
  C(3, 2) = \binom{3}{2} = \frac{3!}{2! \cdot (3-2)!} = 3.
  \]

---

## 2.7 Conditional Probability and Independence

### Conditional Probability
The probability of \( A \) given \( B \):
\[
P(A \mid B) = \frac{P(A \cap B)}{P(B)}, \quad P(B) > 0.
\]

#### Example
- \( P(A) = 0.3 \), \( P(B) = 0.4 \), \( P(A \cap B) = 0.2 \).
- \( P(A \mid B) = \frac{0.2}{0.4} = 0.5 \).

### Independence
Events \( A \) and \( B \) are independent if:
\[
P(A \cap B) = P(A) \cdot P(B).
\]

---

## 2.8 Two Laws of Probability

### 1. **Additive Rule**
For events \( A \) and \( B \):
\[
P(A \cup B) = P(A) + P(B) - P(A \cap B).
\]

### 2. **Complement Rule**
\[
P(A^c) = 1 - P(A).
\]

#### Example
- \( P(A) = 0.6 \), \( P(B) = 0.5 \), \( P(A \cap B) = 0.2 \).
- \( P(A \cup B) = 0.6 + 0.5 - 0.2 = 0.9 \).

---

## 2.10 The Law of Total Probability and Bayes’ Rule

### Law of Total Probability
For mutually exclusive events \( B_1, B_2, \ldots, B_n \) covering \( S \):
\[
P(A) = \sum_{i=1}^n P(A \mid B_i) \cdot P(B_i).
\]

### Bayes’ Rule
\[
P(B_i \mid A) = \frac{P(A \mid B_i) \cdot P(B_i)}{P(A)}.
\]

#### Example
- \( P(B_1) = 0.6 \), \( P(B_2) = 0.4 \).
- \( P(A \mid B_1) = 0.5 \), \( P(A \mid B_2) = 0.2 \).
- Find \( P(B_1 \mid A) \):
  \[
  P(A) = (0.5 \cdot 0.6) + (0.2 \cdot 0.4) = 0.38.
  \]
  \[
  P(B_1 \mid A) = \frac{0.5 \cdot 0.6}{0.38} = 0.789.
  \]

---

## 2.13 Summary
- Probability provides the mathematical foundation for statistical inference.
- Key concepts include sample spaces, events, independence, and conditional probability.
- Bayes' Rule and the Law of Total Probability are essential tools for decision-making under uncertainty.

---

## Exercises
1. A bag contains 4 red balls and 6 green balls. If two balls are drawn randomly, what is the probability that both are red?
2. In a deck of 52 cards, what is the probability of drawing a King or a heart?
3. Using Bayes’ Rule, calculate the posterior probability given:
   - \( P(B_1) = 0.7, P(B_2) = 0.3 \).
   - \( P(A \mid B_1) = 0.4, P(A \mid B_2) = 0.6 \).

