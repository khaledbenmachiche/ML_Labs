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

### Lab06: Neural Networks and Backpropagation
- Implementation of activation functions (Logistic, ReLU) and BCE loss
- Neural network backpropagation from scratch (neuron, layer, network levels)
- Analysis of parameter initialization, activation functions, and optimization methods
- Experiments with TensorFlow/Keras
- Dataset: Diabetes
- Tools: Python, numpy, pandas, matplotlib, TensorFlow/Keras

### Workshop 03: Advanced Neural Networks
- Implementation of clustering algorithms with KMeans
- MLP and CNN-based auto-encoders for dimensionality reduction
- CNN-based and clustering-based classifiers
- Generative models: Variational Auto-Encoders (VAE) and Generative Adversarial Networks (GAN)
- Dataset: Pokemon images
- Tools: TensorFlow, Keras, scikit-learn, matplotlib, numpy, pandas

---

## Tools & Libraries
- Python 3.x
- Jupyter Notebooks
- NumPy, pandas, matplotlib
- scikit-learn
- graphviz (for tree visualization)
- timeit (for benchmarking)
- TensorFlow/Keras (for neural networks and deep learning)
- sklearn.cluster (for clustering algorithms)

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

4. Explore the labs and workshops:
   - Navigate to the respective lab folders (e.g., `Lab01SLQ`, `Lab02SLQ`, etc.) or workshop folders (`ML_WS_ANN_2025`).
   - Open the provided Jupyter Notebooks to follow the exercises and implementations.

---

## Datasets

Datasets are either included in the `datasets/` folder or loaded using `sklearn.datasets`. Some examples:
- Iris
- SMS Spam Collection
- bodyPerformance
- Cars
- Diabetes
- Pokemon images
- Synthetic datasets

---
