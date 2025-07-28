# Week 11 – Hierarchical Modeling

This project implements hierarchical clustering on a dataset of student test scores and school-related attributes to discover natural groupings among schools.

## Objective

Apply hierarchical clustering to group schools based on performance and environment metrics. The resulting dendrogram reveals which schools are more similar based on key features.

---

## Steps Performed

1. **Aggregate Data**  
   Data was grouped at the `school_id` level to compute average test scores and study hours. Categorical fields like `school_funding` and `urban` were taken as-is.

2. **Standardize Features**  
   All numerical features were standardized using `StandardScaler` to ensure fair distance-based clustering.

3. **Perform Clustering**  
   The `scipy.cluster.hierarchy.linkage()` function was used with the `ward` method to compute clusters.

4. **Plot Dendrogram**  
   A dendrogram was generated using `dendrogram()` to visualize the hierarchy of school clusters.

---

## Files

- `Hierarchical Modeling.ipynb` – Jupyter notebook containing the full implementation and dendrogram plot.
- `student_scores.csv` – Dataset with fields: `school_id`, `test_score`, `study_hours`, `school_funding`, and `urban`.
- `Instructions.txt` – Step-by-step task instructions from the instructor.

---

## Requirements

Install necessary libraries using pip if you haven't:

```bash
pip install pandas matplotlib seaborn scipy scikit-learn
```

---

## Output

The dendrogram shows how schools group together based on standardized performance and context features. It helps identify similar or outlier schools.

---
