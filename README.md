# Fast Capacity Estimation for Production-Line Screening of Inventory Battery Cells

Code and datasets for the paper:

> **Fast capacity estimation for production-line screening of inventory battery cells via combined pulsed and dynamic excitation**

---

## 1. Introduction

This repository contains the code for our paper *"Fast capacity estimation for production-line screening of inventory battery cells via combined pulsed and dynamic excitation."*

We openly release the complete dataset together with runnable, notebook-based code. The code documents, in detail, the **data preprocessing**, **feature engineering**, and **machine-learning modeling** of this work, and reports results separately and in full for both **LFP cells** and **NCM cells**.

### Repository structure

| Item | Description |
| --- | --- |
| `XJTU-EVIR Mixed-excitation datasets/` | Mixed-excitation (DC pulse + dynamic excitation) test datasets for **61 LFP cells** and **74 NCM cells**. The data are intended for the task of fast capacity screening of inventory cells. Please refer to the paper for details. |
| `features_csv/` | Feature-engineering tables for the 61 LFP cells and 74 NCM cells, ready for tabular machine-learning tasks. |
| `Pulsed-and-dynamic-excitation-based-battery-grading.ipynb` | Fully runnable source code covering feature engineering, machine-learning modeling, and the presentation of capacity-estimation results. |

### Environment

The notebook is written in Python and runs in a standard Jupyter environment. The main dependencies are:

```bash
matplotlib: 3.11.1
numpy: 2.4.0
pandas: 3.0.3
sklearn: 1.9.0
scipy: 1.18.0
```

### Usage

```bash
git clone <this-repository-url>
cd <repository-name>
jupyter notebook Pulsed-and-dynamic-excitation-based-battery-grading.ipynb
```

Run the notebook cells in order. The notebook reads the raw data from `XJTU-EVIR Mixed-excitation datasets/`, then reproduces the feature engineering, model training, and capacity-estimation results for the LFP and NCM cells.

---

## 2. Citation

If you find our code or dataset useful, please cite our paper:

```bibtex
@article{Lin2026Fast,
  title   = {Fast capacity estimation for production-line screening of inventory
             battery cells via combined pulsed and dynamic excitation},
  author  = {Lin, C. and Xu, J. and Hou, J. and Wang, W. and Ma, Z. and Mei, X.},
  journal = {Energy},
  year    = {2026},
  doi     = {10.1016/j.energy.2026.143168}
}
```

Plain-text format:

> Lin C, Xu J, Hou J, Wang W, Ma Z, Mei X. Fast capacity estimation for production-line screening of inventory battery cells via combined pulsed and dynamic excitation. Energy. https://doi.org/10.1016/j.energy.2026.143168
