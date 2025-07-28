# Week 6: Decision Tree Practice

This notebook introduces the basic usage of the `DecisionTreeClassifier` in Python using `scikit-learn`. The dataset provided (`ex3 dataset for decision tree.csv`) is used to build and visualize a decision tree with controlled depth and sample split size.

---

## Files

- `Decision Tree.ipynb` – Main notebook where the decision tree is implemented and visualized.
- `ex3 dataset for decision tree (1).csv` – Dataset for training and evaluation.
- `Instruction.txt` – Assignment prompt.

---

## Instructions

According to the task:

1. Implement a **`DecisionTreeClassifier`** using the provided dataset.
2. Use **`plot_tree()`** to visualize the tree.
3. Limit the tree to **no more than 4 layers** using `max_depth`.
4. Experiment with the parameters `max_depth` and `min_samples_split`.

---

## What Was Done

- Loaded the dataset and preprocessed it using pandas.
- Trained a `DecisionTreeClassifier` with `max_depth` and `min_samples_split` specified.
- Plotted the decision tree using `plot_tree()` with `max_depth=4` or less.
- Included visual output to show the resulting tree.

---

## Libraries Used

- `pandas`
- `numpy`
- `sklearn.tree`
- `matplotlib.pyplot`

---

## Output

- A visual snapshot of the decision tree was generated within the notebook using `plot_tree()`.

---

## Note

This is a basic hands-on exercise to understand how hyperparameters like `max_depth` and `min_samples_split` affect the complexity of the decision tree and its ability to generalize.

---
