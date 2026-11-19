# Fast Capacity Estimation for Production-Line Screening of Inventory Battery Cells

Code repository for the paper:

> **Fast capacity estimation for production-line screening of inventory battery cells via combined pulsed and dynamic excitation**

---

## 1. Introduction

This repository contains the code for our paper *"Fast capacity estimation for production-line screening of inventory battery cells via combined pulsed and dynamic excitation."*

The code documents, in detail, the **data preprocessing**, **feature engineering**, and **machine-learning modeling** of this work, and reports results separately and in full for both **LFP cells** and **NCM cells**.

> **Note on the dataset:** owing to confidentiality constraints, the raw measurement data are **not** publicly released. The `XJTU-EVIR Mixed-excitation datasets/` folder is kept only as a placeholder documenting the expected directory layout. See [Data availability](#2-data-availability).

### Repository structure

| Item | Description |
| --- | --- |
| `XJTU-EVIR Mixed-excitation datasets/` | Placeholder for the mixed-excitation (DC pulse + dynamic excitation) dataset of **61 LFP cells** and **74 NCM cells**. The raw data are *not* included; the folder documents the layout the notebook expects. |
| `features_csv/` | **Included.** Feature-engineering tables for the 61 LFP and 74 NCM cells, ready for tabular machine-learning tasks. This is all that is needed to reproduce the modeling results. |
| `Pulsed-and-dynamic-excitation-based-battery-grading.ipynb` | **Included.** Runnable source code covering data preprocessing, feature engineering, machine-learning modeling, and the presentation of capacity-estimation results. |

### Environment

The notebook is written in Python and runs in a standard Jupyter environment. The main dependencies are:

```bash
matplotlib: 3.11.1
numpy: 2.4.0
pandas: 3.0.3
sklearn: 1.9.0
scipy: 1.18.0
```

## 2. Data availability

The raw measurement data will be made available on request. The code used in this work is available at https://github.com/Lin-Chuanping/Pulsed-and-dynamic-excitation-based-battery-grading.




## 3. Citation

If you find our code useful, please cite our paper:

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
