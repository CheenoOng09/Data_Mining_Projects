===============================
Reddit Depression Classifier
===============================

Group Members:
Mikollito Ong (林米克) - 1103558
Mlandvo - 1113523
Rey - 1111549
Zithile - 1113552

-------------------------------
How to Run:
-------------------------------
1. Open `Depression_Content_Detection.ipynb` in Jupyter Notebook.
2. Make sure all required packages are installed (see below).
3. Run the notebook cells from top to bottom.

The notebook:
- Imports necessary libraries
- Loads and cleans the dataset
- Applies NLP preprocessing (tokenization, stopword removal, POS tagging, lemmatization)
- Saves the cleaned dataset to CSV (Optional)
- Converts text to TF-IDF vectors
- Trains and evaluates Logistic Regression and Naive Bayes classifiers

-------------------------------
Required Packages:
-------------------------------
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- nltk
- scikit-learn
- matplotlib
- seaborn

To install dependencies:
1. Run the following in your Anaconda prompt or terminal:
    pip install pandas numpy nltk scikit-learn matplotlib seaborn

2. Download NLTK resources:
In the notebook, these are downloaded automatically:
    punkt, stopwords, wordnet, averaged_perceptron_tagger

-------------------------------
Output Files:
-------------------------------
- `reddit_processed_text_data.csv` – Cleaned and preprocessed dataset
