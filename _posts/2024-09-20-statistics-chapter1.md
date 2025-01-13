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

## 2.3 A Review of Set Notation

### Definitions
- **Sample Space (\( S \))**: The set of all possible outcomes.
  Example:
  $$ S = \{1, 2, 3, 4, 5, 6\} $$

- **Event**: A subset of the sample space. Example:
  $$ A = \{\text{rolling an even number}\} = \{2, 4, 6\} $$

- **Union** (\( A \cup B \)): Events in \( A \), \( B \), or both.

- **Intersection** (\( A \cap B \)): Events in both \( A \) and \( B \).

- **Complement** (\( A^c \)): Events not in \( A \).

---

## 2.5 Calculating the Probability of an Event

For a finite sample space:
$$
P(A) = \sum_{x \in A} P(x)
$$

Example:
For a loaded die where:
$$
P(1) = 0.1, \, P(2) = 0.2, \, P(3) = 0.2, \, P(4) = 0.1, \, P(5) = 0.2, \, P(6) = 0.2,
$$
the probability of rolling \( \{2, 4, 6\} \) is:
$$
P(\{2, 4, 6\}) = P(2) + P(4) + P(6) = 0.2 + 0.1 + 0.2 = 0.5.
$$

---

## 2.7 Conditional Probability and Independence

### Conditional Probability
The probability of \( A \) given \( B \):
$$
P(A \mid B) = \frac{P(A \cap B)}{P(B)}, \quad P(B) > 0.
$$

Example:
If:
$$
P(A) = 0.3, \, P(B) = 0.4, \, P(A \cap B) = 0.2,
$$
then:
$$
P(A \mid B) = \frac{0.2}{0.4} = 0.5.
$$

---

### Independence
Events \( A \) and \( B \) are independent if:
$$
P(A \cap B) = P(A) \cdot P(B).
$$

---

## Exercises
1. A bag contains 4 red balls and 6 green balls. If two balls are drawn randomly, what is the probability that both are red?
2. In a deck of 52 cards, what is the probability of drawing a King or a heart?
