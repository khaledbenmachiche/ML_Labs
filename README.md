# Machine Learning Labs Repository

This repository contains a series of lab exercises for learning and implementing core machine learning algorithms and concepts from scratch and with libraries such as `scikit-learn`. Each lab is designed to reinforce theoretical understanding through practical application, data analysis, and performance evaluation.

---

## Labs Overview

### Lab01: Logistic Regression
- Linear, Binary, Multi-class, and Multi-label Logistic Regression
- Implementation of prediction, cost, and gradient functions
- Application to Grades and bodyPerformance datasets
- Tools: Python, pandas, scikit-learn, matplotlib, Jupyter

### Lab02: Regularization and Feature Selection
- L1 and L2 regularization for logistic regression
- Feature filtering using ANOVA
- Application to diabetes prediction
- Tools: Python, pandas, scikit-learn, matplotlib, timeit

### Lab03: Naive Bayes
- Multinomial and Gaussian Naive Bayes implementations
- Prior probabilities, smoothing, and model evaluation
- Dataset: SMS Spam Collection
- Tools: Python, pandas, scikit-learn, numpy, Jupyter

### Lab04: Decision Trees and Ensemble Learning
- ID3 and CART decision tree algorithms
- Random forests and ensemble methods
- Hyperparameter tuning and visualization
- Dataset: Cars
- Tools: Python, scikit-learn, graphviz, timeit

### Lab05: Support Vector Machines and Optimization
- Primal and dual SVM formulation
- Stochastic gradient descent
- Analysis of kernels, C parameter, and problem complexity
- Datasets: Iris, synthetic Circles
- Tools: Python, scikit-learn, numpy, matplotlib, timeit

---

## Tools & Libraries
- Python 3.x
- Jupyter Notebooks
- NumPy, pandas, matplotlib
- scikit-learn
- graphviz (for tree visualization)
- timeit (for benchmarking)

---

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/khaledbenmachiche/TPs_ML.git
   cd TPs_ML
   ```

2. Create a virtual environment and install requirements:
   ```bash
   python -m venv venv
   source venv/bin/activate  # or .\venv\Scripts\activate on Windows
   pip install -r requirements.txt
   ```

3. Launch Jupyter Lab:
   ```bash
   jupyter lab
   ```

---

## Datasets

Datasets are either included in the `datasets/` folder or loaded using `sklearn.datasets`. Some examples:
- Iris
- SMS Spam Collection
- bodyPerformance
- Cars
- Synthetic datasets

---

## Contributions

This project is part of a lab series and is not currently accepting outside contributions. Feel free to fork it for your own learning purposes!

---

## License

This project is for educational purposes and does not carry a formal license.