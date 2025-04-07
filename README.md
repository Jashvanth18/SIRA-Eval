# 🧠 SIRA Project - Evaluation Task for GSoC 2025

This repository contains the evaluation task completed for the **SIRA** (Symbolic Integration for Real Applications) project under the **HumanAI** umbrella organization for **Google Summer of Code 2025**.

## 📌 Project Title
**Symbolic Integration for Real Applications (SIRA)**

## 🔍 Overview

The goal of this task was to build a system that:
- Uses symbolic computation to solve differential equations
- Applies machine learning methods (e.g., regression) to model the solution
- Simulates and visualizes the system using real-world dynamic equations

This aligns with the goals outlined in the [SIRA project proposal](https://humanai.foundation/gsoc/2025/proposal_SIRA1.html).

---

## 📁 Contents

| File | Description |
|------|-------------|
| `sira_eval_notebook.ipynb` | Main Jupyter Notebook with code, explanation, and results |
| `Output_google.pdf` | Exported version of the notebook with output |
| `sira.py` | Python script version of the task |
| `README.md` | This file |

---

## 🧠 Key Features

- ✔️ Solved differential equations using **SymPy**
- ✔️ Applied **Polynomial Regression** using `scikit-learn`
- ✔️ Visualized true vs predicted results using `matplotlib`
- ✔️ Demonstrated symbolic + ML hybrid workflow
- ✔️ Verified output to match expected behavior of differential systems

---

## ⚙️ Requirements

```bash
pip install numpy matplotlib torch sympy pandas scikit-learn
