# CS-5703 • Machine Learning Practice (MLP)
### Assignment & Project Notebook Collection

> **University of Oklahoma – Spring 2025**  
> Maintainer: **Naveen Jajapur**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python 3.9 | 3.10 | 3.11](https://img.shields.io/badge/python-3.9%20%7C%203.10%20%7C%203.11-blue.svg)](https://www.python.org/)

---

## 📂 Repository layout

<details>
<summary><strong>(click to expand)</strong></summary>

~~~text
.
├── hwA_linear_regression.ipynb
├── hwB_logistic_classification.ipynb
├── hwC_neural_nets.ipynb
├── hwD_unsupervised_clustering.ipynb
├── hwE_feature_engineering.ipynb
├── hwF_model_interpretation.ipynb
├── hwG_holistic_cv_grid_search.ipynb
├── helpers/                        # Re-usable Python utilities
├── data/                           # Tiny, public sample data sets
├── requirements.txt                # pip dependency list
├── environment.yml                 # Conda environment definition
└── .github/
    └── workflows/
        └── notebook-test.yml       # GitHub Actions CI workflow
~~~

</details>

---

## 🚀 Quick-start (pip + venv)

```bash
git clone https://github.com/nvn-jajapur/CS-5703-MLP.git
cd CS-5703-MLP

python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook          # or: jupyter lab
