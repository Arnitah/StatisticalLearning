# Statistical Learning

This repository contains implementations and scripts aligned with the textbook **"An Introduction to Statistical Learning" (ISLR)**, applying statistical techniques to analyze banking data. The final project focuses on using **bank marketing data** to track customer subscriptions. Both **R** and **Python** are utilized for the analyses and models.

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [File Structure](#file-structure)
4. [Getting Started](#getting-started)
5. [Tools and Libraries Used](#tools-and-libraries-used)
6. [Future Scope](#future-scope)
7. [License](#license)
8. [Acknowledgments](#acknowledgments)

---

## Overview
The repository includes:
- Scripts that follow the statistical techniques outlined in **"An Introduction to Statistical Learning".**
- Applications of various models and statistical methods to analyze **banking marketing data**.
- Final project analyzes customer subscriptions based on marketing campaigns, providing insights and visualization.

Topics covered include:
- Data preprocessing and exploratory data analysis (EDA).
- Regression techniques (linear regression, logistic regression).
- Classification methods (decision trees, random forests, support vector machines).
- Statistical modeling and hypothesis testing.

---

## Features
- **ISLR Chapter Implementation:** Practical scripts replicating statistical techniques from the textbook.
- **Banking Data Analysis:**
  - Feature engineering, data cleaning, and visualization of banking datasets.
  - Customer subscription prediction based on marketing data.
- **Multi-language Support:**
  - Scripts written in both **R** and **Python** to leverage the strengths of both languages.

---

## File Structure
```
├── analysis/               # Contains statistical analysis scripts by ISLR chapters
├── datasets/               # Banking marketing datasets for analysis
├── final_project/          # Scripts, models, and reports for customer subscription analysis
├── python_scripts/         # Python code for textbook and project implementations
├── r_scripts/              # R code for textbook and project implementations
├── README.md               # Repository overview
```

---

## Getting Started
To get started with the repository, clone it and set up the environment:

### Clone the Repository
```bash
git clone https://github.com/Arnitah/StatisticalLearning.git
cd StatisticalLearning
```

### Install Dependencies
Python dependencies are described in the `requirements.txt` file:
```bash
pip install -r requirements.txt
```
Install required libraries for R:
```r
install.packages(c("tidyverse", "caret", "randomForest"))
```

---

## Tools and Libraries Used
### Python Components:
- **Data Analysis**: pandas, NumPy
- **Visualization**: matplotlib, seaborn
- **Modeling**: scikit-learn, statsmodels

### R Components:
- **Data Analysis**: tidyverse, dplyr
- **Visualization**: ggplot2
- **Modeling**: caret, randomForest

---

## Future Scope
- Add advanced statistical techniques from ISLR chapters (e.g., PCA and clustering analysis).
- Enhance analysis with more real-world finance datasets.
- Deploy final project models with a user-friendly web interface.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **"An Introduction to Statistical Learning" (ISLR)** for inspiring the techniques and analyses.
- Banking Dataset: Sourced from [UCI Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).
- Community contributors for additional insights and improvement.

---

Feel free to contribute by submitting issues or pull requests. Happy learning!
