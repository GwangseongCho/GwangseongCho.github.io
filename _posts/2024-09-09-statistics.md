---
layout: post
title: Statistics Chapter 1
category: Mathematics
---

# Chapter 1: What Is Statistics?

## Purpose of this Chapter
This chapter establishes the foundation of statistics, explaining its purpose and role in analyzing data to make inferences. It introduces populations, samples, and the connection between statistical methods and real-world applications.

---

## 1.1 Introduction

### Definition of Statistics
Statistics is the science of:
- **Collecting** data.
- **Analyzing** data.
- **Interpreting** data.
- **Presenting** data.

Statistics aims to:
1. Make decisions under uncertainty.
2. Draw conclusions about populations based on samples.

### Real-World Applications
- **Elections:** Predicting results through surveys.
- **Medicine:** Testing drug efficacy.
- **Manufacturing:** Assessing product quality.

---

## 1.2 Characterizing a Set of Measurements: Graphical Methods

### Purpose
Graphical methods provide a visual summary of data, enabling quick insights into patterns, distributions, and variability.

### Common Graphical Methods
1. **Histograms:**
   - Visualize the frequency distribution of data.
   - Divide the range of data into equal intervals (bins).
   - Height of each bar represents frequency.

   **Example:**
   Data: \( 2.1, 2.4, 2.2, 2.3, 2.7, 2.5, 2.4, 2.6, 2.6, 2.9 \)  
   - Bins: \( [2.0, 2.2], [2.2, 2.4], [2.4, 2.6], [2.6, 2.8], [2.8, 3.0] \).  
   - Histogram:
     ```
     [2.0, 2.2] -> ▇
     [2.2, 2.4] -> ▇▇
     [2.4, 2.6] -> ▇▇▇
     [2.6, 2.8] -> ▇▇▇▇
     [2.8, 3.0] -> ▇
     ```

2. **Boxplots:**
   - Summarize data using minimum, Q1, median, Q3, and maximum.
   - Detect outliers and spread.

3. **Scatterplots:**
   - Show relationships between two variables.
   - Example: Plotting height vs. weight.

---

## 1.3 Characterizing a Set of Measurements: Numerical Methods

### Purpose
Numerical summaries describe data concisely, focusing on central tendency and variability.

### Measures of Central Tendency
1. **Mean (Average):**
   \[
   \bar{y} = \frac{1}{n} \sum_{i=1}^n y_i
   \]
   Example: For \( 85, 90, 78, 92, 88 \):
   \[
   \bar{y} = \frac{85 + 90 + 78 + 92 + 88}{5} = 86.6
   \]

2. **Median:**
   - Middle value when data are sorted.
   - Example: \( 78, 85, 88, 90, 92 \): Median = 88.

3. **Mode:**
   - Most frequent value.
   - Example: \( 85, 90, 85, 92, 88 \): Mode = 85.

### Measures of Dispersion
1. **Variance:**
   \[
   s^2 = \frac{1}{n-1} \sum_{i=1}^n (y_i - \bar{y})^2
   \]
   Example: For \( 85, 90, 78, 92, 88 \):
   - Mean \( \bar{y} = 86.6 \).
   - Variance:
     \[
     s^2 = \frac{(85-86.6)^2 + (90-86.6)^2 + \ldots}{4} = 28.3
     \]

2. **Standard Deviation:**
   \[
   s = \sqrt{s^2}
   \]

---

## 1.4 How Inferences Are Made

### Key Steps
1. Identify the population and parameter of interest.
2. Select a sample.
3. Use the sample statistic to estimate the population parameter.
4. Evaluate accuracy with tools like confidence intervals.

### Example
**Scenario:** Estimating the mean height of university students.  
- **Population:** All students at the university.  
- **Sample:** 50 randomly selected students.  
- **Statistic:** Sample mean \( \bar{X} = 170 \) cm.  
- **Parameter:** Population mean \( \mu \).

---

## 1.5 Theory and Reality

### Key Ideas
- Statistical methods model uncertainty.
- Assumptions must be validated for accurate inferences.
- Real-world data may deviate from theoretical models.

---

## 1.6 Summary

- Statistics is the science of analyzing data to make inferences.
- Graphical methods help visualize data.
- Numerical methods summarize central tendency and variability.
- Statistical inference bridges sample data and population characteristics.

---

## Exercises
1. **Construct a histogram** for the data: \( 5, 7, 8, 9, 10, 12, 12, 15, 18, 20 \).  
2. **Compute the mean, variance, and standard deviation** for the dataset: \( 3, 4, 6, 8, 10 \).  
3. Identify the **population, sample, and parameter** in this scenario:  
   - A researcher surveys 200 households to estimate the average income in City A.



