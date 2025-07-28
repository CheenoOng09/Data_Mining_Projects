# Week 7 – Titanic Random Forest Modelling

This project uses a Random Forest Classifier to predict passenger survival from the Titanic dataset. It includes preprocessing, feature engineering, model training, and evaluation.

## Dataset

- **File:** `Titanic-Dataset.csv`
- **Source:** Contains information about passengers such as name, age, sex, fare, class, etc.
- **Target:** `Survived` column (1 = survived, 0 = did not survive)

## Tasks Completed

- Loaded and explored dataset
- Handled missing values (e.g., `Age`, `Embarked`)
- Converted categorical variables to numeric using one-hot encoding
- Split dataset into training and testing sets
- Trained a `RandomForestClassifier`
- Evaluated using classification report and accuracy

## Results

- **Accuracy:** 81.56%
- **Precision/Recall/F1 Score:**
  - Class 0 (did not survive): Precision 0.81, Recall 0.90, F1-score 0.85
  - Class 1 (survived): Precision 0.83, Recall 0.70, F1-score 0.76

## Output Screenshot

See `Results.png` for the full classification report.

## File List

- `Titanic Random Forest Modelling.ipynb` – Complete notebook with all code and output
- `Titanic-Dataset.csv` – Titanic dataset
- `Results.png` – Screenshot of model evaluation results

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- matplotlib (optional, for visualization)

## How to Run

1. Open the notebook `Titanic Random Forest Modelling.ipynb` in Jupyter Notebook or VSCode.
2. Run each cell in order.
3. Modify parameters or preprocessing to explore different model performance.
