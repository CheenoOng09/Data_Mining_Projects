# Depression Content Detection using Reddit Posts

This project applies Natural Language Processing (NLP) and Machine Learning to determine whether a Reddit post is **related to the topic of depression**. It was completed as a final group project for our Data Mining course.

---

## Objective

To build a classifier that can detect if a given Reddit post is **about depression**—regardless of whether the author is personally depressed. The goal is to identify and categorize content that discusses or relates to the subject of depression.

---

## Project Structure

| File | Description |
|------|-------------|
| `Depression_Content_Detection.ipynb` | Main notebook with preprocessing, feature extraction, modeling, and evaluation |
| `depression_dataset_reddit_cleaned.csv` | Cleaned dataset of Reddit posts labeled as related or unrelated to depression |
| `Data Mining Project Report_Group6.pdf` | Full written report with problem background, methodology, results, and conclusion |
| `Project Presentation.pdf` | Slide deck summarizing project goals, methods, and outcomes |
| `README.txt` | Team member contributions and setup guide (optional CLI version)

---

## Methodology

1. **Data Preprocessing**  
   - Removed noise: URLs, punctuation, and stopwords  
   - Performed tokenization and lemmatization

2. **Feature Engineering**  
   - Text was converted into numerical format using TF-IDF vectorization

3. **Model Training**  
   - Evaluated multiple classifiers including:  
     - Logistic Regression  
     - Support Vector Machine (SVM)  
     - Random Forest  

4. **Performance Metrics**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
   - Confusion Matrix

---

## Results

- The best-performing models accurately identified whether a post was about depression.
- TF-IDF with SVM and Logistic Regression yielded the most consistent results.

---

## How to Run

1. Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

2. Download or clone the repository.

3. Run the notebook:

```bash
jupyter notebook Depression_Content_Detection.ipynb
```

4. Ensure `depression_dataset_reddit_cleaned.csv` is in the same directory.

---

## Dataset

The dataset consists of Reddit posts labeled as either:
- Related to the topic of depression  
- Not related to depression

Posts are anonymized and cleaned.

---

## Group Members

See `README.txt` or `Data Mining Project Report_Group6.pdf` for team member roles and contributions.

---

## License

For academic use only.

---

Let me know if you'd like this tailored further for portfolio purposes or public release.
