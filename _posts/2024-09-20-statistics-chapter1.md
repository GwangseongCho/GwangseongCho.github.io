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
P(\{2, 4, 6\}) = P(2) + P(4) + P(6) = 0.2 + 0.1 + 0.2 = 0.
