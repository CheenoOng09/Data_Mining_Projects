# Week 10 - Midterm Project: Student Performance Prediction

## Objective
The midterm project focuses on analyzing student performance using the `student-mat.csv` dataset. The goal is to apply data mining techniques to discover useful patterns and make predictions regarding student success.

## Tasks Overview

1. **Exploratory Data Analysis (EDA)**  
   - Cleaned the dataset by handling missing values and data types.
   - Visualized correlations and key relationships using plots (e.g., heatmaps, histograms).

2. **Classification Mining (Decision Tree Classifier)**  
   - Applied a decision tree algorithm to predict whether a student will pass or fail.
   - Evaluated model accuracy and performance using metrics like accuracy, precision, recall, and F1-score.

3. **Association Rule Mining**  
   - Used the Apriori algorithm to discover patterns in categorical student data.
   - Adjusted parameters such as minimum support and confidence to refine rules.

4. **Reflection on Ethical and Societal Impact**  
   - Discussed ethical considerations of using student data.
   - Highlighted possible biases, fairness, and data privacy concerns in academic prediction models.

## Dataset
The project uses the [student-mat.csv](https://archive.ics.uci.edu/ml/datasets/Student+Performance) dataset from the UCI Machine Learning Repository, which contains information about students' academic performance and related factors.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (Decision Trees)
- mlxtend / apyori (for association rules)

## Output
The notebook includes:
- Cleaned and transformed dataset
- Performance evaluation metrics for classification
- Sample association rules with support, confidence, and lift

## File Structure
- `Student Performance_Prediction_Code.ipynb`: Main notebook containing the entire analysis and results.
- `student-mat.csv`: Dataset file used in the project.

---

**Note:** To reproduce the results, simply open the notebook in Jupyter and run all cells.
