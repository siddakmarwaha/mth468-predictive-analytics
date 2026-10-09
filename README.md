# MTH 468 — Predictive Analytics Projects

![Python](https://img.shields.io/badge/python-3.9%2B-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Four projects implementing core predictive-analytics methods from first principles and with scikit-learn.

**Course:** MTH 468 — Predictive Analytics  
**Term:** Spring 2024  
**Institution:** Michigan State University

## Contents

- [`projects/project1_algorithms.ipynb`](projects/project1_algorithms.ipynb) — iterative vs. recursive algorithms and complexity
- [`projects/project2_gradient_descent_regression.ipynb`](projects/project2_gradient_descent_regression.ipynb) — gradient descent learning-rate study and regression on weight data
- [`projects/project3_classification_boundaries.ipynb`](projects/project3_classification_boundaries.ipynb) — linear/quadratic decision boundaries and model diagnostics
- [`projects/project4_classification_models.ipynb`](projects/project4_classification_models.ipynb) — classification and evaluation on a target dataset

## Repository Structure

```text
mth468-predictive-analytics/
├── projects/
│   ├── BoundaryQuad.xlsx
│   ├── project1_algorithms.ipynb
│   ├── project2_gradient_descent_regression.ipynb
│   ├── project3_classification_boundaries.ipynb
│   ├── project4_classification_models.ipynb
│   ├── target.xlsx
│   └── Weight.xlsx
├── LICENSE
├── README.md
└── requirements.txt
```

## Tech Stack

Python, NumPy, pandas, scikit-learn, statsmodels, SciPy, matplotlib

## Getting Started

```bash
git clone https://github.com/siddakmarwaha/mth468-predictive-analytics.git
cd mth468-predictive-analytics
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

> **Academic integrity:** This repository contains my own submitted work for a university course and is shared as a portfolio sample. Assignment prompts and starter code belong to the course instructors. Current students should not copy this work.

## Author

**Siddak Marwaha**

## License

Code in this repository is released under the [MIT License](LICENSE). Course-provided prompts and materials remain the property of their authors.
