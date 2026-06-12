# Privacy-Preserving Data Publishing Using Composite Scoring and Decision Support

## Overview

This project presents a comprehensive evaluation framework for Privacy-Preserving Data Publishing (PPDP) techniques.

The research evaluates three representative privacy-preserving approaches:

* k-Anonymity
* Differential Privacy
* Synthetic Data Generation

The framework integrates privacy protection, machine learning utility, and computational efficiency into a unified composite scoring model and decision-support mechanism.

---

## Research Motivation

Selecting an appropriate privacy-preserving technique is challenging because privacy, utility, and computational performance often conflict with one another.

Most existing evaluation approaches focus on only one aspect of performance.

This project introduces a multi-dimensional evaluation framework capable of comparing multiple PPDP techniques under a common experimental environment.

---

## Dataset

Adult Income Dataset

Source:
UCI Machine Learning Repository

Records after preprocessing:
30,162

---

## Methodology

Evaluation Pipeline:

1. Dataset Collection
2. Data Preprocessing
3. Feature Engineering
4. Privacy-Preserving Transformation
5. Machine Learning Model Development
6. Utility Assessment
7. Privacy Assessment
8. Computational Performance Evaluation
9. Score Normalisation
10. Composite Score Calculation
11. Decision-Support Ranking

---

## Privacy-Preserving Techniques

### k-Anonymity

Implemented using:

* Generalisation
* Quantile Binning

### Differential Privacy

Implemented using:

* Laplace Noise Mechanism

### Synthetic Data Generation

Implemented using:

* Bootstrap Sampling

---

## Machine Learning Models Evaluated

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

XGBoost achieved the strongest predictive performance and was selected for final utility evaluation.

---

## Composite Scoring Model

S = 0.4P + 0.4U + 0.2C

Where:

P = Privacy Score

U = Utility Score

C = Computational Performance Score

---

## Key Findings

Final Ranking:

1. Synthetic Data Generation
2. k-Anonymity
3. Differential Privacy
4. Original Dataset Baseline

Synthetic Data Generation achieved the highest overall composite score by balancing privacy protection, machine learning utility, and computational efficiency.

---

## Skills Demonstrated

* Privacy Engineering
* Data Privacy
* Cybersecurity Research
* Machine Learning
* XGBoost
* Data Analysis
* Feature Engineering
* Privacy Risk Assessment
* Decision Support Systems
* Technical Documentation

---

## Research Contributions

* Developed a comprehensive PPDP evaluation framework.
* Proposed a weighted composite scoring model.
* Created a decision-support ranking mechanism.
* Conducted comparative evaluation across multiple privacy-preserving techniques.
* Demonstrated practical implementation using real-world data.

---

## Author

Md. Ariful Islam

MSc Cybersecurity and Digital Forensics

University of Wales Trinity Saint David
